# here we are counting the no of digits in a integer
there are bascially 2 ways of 

- Using the loop
- using the (log10) maths function

1 using loop
```
n = 34567
num = n
count = 0
while num > 0 :
  count += 1           # incease the count 
  nuum = num // 10     # updating the no in the int form 
print(count)
```

2 the log maths fucntion

```
from math import *
def countDigit(num):
    return int(log10(num)+1)
```

