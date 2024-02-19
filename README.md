print("I am a CSE student")
#output:I am a CSE student


print("I am a CSE student)
#output:Cell In[3], line 1
   # print("I am a CSE student)
          ^
#SyntaxError: unterminated string literal (detected at line 1)


print("I am a CSE student"
#output:Cell In[4], line 1
   # print("I am a CSE student"
         ^
#SyntaxError: '(' was never closed

# Plus sign before a number
x = +2
print(x)  # Output: 2

2++2
y = 2++2
print(y)  # Output: 4

number = 09

SyntaxError: leading zeros in decimal integer literals are not permitted; use an 0o prefix for octal integers
number = 011
print(number)  # Output: 9

x = 5 10
SyntaxError: invalid syntax


