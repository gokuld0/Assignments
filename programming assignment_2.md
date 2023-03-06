```python
k=int(input(""))
miles=k*3
print(miles)
```

    9
    27
    


```python
c=int(input(""))
f=c*9/5+32
print(f)
```

    7
    44.6
    


```python
import calendar
yy =int(input("enter the year"))
mm = int(input("enter the month"))
print(calendar.month(yy, mm))
```

    enter the year2016
    enter the month10
        October 2016
    Mo Tu We Th Fr Sa Su
                    1  2
     3  4  5  6  7  8  9
    10 11 12 13 14 15 16
    17 18 19 20 21 22 23
    24 25 26 27 28 29 30
    31
    
    


```python
import cmath
a = 1
b = 5
c = 6
d = (b**2) - (4*a*c)
sol1 = (-b-cmath.sqrt(d))/(2*a)
sol2 = (-b+cmath.sqrt(d))/(2*a)
print('The solution are {0} and {1}'.format(sol1,sol2))
```

    The solution are (-3+0j) and (-2+0j)
    


```python
x = 5
y = 10
x, y = y, x
print("x =", x)
print("y =", y)
```

    x = 10
    y = 5
    


```python

```
