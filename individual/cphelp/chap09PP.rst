


Chapter 9: Programming Projects
===============================

::

    
     1. The information kept about a part includes part number,
        part description, unit of measure( pounds, ounces, 
        liters, gallons, etc), unit cost, quantity on hand (in 
        the inventory), reorder point (value for quantity on 
        hand at which point an order for additional parts 
        should be made), stock room ( four character 
        identifier) and bin number ( four digits). 
    
        Write a program that allows a user to enter part 
        information for up to a maximum of 30 parts from the 
        keyboard.  When the user is done, the program outputs a 
        report about the parts.   The program must ask the user 
        to select which report is to be produced.  A list of 
        parts in ascending order by part number or a list in 
        ascending order by stock room.  All output must be 
        nicely formatted into columns with column headings.  
        In addition, the program must pause when a screen is 
        full and ask if the next page is to be seen or the 
        program is to terminate. In addition, parts that have 
        quantity on hand values that are equal to or below the  
        reorder point should be flagged with an asterisk. 
    
        Write a C++ type declaration for a data structure that 
        will hold the information about a part as well as the 
        bound methods for the part.
    
     2. Write this program as a C++ program using structures 
        that have bound methods, functions.  Write a structure, 
         **struct card**, that will represent a card in a 
        standard deck of playing cards.  You will need to 
        represent both the suit (clubs, diamonds, hearts, or 
        spades) as well as the rank (A, K, Q, J, 10, 9, 8, 7, 
        6, 5, 4, 3, 2) of each card.  Note that a deck of 
        playing cards can be represented as an array declared 
        as 
    
        struct card deck[52];
    
        Also, the suit and the rank can both be expressed as 
        enumerated data types:
    
        enum rank {     TWO=2,THREE,FOUR,FIVE,SIX,SEVEN,EIGHT,NINE,TEN,
                  KING=10,QUEEN=10,JACK=10,ACE=11};
       
        enum suit { CLUBS,DIAMONDS,HEARTS,SPADES };
    
        as a result of the enumerated types the card deck could 
        be as follows:
    
        struct card
        {
             enum rank rval;
             enum suit sval;
        };
    
        Using the above structure write a program that will 
        present a menu with the following options:
    
        1.   Deal Five Cards
        2.   Deal Seven Cards
        3.   Quit the Game
    
        Enter Selection:
    
        For either of the deal options, the program will call a 
        function that performs a shuffle of the deck.  In a 
        perfect shuffle, the deck is broken exactly in half and 
        rearranged so that the first card is followed by the 
        27th card, followed by the second card, followed by the 
        28th card, and so on.  You may use a random number 
        generator to shuffle the deck of cards and not worry 
        about a perfect shuffle.  The program then asks for how 
        many players are at the table. There can be no more 
        than seven players at the table and no less than three 
        players.  The program will then deal cards, either five 
        cards per player or seven cards per player depending 
        upon the menu selection, to the players at the table.  
        The dealer, the program, always is dealt to last.  
        Using a simple scoring method of where A=11, K=Q=J=10, 
        and all other cards are of face value, compute and 
        display which hand holds the most points.  For a seven 
        card game, the highest five cards a player holds 
        composes the players hand. 
    
     3. Write this program as a C++ program using structures 
        that have bound methods, functions.  You are to write a 
        program that will read from  **stdin** a C program.  
        The program you write will process the input program 
        and break the program into keywords, identifiers, 
        constants, and function calls.  Your program will 
        build an array of structures that will represent a 
        symbol table for the processed program.   **For this 
        assignment the program you **  **write will only look 
        for C keywords.** The structure will look as follows: 
    
        struct symtbl
        {
             /*
             *    type of symbol: K=keyword, I=identifier, 
             *    C=constant, F=function
             */
             char symtype;
             /*
             *    the symbol itself: the keyword, identifier, 
             *    constant or function name
             /*
             char *symbol;
             /*
             *    the location of the symbol within the
             *    program, 
             *    in our case we will use the line number with 
             *    the first line being 1; multiple occurrences of 
             *    the same symbol simply require another line number
             *    entry
             */
             int *symloc;
             /*
             *    the symbol data type: this applies only to 
             *    identifiers, variables, that the programmer 
             *    declared; C=char, I=integer, S=short, L=long
             *    F=float, D=double, X=structure,
             *    U=union, E=enumerated
             */
             char datatype;
             /*
             *    the size, in bytes of memory, that each of the 
             *    above data types occupies
             */
             int datasize;
        };
    
    The keywords for ANSI C are:
    
        auto      break     case      char      const     continue
        default   do        double    else      enum      extern
        float     for       goto      if        int       long
        register  return    short     signed    sizeof    static
        struct    switch    typedef   union     unsigned  void
        volatile  while
    
        When done processing the program, print the array out 
        in sorted order by symbol type.  
    
     **HINT:** To read from  **stdin**, simply use  **gets()** to read from the keyboard.  When the program 
    is run, then redirect the input to come from a file, the 
    source file holding the program to be processed.  Remember, that C supports 256 byte lines for source programs.  When printing the final report, use  **printf()** or 
     **cout** and redirect the  **stdout** to a file, then 
    send that file to the printer. 
    




