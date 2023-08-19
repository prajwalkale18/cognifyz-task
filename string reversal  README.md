# cognifyz-task1 level 1
# Function to reverse a string
def reverse(string):
	string = string[::-1]
	return string

s=input("enter any string:")

print("The original string is : ", end="")
print(s)

print("The reversed string is : ", end="")
print(reverse(s))
