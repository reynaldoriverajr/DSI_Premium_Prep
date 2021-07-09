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

    
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete

pagebreak

""" un/comment to de/activate ###########################

'''
BREAKOUT (2 minutes)
What is the result of calculating 1/10**1000000? Explain this result
What is the result of bool(‘’)?
What is the result of bool(‘’ + ‘Hi’)?
'''

####################################################### """
""" un/comment to de/activate ###########################

# overview
    # data types
        # int
        # float
            # underflow
        # bool
            # truthyness and falsyness
        # str
            # concatenation
        # None

    # abstractions
        # variables
        # functions
    # control flow
    # iteration


# float underflow
# print( 1 / 23 )     # 0.043478260869565216
# print( 1 / 233 )    #
# print( 1 / 2342 )   #
# print( 1 / 23235 )  #
# print( 1/10**1000 ) #

# truthyness and falsyness
# print( bool(3) )   # True
# print( bool(0) )   # False
# print( bool(-3) )  # True

# print( bool(3.3) )   # True
# print( bool(0) )   # False
# print( bool(-3) )  # True
# print( bool(0.0000000000000001) )   # True

# print( bool("") )
# print( bool("anything") )
# print( bool("False") )


# strings # concatenation
# 3 + 4
# a = "hello" # original value
# print( a )
# b = a + " " + "world"
# print( b )
# print( a ) # "hello", "hello world"

# counter = 0
# print(counter)
# counter += 1
# counter = counter + 1
# print(counter)

# a = ""
# a += "hello"
# a += " there"
# a += " world"
# a = a + " world"
# print(a)

# None
# print(None)
# print( print("hello") )
# print(None)
# print(None)
# print(True)
# print(False)
# print(4)
# print("this is a string")
# a = 0
# print(undefined) # NameError: name 'undefined' is not defined
# print(Nul)  # NameError: name 'Nul' is not defined
# print(Null) # NameError: name 'Null' is not defined

####################################################### """
""" un/comment to de/activate ###########################

# n = 4
# n_factorial = 1
# for i in range(2, n+1):
#     n_factorial *= i

# print( n_factorial )

# m = 5
# m_factorial = 1
# for i in range(2, m+1):
#     m_factorial *= i

# print( m_factorial )

# o = 3
# o_factorial = 1
# for i in range(2, o+1):
#     o_factorial *= i

# print( o_factorial )

# p = 8
# p_factorial = 1
# for i in range(2, p+1):
#     p_factorial *= i

# print( p_factorial )

def factorial(n):
    prod = 1
    for i in range(2, n+1):
        prod *= i

    return prod


n = 4
print(factorial(n))
print(factorial(4))

m = 5
print(factorial(m))
print(factorial(5))

o = 3
print(factorial(o))
print(factorial(3))

p = 8
print(factorial(p))
print(factorial(8))

####################################################### """
""" un/comment to de/activate ###########################

# variable
# identifier, assignment operator, value
a = 10
# 10 = a # SyntaxError: cannot assign to literal
print(a * 3)

####################################################### """
""" un/comment to de/activate ###########################


# generally do this
x = 3
y = 5

# over this
x, y = 3, 5
# print(y, x)

x, y, z = 0, 0, 0
print(x, y, z)

x = y = z = 0
print(x, y, z)

x = 0
y = 0
z = 0
print(x, y, z)

####################################################### """
""" un/comment to de/activate ###########################

# list_of_clients_who_defferred_service
# clients_defferred_lst

####################################################### """
""" un/comment to de/activate ###########################

# elsey = 5
# print(elsey)

####################################################### """
""" un/comment to de/activate ###########################

a = 9
b = 2
print(a == b) # False
print(a == 9) # True

print(a != b) # True
print(a != 9) # False

print( "hello" == "world" ) # False
print( "hello" == "hello" ) # True
print( "hello" != "world" ) # True
print( "hello" != "hello" ) # False

print(3 > 4)  # False
print(4 > 4)  # False  <----
print(5 > 4)  # True       |
#                          |
print(3 >= 4) # False      |
print(4 >= 4) # True  # <---
print(5 >= 4) # True

print(3 < 4)  # True
print(4 < 4)  # False  <----
print(5 < 4)  # False      |
#                          |
print(3 <= 4) # True       |
print(4 <= 4) # True  # <---
print(5 <= 4) # False

# print("hello" < "goodby")
# print("hello" > "goodby")

####################################################### """
""" un/comment to de/activate ###########################

# logical
# print( not True  ) # False
# print( not False ) # True

# print( not 0 ) #
# print( not 4 ) # True

# and
print(True  and True)  # True
print(False and True)  # False
print(True  and False) # False
print(False and False) # False

# or
print(True  or True)  # True
print(False or True)  # True
print(True  or False) # True
print(False or False) # False

# xor
print(True  != True)  # False
print(False != True)  # True
print(True  != False) # True
print(False != False) # False

####################################################### """
""" un/comment to de/activate ###########################

'''
If 3 letter carriers must deliver the same exact number of letters, and there are 299 letters, how many letters will not be delivered? Write a Python expression that answers this question.
'''

'''
If you have 5 bank tellers and 28 people waiting to be served, what is the least number of people who will not be served if it takes exactly 4 minutes to serve each person and the bank MUST close in 20 minutes? Write a Python expression that answers this question.
'''

# 28 people waiting to be served
# the bank MUST close in 20 minutes
# each transaction takes exactly 4 minutes
# 5 bank tellers
# print( 28 - (20//4 * 5) ) # --> 3


####################################################### """
# """ un/comment to de/activate ###########################

# overview
# data types
# abstractions
# control flow (conditional logic)
# iteration

####################################################### """
# """ un/comment to de/activate ###########################



####################################################### """

