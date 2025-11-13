# CALCULATOR-CLI-APP
#This is a calculator made for the user to simplify the calculations 
#CODE FOR CALCULATOR 
print('''.....CALCULATOR.....''')
print('''The operation performed is
+,-,*,/,//,**,%''')

While True:
  a=int(input('Enter -1 to stop the   calculations or press any digit     from 0-9 to continue'))
  if a==-1:
    print('Program Terminated')
    break 
  else :
    #to take input from user ......
    op=input('What operation you        want to perform…?')
    #take two inputs from user
    num1=float(input('Enter The         first number :'))
    num2=float(input('Enter the         second number'))
    if op=='+':
      print(num1+num2)
    elif op=='-':
      print(num1-num2)
    elif op=='/':
      print(num1/num2)
    elif op=='*':
      print(num1*num2)
    elif op=='%':
      print(num1%num2)
    elif op=='**':
      print(num1**num2)
    elif op=='//':
      print(num1//num2)
    else:
    print('Invalid Syntax') 
