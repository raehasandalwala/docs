


Chapter 12: Programming Exercises
=================================

::

    
    //
    //  student.cpp - example of inheritance
    //
    #include 
    #include 
    #include 
    
    enum YEAR { FRESH, SOPH, JUNIOR, SENIOR };
    enum SUPPORT {TA, RA, FELLOWSHIP, OTHER };
    
    class Student
    {
    public:
        //   Constructors
        Student()
        {
             student_id = 0;
             gpa = 0.0;
             college[0] = '\0';
             yr = FRESH;
             major [0] = '\0';
        }
        Student( int id, float g )
        {
             student_id = id;
             gpa = g;
             college[0] = '\0';
             yr = FRESH;
             major [0] = '\0';
        }
        //   prompt for and read values
        virtual void read( void );
        //   print values held
        virtual void print( void );
    
    protected:
        int student_id;     // student ssn
        float gpa;          // student grade point average
        char name[30];      // student name
        char college[20];   // college name
        YEAR yr;            // year in college
        char major[10];     // area of study
    
    };
    
    
    class GradStudent : public Student
    {
    public:
        // Constructors
        GradStudent() : Student()
        {
             supp = TA;
             dept[0] = '\0';
             thesis[0] = '\0';
        }
        GradStudent( SUPPORT x, int id, float g)
             : Student(id, g)
        {
             supp = x;
             dept[0] = '\0';
             thesis[0] = '\0';
        }
        // implementation of base class virtual functions
        void print( void );
        void read( void );
    
    private:
        SUPPORT supp;
        char dept[10];
        char thesis[80];
    
    };
    
     1. Implement the following methods for both of the above 
        classes.
    
        For the Student class code the implementation of:
    
        A. virtual void read( void );
       
    
        B. virtual void print();
    
        For the GradStudent class code the implementation of:
    
        A. virtual void read( void );
    
        B. virtual void print();
    
     2. Write a test program that will demonstrate the 
        inheritance relationship between the Student and the 
        GradStudent classes.




