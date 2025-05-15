''' program to determine the character enterd by a user ,
whether it is an alphabet, digit or space by using seperate if condition and predefined string functions'''
char= input("press any key:")
if char.isalpha():
    print("The user has enterd charater")
if char.isdigit():
    print("The user has enterd digital")
if char.isspace():
    print("The user has enterd spaace")
