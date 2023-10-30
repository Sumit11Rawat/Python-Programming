             Python - Modify Strings

1:Upper Case  -->The upper() method returns the string in upper case

          for example  a = "Hello, World!"
                       print(a.upper())
            output      HELLO, WORLD!

2:Lower Case  -->The lower() method returns the string in lower case:

          for example  a = "Hello, World!"
                       print(a.lower())
              output    hello, world!

3:Remove Whitespace  --> Whitespace is the space before and/or after the actual text, and very often you want to remove this space.
                     -->The strip() method removes any whitespace from the beginning or the end:

          for example  a = " Hello, World! "
                       print(a.strip())
            ouput      Hello, World!

4:Replace String--> The replace() method replaces a string with another string:

          for example  a = "Hello, World!"
                       print(a.replace("H", "J"))
            output     Jello, World!

5:Split String  -->The split() method returns a list where the text between the specified separator becomes the list items.
                -->The split() method splits the string into substrings if it finds instances of the separator:

          for example  a = "Hello, World!"
                      print(a.split(","))
           output     ['Hello', ' World!']

6:String Concatenation  -->To concatenate, or combine, two strings you can use the + operator.

          example 1-  a = "Hello"
                          b = "World"
                          c = a + b
                         print(c)
          output        HelloWorld
NOTE -->   To add a space between them, add a " ":

          example 2    a = "Hello"
                       b = "World"
                       c = a + " " + b
                       print(c)
          output       Hello  World

​



           
