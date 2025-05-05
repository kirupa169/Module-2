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
string="google" 
if string==string[::-1]: 
print ("The entered string is palindrome") else: 
print ("The entered string is not palindrome")
## Output
![image](https://github.com/user-attachments/assets/f7421d43-86eb-4d8c-85b6-f3741fea429e)

## Result
Thus, the program has been successfully executed.
