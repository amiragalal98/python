# -*- coding: utf-8 -*-
"""
Created on Sat Nov 16 15:02:58 2024

@author: Autocad Store
"""

# =============================================================================
# =============================================================================
# num1 = input("enter num1:") 
# num2 = input("enter num2:") 
# sum =int(num1) +int(num2)
# print('the sum {0} and {1} is {2}'.format(num1, num2, sum))
# =============================================================================
#even no check
# =============================================================================
# a=int(input("Enter a no:"))
# if(a % 2 == 0):
#     print('{0} is even'.format(a))
# else:
#     print('{0} is odd'.format(a))
#     
# =============================================================================
    
    
# =============================================================================
# =============================================================================
# for x in 'python':
#     print(x)
# =============================================================================
# =============================================================================
# for y in ['python', 'php', 'java', 'c++']:
#     print(y)

# =============================================================================
# =============================================================================
# for d in {'python': '30%', 'php': '50%', 'java': '80%', 'c++': '100%'}:
#     print(d) #output:python
#              #output:php
#              #output:java
#              #output:c++
# =============================================================================
# =============================================================================
#              
# for a in ('allah akbar', 'allah allah', 'allah elhaq', 'allah azm'):
#     print(a) #output:allah akbar
#              #output:allah allah
#              #output:allah elhaq
#              #output:allah azam
# =============================================================================
# =============================================================================
# f_list = ["adam", "youssef","mohamed", "ibrhim"]
# for i in range(4):
#     print(i)
#     print(f_list[i])
# =============================================================================
# =============================================================================
 
# =============================================================================
# lst = ["Hello", "World"] 
# print(" ".join(lst)) #Hello World  
# 
# =============================================================================



# =============================================================================
#  ❑ Create a List
#  ❑ Access List Elements
#  ❑ Slicing of a List
#  ❑ Add Elements to a List
#  ❑ Remove an Item From a List
#  ❑ Iterating through a List
#  ❑ List Comprehension
#  ❑ List Methods 
# =============================================================================
#❑ Create a List
ages = [19, 26, 23]
 
#❑ Access List Elements

# =============================================================================
# print(ages[0])  # Output: 19
# print(ages[1])  # Output: 26
# print(ages[2])  # Output: 23
# #print(ages[3]) # Output: Index Error 
# print(ages[-1]) # Output: 23
# 
# =============================================================================
# =============================================================================
# numbers = [21, 34, 54, 12]
# even_numbers = [4, 6, 8]
# numbers.append(32)
# numbers[2] = 'C' 
# print(numbers)
# print(numbers[:])
# =============================================================================
# =============================================================================
# 
# =============================================================================
# =============================================================================
# lst = [1, 2, 3, 'ahmed', 'ali', 2.34]
# del lst[1]   #output[1, 3, ‘ahmed’, ‘ali’, 2.34]
# del lst[-1]  #output[1, 2, 3, ‘ahmed’, ‘ali’]
# del lst[0:2] #output[‘ahmed’, ‘ali’, 2.34]
# print(lst)
# =============================================================================
# =============================================================================
# lst = [1,2,3,4] 
# 
# lst.append(5) #Reverses the item of the list
# print(lst)             
# =============================================================================
# =============================================================================
# =============================================================================
# lst.insert(2, 10) #Inserts an item at the specified index [1, 2, 10, 3, 4, 5]
# print(lst)
# lst.remove(2) #Removes item present at the given index [1, 10, 3, 4, 5]
# print(lst)
# lst.pop(1) #Returns and removes item present at the given index [1, 10, 3, 4, 5]
# print(lst)
# lst.clear() #Removes all items from the list  output:[]
# print(lst)
# lst = [1,2,3,4] 
# print(lst.index(3)) #Returns the index of the first matched item output:2
# print(lst.count(4)) #Returns the count of the specified item in the list output: count =1
# lst.sort() #Sort the list in ascending/descending order [1, 2, 3, 4]
# print(lst)
# lst2= lst.copy() #Returns the shallow copy of the list [1, 2, 3, 4]
# print(lst2)
# lst.reverse() #Reverses the item of the listlst = [1,2,3,4] 
# =============================================================================
# =============================================================================
# print(lst)  
# =============================================================================
# =============================================================================
# ❑ Create a tuple
# =============================================================================
# my_tuple = ("mouse", [8, 4, 6], (1, 2, 3))
# print(my_tuple[:])
# print(my_tuple[0])
# print(my_tuple[1])
# print(my_tuple[2])
# print(my_tuple[2][2])
# =============================================================================
 

# =============================================================================
# 
#  ❑ Create a Dictionary
#  ❑ Access Dictionary Items
#  ❑ Change Dictionary Items
#  ❑ Add Items to a Dictionary
#  ❑ Remove Dictionary Items
#  ❑ Iterating through a Dictionary
#  ❑ Dictionary Methods
#  
# =============================================================================
#❑ Create a Dictionary
# Dictionaries in Python are mutable, meaning we can modify the value of an element by referencing its key.
country_capitals = {"Egypt": "Cairo", "Qatar": "Qaatar", "England": "London" }
# =============================================================================
# country_capitals["Egypt"]     #Output: Cairo 
# country_capitals["England"]   # Output: London
# country_capitals["Qatar"] = "Doha"  # change the value of ”Qatar" key to "Doha"
# country_capitals["Germany"] = "Berlin"  # add to dictionary or use update method()
#print(country_capitals.keys())
#del country_capitals["Germany"] 
#print(country_capitals)       
#country_capitals.clear()               # or use pop method()
#print(country_capitals)
 
 
 
 
 