# -*- coding: utf-8 -*-
"""
Spyder Editor

This is a temporary script file.




#In [4]: scalar object can't be subdivision
print("hi")
print(type(2))  #class int
print(type(2.5)) #class float
print(type(True)) #class bool
print(type(None)) #class NoneType

#In [5]: Mathematical operation
Num1 = 5
Num2 = 2
print (Num1 + Num2) #additional 7
print (Num1 - Num2) #subtraction 3
print (Num1 * Num2) #multiplecation 10
print (Num1 ** Num2) #power 5^2=25
print (Num1 / Num2) #division 2.5
print (Num1 // Num2) #integer division 2 ignore after .
print (Num1 % Num2) #remaindar 1

#In [6]: operation on String (concatenation, *, length
Message = 'Hi'
Name = "Ahmed"
print(Message + ' ' + Name)  #output: Hi Ahmed
print(Message * 5)
print(len(Message))

#In [10]: STRING INDEX
MyString ='This is My World'
print(MyString[0])
print(MyString[1])
print(MyString[2])
print(MyString[3])
print(MyString[4])
print(MyString[5])
print(MyString[-1])

#In [11]: string slicing
print(MyString[0:2]) #output Th
print(MyString[2:]) #output from i to end ...is is My World
print(MyString[:]) #output return all
print(MyString[0:10:2]) #output step 2  .. Ti sM



#In [14]: in String
print('This' in MyString)  #output true


#In [17]: input() function return string
x =input ("Please Enter an Integer")
print(type(x)) #output class str so we need to convert it to integer

#In [21]: input() function convert return string to int
x =int(input ("Please Enter an Integer"))
print(type(x)) #output class int 




 #In [22]: if statement
userinput = int(input("Sir,please Enter an Number"))
if(userinput % 2 == 0):
     print("The Number Is Even")
else:
    print("The Number Is Odd")
    print("Thanks For Using AMG system")
print("I'M printed anyway Even or Odd :)")
 
 
 
 
 
#In [25]: nested if
if(userinput % 2 == 0):
    if(userinput % 3 == 0):
        print("The Number Divided BY 2 and 3")
    else:
        print("The Number Divide by 2 only")
elif userinput % 3 == 0:
    print("The Number is Divide by 3 only")
            
#In [30]: while statement   
N =0
while N <5:
    N = N + 1
    print(N)
    
#In [33]: for statement
for i in range(5):   # 0:4 for(i =0, i<5, i++)
    print(i)
    
#In [34]: for statement
for i in range(4,7):   # 4:7 for(i =4, i<7, i++)
    print(i)
    
#In [35]: break
for i in range(4):   # 0:3 for(i =0, i<4, i++)
    print(i)   #output 0 only because we exit for
    break
    print("I'M escaped")
print("outside for")

#In [36]: loop over string
str1 = "abcdef"
for index in range(len(str1)): #0:5
    print(index) #print index of string
for char in str1:
    print(char)  #print values of string
    
#In [39]: function with no aurgument no return
def printfun():
    print("Hi")
    
#In [39]: function with aurgument no return
def sum(n1, n2):
    print("the sum is:", n1 + n2)
print(sum(1, 6))    
    
    
#In [39]: function with aurgument return
def IsEven(num):
    return num % 2 == 0
print(IsEven(7))


#In [1]: tuple assign many different element to single variable
tup1 =(1, 's', 6)
print(type(tup1)) #class tuple
tup2 = 3,
print(type(tup2)) #class tuple
isnottuple = ('m')
print(type(isnottuple)) #class str
#In [2]: tuple is mutable means we can't change it after created
#tup1[0] = (3,) #TypeError: 'type' object does not support item assignment
tup1 = (1, 's', 9)  #but we can change value by this method
print(tup1) #output: (1, 's', 9)
#IN [1]: tuple[6]: access vlaue of tuple
print(tup1[0]) #output 1
print(tup1[0: 2]) #output (1, 's')
#In [15]: using tuple to swap
x = 1
y = 2
(x, y) = (y, x)
print(x, y)


#In [15]: using tuple to turn multivalue
def return_tuple(a, b):
    q= a + b
    y= a - b
    return(q, y) # return mutiple value
print(return_tuple(1, 4)) # output (5, -3)

#In []: create an empty list
a_list = [] #initializing empty list

#In []: in python you can create mutli datatype list not recommanded
a_list = [1, 'm', 2] #initializing empty list
b_list = [1, 2, 1] 
print(a_list) #output: [1, 'm', 2]
print(b_list) #output:[1, 2, 1]


#In []: list is mutable you can change value of list
c_list = [1, 'm', 3] 
c_list[2] = 5
print(c_list) #output [1, 'm', 5]

#In []: append() Function ADD an Item In End of List
d_list = [4, 3, 3] 
d_list.append(7)
print(d_list) #output [4, 3, 3, 7]

#In []: extend(list[]) Function ADD Many The Item In End of List
e_list = [4, 3, 3] 
e_list.extend([6, 8, 9])
print(e_list) #output [4, 3, 3, 6, 8, 9]

#In []: del(list[index]) Function Delete an Item  of List
f_list = [4, 3, 3] 
del(f_list[0])
print(f_list) #output [3, 3]
#In []: remove(value) Function Delete a value  of List If there are many remove first
r_list = [4, 3, 3] 
r_list.remove(3)
#r_list.remove(6) #output ValueError: list.remove(x): x not in list
print(r_list) #output [4, 3]



#In []: pop() Function remove and return  a last  value  of List 
p_list = [4, 3, 3, 7, 2] 
p_list.pop()
print(p_list) #output [4, 3, 3, 7]



#In []: pop(index) Function remove and return  aspecific index  of List 
s_list = [4, 5, 3, 7, 9] 
s_list.pop(0)
print(s_list) #output [5, 3, 7, 9]
#In [] : in python we can convert string to list, and list to string
str3 ="hello world"
con = list[str3]
print(con)



#In []: split('') Function split a string 
print(str3.split(' ')) #output:['hello', 'world']
print(' '.join(str3))  #output: h e l l o   w o r l d
#''.join(list) convert list to string 
#In []: sorted list and return copy of it
sort_list = [2, 1, 5, 3, -1]
s =sorted(sort_list)
print(s) #output: sort_list
#l = s.reverse()
#print(l)


#In []: remove deplication from two list
def remove_dub(l1, l2):
    for e in l1:
        if e in l2:
            l1.remove(e)
            return l1
l1 = [1, 2, 3, 4, 5]
l2 = [2, 3]
print(remove_dub(l1, l2)) #output: [1, 3, 4, 5] not remove 3

#In []: The correct way to remove deplication the take copy of list and implement for in it
def remove_dubs(ln1, ln2):
    l1_copy = ln1[:]
    for p in l1_copy:
        if p in ln2:
            ln1.remove(p)
    return ln1
ln1 = [1, 9, 8, 4, 5]
ln2 = [9, 8]
print(remove_dubs(ln1, ln2))
"""

