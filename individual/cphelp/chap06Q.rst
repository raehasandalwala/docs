


Chapter 6: Review Questions
===========================

::

    
     1. The syntax of a function call statement is
    
        a) function name (argument list);
    
        b) [storage class] function name (parameter list);
    
        c) function name (parameter list);
    
        d) [return type] function name (argument list);
    
     2.  The syntax of a user-defined function is (where [] 
         enclose optional items):
    
        a) [storage class] [return type] [function name] (parameters)
    
        b) [storage class] [return type] function name
    
        c) [storage class] [return type] function name (parameters)
    
        d) storage class [function name] (parameters)
    
     3. When defining the storage class for a function, which 
        storage class represents the default class?
    
        a) automatic
    
        b) external
    
        c) static
    
        d) register
    
     4. Functions written to produce a result needed by another 
        part of a program require, as part of their definition, 
        a
    
        a) storage class
    
        b) return value
    
        c) return type
    
        d) function call
    
     5. Which  of  the following storage classes can always be 
        accessed by all of the functions in a program?
    
        a) static
    
        b) external
    
        c) automatic
    
        d) register
    
     6. Given the following code fragment, what is the value of 
        x after the function count() is called and executed 
        twice?
    
        int count()
        {
    	    static int x = 0;
    	    x += 1;
        }
    
        a) 0
    
        b) 1
    
        c) 2
    
        d) more than 2
    
     7. What  is  the  purpose  of  the  term  'return type' in 
        a function definition?
    
        a) To specify the data type of the function.
    
        b) To specify the type  of data the function returns.
    
        c) to specify the type of variables used as parameters.
    
        d) To specify the type of variables passed to the
    	 function.
    
     8. Which one of the following best describes a function 
        call?
    
        a) Identifies the type of data returned from a function
           and the function's storage class.
    
        b) Defines the operation a function must perform.
    
        c) Identifies the function parameters.
    
        d) States the name of the function and passes
    	 arguments.
    
     9.  Which one of the following best describes a function 
         definition?
    
        a) Allocates a storage location for the return value.
    
        b) Contains the statements that indicate the function
           name and parameters to be used in processing.
    
        c) Calls a predefined function and passes the necessary
    	 arguments.
    
        d) Tells the compiler which function you are using.
    
    10. The arguments passed to a function are
    
        a) global variables visible to all functions
    
        b) local variables to the receiving function
    
        c) not allowed to be used by the receiving function
    
        d) available only in ANSI C




