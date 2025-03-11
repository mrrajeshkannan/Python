# Hacker Rank challenges



[Python If-Else](https://www.hackerrank.com/challenges/py-if-else/problem)


```python
import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(input().strip())
if n % 2 == 1:
    print("Weird")
elif 2 <= n <= 5:
    print("Not Weird")
elif 6 <= n <= 20:
    print("Weird")
else:
    print("Not Weird")
    
```

<br /> 


[python-arithmetic-operators](https://www.hackerrank.com/challenges/python-arithmetic-operators/problem)


```
if __name__ == '__main__':
    a = int(input())
    b = int(input())
    add=a+b
    sub=a-b
    mul=a*b
    print(add)
    print(sub)
    print(mul)
    
```
<br /> 



[python-division](https://www.hackerrank.com/challenges/python-division/problem)


```
if __name__ == '__main__':
    a = int(input())
    b = int(input())
    
    int_div=a//b            # getting Integer values 
    float_div=a/b            # Getting Float value
    
    print(int_div)
    print(float_div)
    
```

<br /> 



[python-loops](https://www.hackerrank.com/challenges/python-loops/problem)


```
if __name__ == '__main__':
    n = int(input())
    for i in range(0,n):        # for Loop   and range basically print 0 to nth value
        sqr=i*i                    # Square root 
        print(sqr)
    
```

<br /> 






[write-a-function](https://www.hackerrank.com/challenges/write-a-function/problem)


```
def is_leap(year):                # Find Leap year
    leap = False
    
    # Write your logic here
    if (year % 400 == 0) or (year % 4 == 0 and year % 100 != 0):        # Leap year logic
        leap = True
    return leap

year = int(input())
print(is_leap(year))
    
```

<br /> 
