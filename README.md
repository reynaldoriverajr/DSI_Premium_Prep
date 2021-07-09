# DSI_Premium_Prep
July 2021
Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@reynaldoriverajr 
reynaldoriverajr
/
DSI_Premium_Prep
1
00
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
DSI_Premium_Prep/Day_3
@reynaldoriverajr
reynaldoriverajr Create Day_3
Latest commit ef24557 now
 History
 1 contributor
160 lines (92 sloc)  3.05 KB
  
'''
BREAKOUT (3 minutes)
If 3 letter carriers must deliver the same exact number of letters, and there are 299 letters, how many letters will not be delivered? Write a Python expression that answers this question.
If you have 5 bank tellers and 28 people waiting to be served, what is the least number of people who will not be served if it takes exactly 4 minutes to serve each person and the bank MUST close in 20 minutes? Write a Python expression that answers this question.
'''
#END

letter_carriers = 3

letters = 299

print (letters%letter_carriers)

#END

REVIEW BREAKOUT
What are the two types of comments?

#True #False (WRONG) i guess . .

SINGLE LINE AND BLOCK #Right
What does the type() function do?

#Defines type of value.

#What are some differences between the int and float types?

#int = always a whole number.
#float = always a decimal number.

#NOTE
Sanity Check:

print ("Hello, World!")

#Let's you know that coding is working and you can continue to troubleshoot.
#END

# Python Variables and Logic
    #declaring variables; variable naming syntax
    #logic operators
    #control flow
    #homework

# Covering
    #1. data types - some vocabulary will need to be memorized.
        #a. int
        #b. float
            #i. underflow
        #c. bool
        #d. str
        #e. None

    #2. abstractions - make things easier. when you take a complicated idea and you wrap it up in a simple idea.
        #a. functions.
        #b. variables.
    #3. control flow - lets us write dynamic code.
    #4. iteration - lets us repeat processes a number of times.

#below was in regard to abstraction explanation. idk.

n = 4
n_factorial = 1
for i in range(2, n):

n_factorial *= i

#END

print(1/23) #0.043478260869565216

print(1/233) #0.004291845493562232

# float underflow

    print( 1/10**1000) #float underflow example because answer becomes (0.0)

# truthyness and falsyness

    print(bool(3)) #True
    print(bool(1)) #True

    print(bool(0)) #False

    print(bool(0.0)) #False

    #0 is the only falsy. Everything else is true.


# strings

    print(bool("") #False

    print(bool("anything")) #True

    print(bool("false")) #True

    print("bool " + "False")


# # concatenation - is when you add two strings together

    EX:

    print ("Hello " + "World") #Hello World


#None

print(None) #None
#None is the only value that has .. no .. value.

print(print("hello")) #output is ("hello" + "None")


identifier =

assignment operator

value =

(10) = a #SyntaxError: cannot assign to literal

print(variable)

# Boolean Operators

    Operator = (>) Greater Than

    Operator = (>=) Greather Than or Equal

    Operator = (<) Less Than

    Operator = (<=) Less Than or Equal

    Operator = (==) Equals or Is Equivalent

    Operator = (!=) Does not Equal


print( "hello" == "world" ) #False

print( "hello" == "hello") #True

print ("hello" != "world") True

# Logical Operators
 #Operator Precedence: not, and, or

    print(not True) #False

    print(not False) #True

    print(True and True) #True

    print(True and False) #False

    print(True or False) #True
