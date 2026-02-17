# Simple-Calculator-
def add(x, y):
    print(x + y)
def subtract(x, y):
    print(x - y)
def multiply(x, y):
    print(x * y)
def divide(x, y):
    print(x / y)
print("Enter two numbers")
n1 = int(input())
n2 = int(input())
print("Enter the operation +, -, *, /")
op = input()
if op == '+':
    add(n1, n2)
elif op == '-':
    subtract(n1, n2)
elif op == '*':
    multiply(n1, n2)
elif op == '/':
    divide(n1, n2)
else:
    print("Invalid entry")
    
OUTPUT:
Enter two numbers
10
5
Enter the operation +, -, *, /
+
15
