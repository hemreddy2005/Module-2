# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program

```python
def find_modulo(a, b):
    return a % b

a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))
if b != 0:
    result = find_modulo(a, b)
    print(f"The result of {a} % {b} is: {result}")
else:
    print("Error: Division by zero is not allowed.")
```

## Output

![image](https://github.com/user-attachments/assets/6122ff0c-1e30-4749-81ba-fdb47845ce2f)

## Result
Hence the program is executed successfully.
