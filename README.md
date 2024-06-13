Write a program to convert strings to an integer and float and display its type. 

Sample Input: 

10 

10.9 

Sample Output: 

10,<class 'int'> 

10.9,<class 'float'> 

For example: 

Input Result 

10 

10.9 

10,<class 'int'> 

10.9,<class 'float'>

PROGRAM: 

n1=int(input()) 

n2=float(input()) 

print(round(n1,1),end = ',') 

print(type(n1)) 

print(round(n2,1),end = ',') 

print(type(n2))
