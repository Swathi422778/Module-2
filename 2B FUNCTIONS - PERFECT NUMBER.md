# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number.

---

### ALGORITHM

Start

Read the number a

Initialize sum = 0

For each integer i from 1 to a - 1, do:

If a % i == 0, then:

Add i to sum

If sum == a, then:

Print "The number is a Perfect number!"

Else, print "The number is not a Perfect number!"

End

---

### PROGRAM
```
a=int(input())
sum=0
for i in range(1,a):
    if(a%i==0):
        sum=sum+i
        
if(sum==a):
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")

```
### OUTPUT
![image](https://github.com/user-attachments/assets/ebb8f9c3-cad7-4ade-96c4-b64bc9968748)


### RESULT
Thus the Python program for checking the number is a Perfect number or not is successfully verified.
