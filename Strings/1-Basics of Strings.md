
                           STRING
                           
->It is a built in data type of python that stores sequence of characters
                             
  -> Python does not have a character data type, a single character is simply a string with a length of 1.
 
  ->Strings in python are surrounded by either single quotation marks, or double quotation marks.
          
   ->You can display a string literal with the print() function:

Assign String to a Variable
                     
                 for example     a = "Hello"
                                 print(a)
                    output      Hello
Multiline Strings  ->You can assign a multiline string to a variable by using three quotes Or three single quotes:

                 for example-    a="""This is a 
                                       multiline string"""
                                 print(a);
                    output   This is a 
                              multiline string
Access String Characters in Python ->    Indexing: One way is to treat strings as a list and use index values   
       
                         for example    greet = 'hello'
                                        print(greet[1])
                          output         e
Python Strings are immutable  ->In Python, strings are immutable. That means the characters of a string cannot be changed.

String Length    ->To get the length of a string, use the len() function.

                    for example   a = "Hello, World!"
                                  print(len(a))
                      output      13

Check String   ->   To check if a certain phrase or character is present in a string, we can use the keyword in.

                         for example   txt = "The best things in life are free!"
                                       print("free" in txt)
                                       or
                                       txt = "The best things in life are free!"
                                       if "free" in txt:
                                       print("Yes, 'free' is present.")
                          output       true

Check if NOT     -> To check if a certain phrase or character is NOT present in a string, we can use the keyword not in.

                          for example  txt = "The best things in life are free!"
                                       print("expensive" not in txt)
                          output       true
                    

              

                 
