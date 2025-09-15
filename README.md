''' code to prove that given string are tomriddles anagram each other '''
str1= input("Enter the text1: ")
str2= input("Enter the text1: ")
str1= str1.replace(' ','').lower()
str2= str2.replace(' ','').lower()
if sorted(str1) == sorted(str2):
  print("Yes!... anagram with each other")
else:
  print("No!.... not an anagram with each other")
  
