# Check if a Number is Palindrome or Not

in this we check the no is plaindrome of not

the code for this is 
```
n = 1234

num = n
result = 0

while num > 0:
    ld = num % 10
    result = (result * 10) + ld 
    num = num // 10
    
print(n == result)
```


if the you want to cheak that a string is plaindrome or not
we can reverse the string and cheak it it is or not

the code for the reverse of the string is
```
line = "nitin"

reverse = (line[::-1])  # this line print the reverse of a string without using loop 

print(line == reverse)
```
