# Exp. No: 2a  
## ITERATIVE STATEMENTS – factorial for a Given Number

###  Aim
To create a Python program for printing factorial for a Given Number.

---

###  Algorithm

Start

Read n

If n == 0 or n == 1, then

Return 1

Set fact = 1

For i from 2 to n, do:

fact = fact × i

Return fact

End


---

### 🧾 Program

```python
num=int(input())

fact=1

for i in range(1,num+1):
        fact=fact*i
print(f"Factorial of the given number {num} is {fact}")


```
### OUTPUT

![image](https://github.com/user-attachments/assets/07181a90-15ed-468d-bb81-e1da33b0220f)


### RESULT
Thus the  Python program for printing factorial for a given number is successfully done.

