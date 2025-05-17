# Simple Calculator

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

print("Choose operation:")
print("1. Add")
print("2. Subtract")

choice = input("Enter choice (1/2): ")
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

if choice == '1':
    print("Result:", add(a, b))
elif choice == '2':
    print("Result:", subtract(a, b))
else:
    print("Invalid input")
