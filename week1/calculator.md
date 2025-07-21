# Code

```
print("CLI Calculator Tool\n Avaliable Operations: +, -, *, /,%,^")
while True:
    print("***********************************")
    a=int(input("Enter the first number: "))
    op=input("Enter the operator: ")
    b=int(input("Enter the second number: "))

    match op:
        case '+': result= a + b
        case '-': result= a - b
        case '*': result= a * b
        case '/': result= a / b
        case '%': result= a % b
        case '^': result= a ** b
        case _:
                print("Invalid operator")
                continue
    print("Result is: ",result)
    ch=input("Do you want to perform another calculation (Y/n)?: ").lower()
    if ch=='n':
        print("Exiting calculator!")
        break
```
# Output
<img width="1144" height="768" alt="Screenshot 2025-07-21 104806" src="https://github.com/user-attachments/assets/1551e645-2eca-4804-a017-17ec2b4c3dbe" />
