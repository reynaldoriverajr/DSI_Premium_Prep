
# JUL.-AUG. 2021 DSI PREMIUM PREPARATION COURSE STUDENT NOTES.

# Day_2
   #Notes from second day of class. 
    #Class Day Two
    #Day_2

# On Quotes & Tics.
   #Quote marks with either ('') or ("") are both considered strings. However, single tic quotes(') may intefer with apostrophes.
   
    EX:
    ('there's') would interfere with the string.
    
    "Hello World!"
    
    print ("Hello World!")

# On Reading Numbers.
   #To have Python read numbers write them like this (73).
   
    (73) #Right
    
    print (73) #Right
    
    73 #Wrong
    
    print 73 #Wrong

# On Defining Float & Int.
   #Integer data types must be whole numbers. A floating point (float) is computer science terminology for containing decimal points.
    EX:
   
    print(73+7)
    
    print(73-7)
    
    print(73*7)
    
    print(73/7)
    
    print(73//7)
    
    print(73%7)
    
 # On Floats and Int.

   #Mixing floats and ints in 1 operation always result into float.

    print(73+7) #80
    
    print(73-7) #66
    
    print(73*7) #511
    
    print(73/7) #10.428571428571429
    
    print(73//7) #10
    
    print(73%7) #3
    
 #int and float encode different in memory.

# On Equality Operators.
   #(==) is the equality operator. It shows us if something is indeed equal to something else.

    print (7==8) #False

    print (7==7.0) #True

# On Boolean's or bool.
   #bool also known as a boolean has two possible values. True & False.

    True
    
    False

# On Finding the Type of Value.
   #If you ever want to get a "type" of something you can use "type".
  
    EX:

    print (type(4)) #class 'int'

    print(type(3.2)) #class 'float'

    print (type(4%7)) #class 'int'

    print (type (7==9.0)) #class 'bool'

    1.0 == 1 #True
    1.0 == 1 #True

    type(1.0) == type(1) #False
    type(5) == type(1) #True
    
 # On How to Invoke Code.
 
 #print (   ) = is an invocation code. It displays something on the console/terminal. It's a way of seeing the code in the console.
    
    #A function call example is: print(  ).
    #In order to invoke something you must wrap it in parenthesis.
    
    EX:
    
    print( type() ) #invokes a type to display.

# Breakout.
#Solve Problem.
    
    print(type(74)) #<class 'int'>
      
      #END

# On Parenthesis and (PEMDAS) Parenthesis, Exponent, Multiplication, Division, Addition, Subtraction.
#The order the math executes upon depends on parenthesis and PEMDAS.

    print ( 7 + 3 * 10) #37
    
    print ( 7 + (3 * 10)) #37
    
    print ((7 + 3) * 10) #100

# Breakout
#Add 5 and 7.2, multiply the result by 6, divide that result by 3, then square the result.

    print ((((5+7.2) * 6) / 3) ** 2) #595.3599999999998 = Right
    
    print (5+7.2 * 6 / 3 ** 2) #9.8 = Wrong

      #END

# On Casting (a.k.a) Converting.

#Casting: int(x), float(x) also known as "Converting".

    print ( float(4) ) #4.0
    
    print ( int(4.0) ) #4
    
    print ( int(4.334570)) #4 . . . Even though a decimal is normally a float we converted or
    
    #Cast it by putting "int" in front of it.

# On Input Types (float, Int).
#A "float" has a decimal. A "int" does not, because it is a whole number.

    print ( 5 + 3) #int or 8
    
    print (5.0 + 3) #float or 8.0
    
    print (5.0 +3.0) #float or 8.0

# On Floor Division.
#Floor division always gives you a whole number back.

    print (10 // 3) #int or 3
    
    print (10.0 // 3) #float or 3.0
    
    print (10 // 3.0) #float or 3.0
    
    print (10.0 // 3.0) #float or 3.0
    
#That whole number can be a float or an int.

# On Modulo, mod, or "Remainder" Operator.
#A mod is the remainder of a divided variable.
   
    EX:
    
    print (10%3) #1.
    
#Three goes into 10 three times 10/3 = 9 with a 'remainder' of 1. Answer is 1.


# On Assignment Operator. 
#An assignment operator assigns a value into an identifier.
    
    EX:
    
    a = 5
   
   #A variable is some piece of data you give a name to.
   
    #I am assigning the value (5) to the identifier/variable (a).
    
    EX:
    
    a = 5 * 3
    b = a / 2
    c = a * b

    print (c) #112.5

    EX:
    
    a = 5
    b = a + 3 #8
    a = 0

    print (b) #8 with explanation in #NOTE.
   
   #NOTE: Python evaluates top to bottom, left to right.
    
# On What is Snake Casing.

#Snake Casing is the underscore used to name variables. 

    EX:
    
    (this_is_an_example).
    
    (this_is_another_example).

# "It's Like Castling in Chess" Examples Below.
#I don't remember the actual name for this process, but . .

    #counter = 0
    #print (counter) #0

    #counter = counter + 1
    #print (counter) #1
    
   #this "+=" replaces the (counter = counter + 1) variable.
    
    #counter +=1 
    #print (counter) #1

    #num = 10
    #print(num) #10

    #num += 15
    #print(num) #25

    #num += (10 - num)

    #print (num)


# Breakout.

   1. print the result of multiplying by 7 the addition of 6 and 3.
   2. print the product of 7 times 6, squared, with 23 subtracted from the result.
   3. print the division of the result of 4 minus 2 times 2 into twenty.

    #print ((6 + 3) * 7) #63

    #print (((7 * 6)**2) - 23) #1741

    #print ((4-2) * (20/2)) #20.0
    
      #END

# Hashtags:
    # Galvanize
    # dsi_premprep_day2
    # file1
    
#    
# DAY_3

# Breakout (3 minutes).
If 3 letter carriers must deliver the same exact number of letters, and there are 299 letters, how many letters will not be delivered? Write a Python expression that answers this question.
If you have 5 bank tellers and 28 people waiting to be served, what is the least number of people who will not be served if it takes exactly 4 minutes to serve each person and the bank MUST close in 20 minutes? Write a Python expression that answers this question.

      #letter_carriers = 3

      #letters = 299

      #print (letters%letter_carriers)

      #END

What are the two types of comments?

      #1. Single Line
      #2. Block Line

What does the type() function do?

      #Defines type of value.

#What are some differences between the int and float types?

      #int = always a whole number.
      #float = always a decimal number.

# What is a Sanity Check?
Sanity Check - Helps the coder know that the program is working as intended.

      print ("Hello, World!")

      #Let's you know that coding is working and you can continue to troubleshoot.
      #END

# Python Variables and Logic.
    #declaring variables; variable naming syntax
    #logic operators
    #control flow
    #homework

# Covering.
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

# Below Was in Regard to Abstraction Explanation. idk. I Got Confused.

      n = 4
      n_factorial = 1
      for i in range(2, n):

      n_factorial *= i

      #END

      print(1/23) #0.043478260869565216

      print(1/233) #0.004291845493562232

# Float Underflow.
#float underflow example because answer becomes (0.0)
    
    print( 1/10**1000) #(0,0)

# Truthyness and Falsyness.

    print(bool(3)) #True
    print(bool(1)) #True

    print(bool(0)) #False

    print(bool(0.0)) #False

    #0 is the only falsy. Everything else is truthy.


# Strings.

    print(bool("") #False

    print(bool("anything")) #True

    print(bool("false")) #True

    print("bool " + "False") #bool False


# Concatenation.
   #Is When You Add Two Strings Together.

    EX:

    print ("Hello " + "World") #Hello World


# None.

   #None is the only value that has .. no .. value.
        
      print(None) #None

      print(print("hello")) #output is ("hello" + "None")

# I Should Revise Scratch Notes Below.

      identifier =

      assignment operator

      value =

      (10) = a #SyntaxError: cannot assign to literal

      print(variable)

# Boolean Operators.

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
    
  # HASHTAG
     #Day_3 #DSI_Premium_Prep

    
