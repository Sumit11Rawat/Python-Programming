        STRING SLICING

Python slicing is about obtaining a sub-string from the given string by slicing it respectively from start to end. 

Python slicing can be done in two ways:
               
              Using a slice() method
              Using the array slicing  [:: ] method

Index tracking for positive and negative indexing

     for example     0  1  2  3  4
                     S  U  M  I  T
                    -5 -4 -3 -2 -1
      NOTE -> while traversing the string from front indexing start from 0 and continues till n-1
           -> while traversing the string from end indexing start from -1 from the last element and increases in negative index backwards

Method 1:      Using the slice() method

The slice() constructor creates a slice object representing the set of indices specified by range(start, stop, step).


          for example-> String = 'ASTRING'
                        s1 = slice(3)
                        s2 = slice(1, 5, 2)
                        s3 = slice(-1, -12, -2)
                        print("String slicing")
                        print(String[s1])
                        print(String[s2])
                        print(String[s3])

          output-   String slicing
                    AST
                    SR
                    GITA

        NOTE -> if start stop or step is not given it will be automatically taken default
               default value -->start=0
                             -->stop=n-1
                             -->step=1
             ->  the last index of stop is not counted while slicing

Method 2:      Using the List/array slicing  [start: stop: step]  method

->>This is an easy and convenient way to slice a string using list slicing and Array slicing both syntax-wise and execution-wise. 
    A start, end, and step have the same mechanism as the slice() constructor. 

              for example   string='SUMITRAWAT'
                            print(string[1:5:1]
                            print(string[:7:2]
                            print(string[::3]
                            print(string[-1:-8:-2]

                output      UMIT
                            SMTA
                            SIAT
                            TWRI

                             

       
