print("Enter the num1")
num1 = int(input())
print("Enter the num2")
num2 = int(input())
print("Enter operator:  +,-,*,/")
op = input()
if num1==43 and num2==3 and op=="*":
    print("555")
elif num1==56 and num2==9 and op=="+":
    print("77")
elif num1==56 and num2==6 and op=="/":
    print("4")
elif op=="+":
    print("The sum is", num1 + num2)
elif op=="-":
    print("The difference is", num1 - num2)    
elif op=="*":
    print("The multiplication is", num1 * num2)
elif op=="/":
    print("The division is", num1 / num2)
else:
    print("Invalid input")
