


Chapter 9: Review Questions
===========================

::

    
     T  F    1.   A structure does not need to contain objects
                  that are of like type.
    
     T  F    2.   The structure tag does not reserve storage 
                  for the structure, but instead gives a name 
                  to the structure skeleton.
    
     T  F    3.   Aggregate data types include arrays, 
                  structures, and unions.
    
     T  F    4.   Structures are passed by value when they are 
                  used as array arguments.
    
     T  F    5.   The dot operator requires a structure 
                  variable name or expression on the left side 
                  of the dot.
    
     T  F    6.  Only structure variables, not structure tags, 
                 can be initialized.
    
     T  F    7.  Only constant values can be used to initialize 
                 structures when they are defined.
    
     T  F    8.  Structures that will be used in more than one 
                 source file should be placed into a header 
                 file.
    
     T  F    9.  Structures can be nested only four levels 
                 deep, a limitation that still allows the 
                 creation of complex data structures.
    
     T  F    10.  Both the  **typedef** and the 
                   **#define** command can be used to 
                  simplify the creation of structure 
                  variables apart from the initial definition 
                  of the structure.
    
    11. The term ADT (abstract data type) refers to:
    
        a.   A data type not possible in the C language.
        b.   A data type possessing high-level properties.
        c.   A tree none only.
        d.   A C structure only.
    
    12. Every node in a tree structure possesses certain 
        attributes. 
    
        They are:
    
        a.   A value, one or more children (except terminal 
             nodes), and a parent (except the root).
        b.   A value, pointers.
        c.   A value, pointers, children, and parents.
        d.   Pointers only.
    
    13. Consider the following ADT:
    
        customer_record          Example
             customer name       Jones, Bill
             previous payment    40.00
             account balance     545.75
             past due? (Y/N)     N
    
        Which structure definition below would best represent 
         **customer_record**?
    
        a.   struct customer_record
             {
                  char *name;
                  union
                  {
                       float previous_payment;
                       float account_balance;
                  };
                  float past_due;
             };
        b.   struct customer_record
             {
                  char *name;
                  float previous_payment;
                  float account_balance;
                  float past_due;
             };
        c.   struct customer_record
             {
                  char *name;
                  float previous_payment;
                  float account_balance;
                  char past_due;
             };
        d.   struct customer_record
             {
                  char *name;
                  float previous_payment;
                  float account_balance;
                  int past_due:1;
             };
        
    14. What is wrong with the following structure definition?
    
        struct node
        {
             int node_number;
             char value1[20];
             char *value2;
             struct node left_child;
             struct node right_child;
        };
    
        a.   An array may not be a structure member.
        b.   A structure may not contain an instance of itself.
        c.    **node_number** is not needed.
        d.   The structure has no definite size, which it must 
             have.
    
    15. What does the following statement reference?
    
        my_struct[2].value
    
        a.   The third element of the array  **value**.
        b.   The second member of  **my_struct** which is 
             called  **value**.
        c.   The third structure in the structure array 
              **my_struct** and its member  **value**.
        d.   None of the above.
    
    




