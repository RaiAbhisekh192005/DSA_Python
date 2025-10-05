Quesiton : in this given porblem we have to find the factors of the number given to us 
sol:

this is the code for the problem 
apprich:
  we are going tio take a num and then usiong a for loop of the num and check it the remander is 
  equal to 0 then we can say that it is a factor

```
num = 7

i = 1

for n in range(num):
    a = num % i
    if a == 0:
        print(i, 'it is afactor')
    else:
        pass
    i += 1
```

2 Approch 
in this approch we are not going to get to ever no rather than we are going just the half of it 
for ex -    32/2  = 16 we will go upto 16 only to check the factore for it

```
num = 58


for n in range(1, num//2 + 1):
    if num % n == 0:
        print(n,'is a factor')
        
print(num, ' this is factor')
```
