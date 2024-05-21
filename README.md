Replace a substring in a string
In this page we will learn how to replace a substring in a string using python. we will be asking the user to input a base string, than we will ask for a substring which is to replaced, and finally we will ask for the string which is to be placed on the place of substring and by using replaceAll() we will replace old string with new one.

Python program to replace a substring in a string
In python we have a in-built function “replace” which helps to complete our task. Replace function takes three arguments ( two mandatory arguments and one is optional) 

string.replace(str1,str2,count)

str1= substring of a string which has to be replaced
str2= substring of a string with which str1 has to be replaced
count= number of times we need to replace , by default this value will be 1
Example:
Input:

PrepInsta
Insta
Ster
Output:

PrepSter
Let’s replace a substring in a string using python

Algorithm:
Accept the inputs.
Use replace function
pass the arguments.
Find the substring in the main string.
Replace it with the new string.
Print result.
Python Code:
string=input("Enter String :\n")
str1=input("Enter substring which has to be replaced :\n")
str2=input("Enter substring with which str1 has to be replaced :\n")
string=string.replace(str1,str2)
print("String after replacement")
print(string)
Input:
Enter String :
PrepInsta
Enter substring which has to be replaced :
Insta
Enter substring with which str1 has to be replaced :
Ster
Output:
String after replacement
PrepSter
