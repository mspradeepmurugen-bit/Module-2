## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
temp=int(input())
rev=0
while temp>0:
    rev=(10*rev)+temp%10
    temp=temp//10
    if rev==num:
        print("The number is a palindrome")
    else:
        print("The number is not a Palindrome")
```
## Output

<img width="1038" height="272" alt="Screenshot 2025-12-27 210148" src="https://github.com/user-attachments/assets/f2125913-ab7f-4f14-a43e-7baf869cc538" />

## Result
thus the python program is executed sucessfully!