#In []: Crearing dictionary dic_name{'key':'value'}
grades = {'Ahmed':'c', 'Menna':'A', 'Yassar': 'B'}
print(grades)
print(grades['Yassar']) #output: B
#add to dictionary
grades['aya'] ='B'
print(grades) #OUTPUT {'Ahmed': 'c', 'Menna': 'A', 'Yassar': 'B', 'aya': 'B'}
#In []: the in and not in operator impement on key
print('Ahmed' in grades) #output: True ...python is case senstive A != a
#In []: delete from dictionary
del[grades['Ahmed']]
print(grades)  #output: {'Menna': 'A', 'Yassar': 'B', 'aya': 'B'}
print(grades.keys())
#In []: operation on dictionary
for key in grades:
    print(key+ ':' + str(grades[key])) #output: Menna:A
                                       #output: Yassar:B
                                       #output: aya:B
print(grades.get('Menna'))   #to get value of specific key
print(grades['Menna'])       #to get value of specific key


#In []:update dictionary
d1= {1:'Hammad', 2:'Fatma'}
d2= {1:'Mostafa', 3:'Mhamed'}
d3={4:'Asharket', 5:'Nor'}
d1.update(d2)
print(d1)  #output{1: 'Mostafa', 2: 'Fatma', 3: 'Mhamed'} note that we can't add same key to two values
d2.update(d3)
print(d2) #output: {1: 'Mostafa', 3: 'Mhamed', 4: 'Asharket', 5: 'Nor'}