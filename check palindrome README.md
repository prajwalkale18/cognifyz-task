# cognifyz-task5 level 1
def is_palindrome(s):
    s = s.lower()  # Convert to lower case
    reversed_s = s[::-1]  # Reverse the string
    return s == reversed_s  # Compare original and reversed strings

print(is_palindrome('racecar'))
print(is_palindrome('Prajwal'))
