# calculator
def calculator():
    
    print("welcome to the simple calculator")
    n1 = float(input("enter the first number:"))
    n2 = float(input("enter the second number:"))
    print("SELECT OPERATION")
    print("1.ADDITION:")
    print("2.SUBTRACTION:")
    print("3.MULTIPLICATION:")
    print("4.DIVISION:")
   
    operation = input("enter operation number(1/2/3/4):")
    if operation == '1':
        result = n1 + n2
        print("the result of addition is:",result)
    elif operation == '2':
        result = n1 - n2
        print("the result of subtraction is:",result)
    elif operation == '3':
        result = n1 * n2
        print("the result of multiplication is:",result)
    elif operation == '4':
        if n2 == 0:
            print("error! division by zero is not allowed:")
        else:
            result = n1 / n2
            print("the result of division is:",result)
    else:
        print("invalid operation")
calculator()
