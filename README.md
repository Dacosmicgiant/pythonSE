# pythonSE
sem-3 python lab programs

 # Get the Type
    You can get the data type of a variable with the type() function.
    
    Example
    x = 5
    y = "John"
    print(type(x))
    print(type(y))

# A variable name must start with a letter or the underscore character
  A variable name cannot start with a number
  A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
  Variable names are case-sensitive (age, Age and AGE are three different variables)
  A variable name cannot be any of the Python keywords.
    Legal variable names:
    
    myvar = "John"
    my_var = "John"
    _my_var = "John"
    myVar = "John"
    MYVAR = "John"
    myvar2 = "John"

#Unpack a Collection
  If you have a collection of values in a list, tuple etc. Python allows you to extract the values into variables. This is called unpacking.
  
    Example
    Unpack a list:
    
    fruits = ["apple", "banana", "cherry"]
    x, y, z = fruits
    print(x)
    print(y)
    print(z)

#You can get the data type of any object by using the type() function:

    ExampleGet your own Python Server
    Print the data type of the variable x:
    
    x = 5
    print(type(x))

#Looping Through a String
  Since strings are arrays, we can loop through the characters in a string, with a for loop.

    Example
    Loop through the letters in the word "banana":
    
    for x in "banana":
      print(x)

#Check String
  To check if a certain phrase or character is present in a string, we can use the keyword in.

    Example
    Check if "free" is present in the following text:
    
    txt = "The best things in life are free!"
    print("free" in txt)

    Use it in an if statement:

    Example
    Print only if "free" is present:
    
    txt = "The best things in life are free!"
    if "free" in txt:
      print("Yes, 'free' is present.")

#Check if NOT
  To check if a certain phrase or character is NOT present in a string, we can use the keyword not in.
    
    Example
    Check if "expensive" is NOT present in the following text:
    
    txt = "The best things in life are free!"
    print("expensive" not in txt)
    Use it in an if statement:
    
    Example
    print only if "expensive" is NOT present:
    
    txt = "The best things in life are free!"
    if "expensive" not in txt:
      print("No, 'expensive' is NOT present.")
