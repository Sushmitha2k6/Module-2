# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
def decimal_to_binary(decimal_number):
    binary_number = bin(decimal_number)[2:]
    return binary_number

# Input from the user
decimal_number = int(input("Enter a decimal number: "))

# Convert and display the binary equivalent
binary_number = decimal_to_binary(decimal_number)
print(f"0b{binary_number}")

```


## Output

![image](https://github.com/user-attachments/assets/3b97eb3e-9266-4791-86dd-7c0dcd4fa9ed)


## Result

The expected output is achieved.
