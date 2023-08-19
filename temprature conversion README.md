# cognifyz-task2 level 1
#temrature conversion
temprature = input("Enter temprature value and Unit (eg: 23F,65C) : ")
degree = int(temprature[:-1])
a = temprature[-1]

if a.upper() == "C":
  result = int(round((9 * degree) / 5 + 32))
  b= "Fahrenheit"
elif a.upper() == "F":
  result = int(round((degree - 32) * 5 / 9))
  b= "Celsius"
else:
  quit()
print("The temperature in", b, "is", result, "degrees.")

