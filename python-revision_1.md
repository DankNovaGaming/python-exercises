# Python Revision 1
## Mathematical operations  
/ + - % // %
1. calculate the hypotenuse of a right angle triangle with sides 6 and 7 cm
1. what does 
```python
print(17//5)
```
get you and why?  

3. Print all numbers below 75 dividable by 7
1. Now do it without using modular division

## Input /output
5. Ask user for a number and a name  
    Now print the name with as many spaces between the letters  
    Also print the name as may times as the number
5. Ask user for a name and print name one letter at a time (separate lines)  
	Now print the letters diagonally across the page one letter at a time (separate lines)
6. Figure out how to print this pattern below with and without using a loop (its just a formatting trick)  
```
     *
    ***
   *****
  *******
 *********
```
## Mathematical operations  
a=6
b=7
c=(a*a+b*b)**(1/2)
print(c)
print("_____")
print(17//5)
print("_____")
for i in range(0,75):
	if i%7==0:
		print(i)
print("_____")
seven=0
for i in range(0,10):
	seven=seven+7
	print(seven)




## INPUT/OUTPUT
Name=input("Enter a name")
Number=int(input("Enter a number"))
Namelist=[]
NumberCounter=0
SpaceCounter=0
print("There is",(len(Name)),"letters")
for i in range(0,(len(Name))):
	Namelist.append(Name[i])
	for i in range(0,(len(Name))):
		Namelist.append("")
print("Your number is",(Number))
for i in range(0,Number):
	NumberCounter=NumberCounter+1
	print((NumberCounter),")",(Namelist))
Name2=input("Enter a name")
for i in range(0,(len(Name2))):
	print(Name2[i])
print("")
for i in range(len(Name2)):
	print("\t" * i + (Name2[i]))
print("")
print("     *")
print("    ***")
print("   *****")
print("  *******")
print(" *********")
