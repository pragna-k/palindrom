# palindrom
def palindrom(str):
 if str[0:len(str)]==str[::-1]:
    print("palindrom")
 else:
    print("not a plaindrom")
palindrom("madam")
