# Project-1


number_1 = input("Enter the first number : ")
number_2 = input("Enter the second number : " )
operator = input("Enter the operator : (+ , - , * , /)")

if operator == "+":
  print(int(number_1) + int(number_2))
elif operator == "-":
  print(int(number_1) - int(number_2))
elif operator == "*":
  print(int(number_1) * int(number_2)) 
elif operator == "/":
  print(int(number_1) / int(number_2))
else:
  print("Invalid operator")
