# Simple-calculator-
A simple python programming calculator, signs used (* + - and /)

... python .
print("simple calculator")
operator=input("choose operator -,+,/,*: ")
num1=float(input("enter first number: "))
num2=float(input("enter second number: "))



if operator=="+":
    result = num1 + num2
    print(result)
elif operator=="-":
    result = num1 - num2
    print(result)
elif operator=="*":
    result = num1 * num2
    print(result)
elif operator == "/":
    if num2 == 0:
        print("syntax error ")
    else:
         result = ("num1/num2")
         print (result )
else :
    print("invalid operator ")


    
    
    

