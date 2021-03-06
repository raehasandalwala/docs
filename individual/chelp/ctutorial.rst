====
The GNU C Reference Manual
====

Table of Contents
-----------------

-  `The GNU C Reference Manual <#Top>`_
-  `Preface <#Preface>`_

   -  `Credits <#Preface>`_

-  `1 Lexical Elements <#Lexical-Elements>`_

   -  `1.1 Identifiers <#Identifiers>`_
   -  `1.2 Keywords <#Keywords>`_
   -  `1.3 Constants <#Constants>`_

      -  `1.3.1 Integer Constants <#Integer-Constants>`_
      -  `1.3.2 Character Constants <#Character-Constants>`_
      -  `1.3.3 Real Number Constants <#Real-Number-Constants>`_
      -  `1.3.4 String Constants <#String-Constants>`_

   -  `1.4 Operators <#Operators>`_
   -  `1.5 Separators <#Separators>`_
   -  `1.6 White Space <#White-Space>`_

-  `2 Data Types <#Data-Types>`_

   -  `2.1 Primitive Data Types <#Primitive-Types>`_

      -  `2.1.1 Integer Types <#Integer-Types>`_
      -  `2.1.2 Real Number Types <#Real-Number-Types>`_
      -  `2.1.3 Complex Number Types <#Complex-Number-Types>`_

         -  `2.1.3.1 Standard Complex Number
            Types <#Standard-Complex-Number-Types>`_
         -  `2.1.3.2 GNU Extensions for Complex Number
            Types <#GNU-Extensions-for-Complex-Number-Types>`_

   -  `2.2 Enumerations <#Enumerations>`_

      -  `2.2.1 Defining Enumerations <#Defining-Enumerations>`_
      -  `2.2.2 Declaring Enumerations <#Declaring-Enumerations>`_

   -  `2.3 Unions <#Unions>`_

      -  `2.3.1 Defining Unions <#Defining-Unions>`_
      -  `2.3.2 Declaring Union Variables <#Declaring-Union-Variables>`_

         -  `2.3.2.1 Declaring Union Variables at
            Definition <#Declaring-Union-Variables-at-Definition>`_
         -  `2.3.2.2 Declaring Union Variables After
            Definition <#Declaring-Union-Variables-After-Definition>`_
         -  `2.3.2.3 Initializing Union
            Members <#Initializing-Union-Members>`_

      -  `2.3.3 Accessing Union Members <#Accessing-Union-Members>`_
      -  `2.3.4 Size of Unions <#Size-of-Unions>`_

   -  `2.4 Structures <#Structures>`_

      -  `2.4.1 Defining Structures <#Defining-Structures>`_
      -  `2.4.2 Declaring Structure
         Variables <#Declaring-Structure-Variables>`_

         -  `2.4.2.1 Declaring Structure Variables at
            Definition <#Declaring-Structure-Variables-at-Definition>`_
         -  `2.4.2.2 Declaring Structure Variables After
            Definition <#Declaring-Structure-Variables-After-Definition>`_
         -  `2.4.2.3 Initializing Structure
            Members <#Initializing-Structure-Members>`_

      -  `2.4.3 Accessing Structure
         Members <#Accessing-Structure-Members>`_
      -  `2.4.4 Bit Fields <#Bit-Fields>`_
      -  `2.4.5 Size of Structures <#Size-of-Structures>`_

   -  `2.5 Arrays <#Arrays>`_

      -  `2.5.1 Declaring Arrays <#Declaring-Arrays>`_
      -  `2.5.2 Initializing Arrays <#Initializing-Arrays>`_
      -  `2.5.3 Accessing Array Elements <#Accessing-Array-Elements>`_
      -  `2.5.4 Multidimensional Arrays <#Multidimensional-Arrays>`_
      -  `2.5.5 Arrays as Strings <#Arrays-as-Strings>`_
      -  `2.5.6 Arrays of Unions <#Arrays-of-Unions>`_
      -  `2.5.7 Arrays of Structures <#Arrays-of-Structures>`_

   -  `2.6 Pointers <#Pointers>`_

      -  `2.6.1 Declaring Pointers <#Declaring-Pointers>`_
      -  `2.6.2 Initializing Pointers <#Initializing-Pointers>`_
      -  `2.6.3 Pointers to Unions <#Pointers-to-Unions>`_
      -  `2.6.4 Pointers to Structures <#Pointers-to-Structures>`_

   -  `2.7 Incomplete Types <#Incomplete-Types>`_
   -  `2.8 Type Qualifiers <#Type-Qualifiers>`_
   -  `2.9 Storage Class Specifiers <#Storage-Class-Specifiers>`_
   -  `2.10 Renaming Types <#Renaming-Types>`_

-  `3 Expressions and Operators <#Expressions-and-Operators>`_

   -  `3.1 Expressions <#Expressions>`_
   -  `3.2 Assignment Operators <#Assignment-Operators>`_
   -  `3.3 Incrementing and
      Decrementing <#Incrementing-and-Decrementing>`_
   -  `3.4 Arithmetic Operators <#Arithmetic-Operators>`_
   -  `3.5 Complex Conjugation <#Complex-Conjugation>`_
   -  `3.6 Comparison Operators <#Comparison-Operators>`_
   -  `3.7 Logical Operators <#Logical-Operators>`_
   -  `3.8 Bit Shifting <#Bit-Shifting>`_
   -  `3.9 Bitwise Logical Operators <#Bitwise-Logical-Operators>`_
   -  `3.10 Pointer Operators <#Pointer-Operators>`_
   -  `3.11 The sizeof Operator <#The-sizeof-Operator>`_
   -  `3.12 Type Casts <#Type-Casts>`_
   -  `3.13 Array Subscripts <#Array-Subscripts>`_
   -  `3.14 Function Calls as
      Expressions <#Function-Calls-as-Expressions>`_
   -  `3.15 The Comma Operator <#The-Comma-Operator>`_
   -  `3.16 Member Access Expressions <#Member-Access-Expressions>`_
   -  `3.17 Conditional Expressions <#Conditional-Expressions>`_
   -  `3.18 Statements and Declarations in
      Expressions <#Statements-and-Declarations-in-Expressions>`_
   -  `3.19 Operator Precedence <#Operator-Precedence>`_
   -  `3.20 Order of Evaluation <#Order-of-Evaluation>`_

      -  `3.20.1 Side Effects <#Side-Effects>`_
      -  `3.20.2 Sequence Points <#Sequence-Points>`_
      -  `3.20.3 Sequence Points Constrain
         Expressions <#Sequence-Points-Constrain-Expressions>`_
      -  `3.20.4 Sequence Points and Signal
         Delivery <#Sequence-Points-and-Signal-Delivery>`_

-  `4 Statements <#Statements>`_

   -  `4.1 Labels <#Labels>`_
   -  `4.2 Expression Statements <#Expression-Statements>`_
   -  `4.3 The ``if`` Statement <#The-if-Statement>`_
   -  `4.4 The ``switch`` Statement <#The-switch-Statement>`_
   -  `4.5 The ``while`` Statement <#The-while-Statement>`_
   -  `4.6 The ``do`` Statement <#The-do-Statement>`_
   -  `4.7 The ``for`` Statement <#The-for-Statement>`_
   -  `4.8 Blocks <#Blocks>`_
   -  `4.9 The Null Statement <#The-Null-Statement>`_
   -  `4.10 The ``goto`` Statement <#The-goto-Statement>`_
   -  `4.11 The ``break`` Statement <#The-break-Statement>`_
   -  `4.12 The ``continue`` Statement <#The-continue-Statement>`_
   -  `4.13 The ``return`` Statement <#The-return-Statement>`_
   -  `4.14 The ``typedef`` Statement <#The-typedef-Statement>`_

-  `5 Functions <#Functions>`_

   -  `5.1 Function Declarations <#Function-Declarations>`_
   -  `5.2 Function Definitions <#Function-Definitions>`_
   -  `5.3 Calling Functions <#Calling-Functions>`_
   -  `5.4 Function Parameters <#Function-Parameters>`_
   -  `5.5 Variable Length Parameter
      Lists <#Variable-Length-Parameter-Lists>`_
   -  `5.6 Calling Functions Through Function
      Pointers <#Calling-Functions-Through-Function-Pointers>`_
   -  `5.7 The ``main`` Function <#The-main-Function>`_
   -  `5.8 Recursive Functions <#Recursive-Functions>`_
   -  `5.9 Static Functions <#Static-Functions>`_
   -  `5.10 Nested Functions <#Nested-Functions>`_

-  `6 Program Structure and Scope <#Program-Structure-and-Scope>`_

   -  `6.1 Program Structure <#Program-Structure>`_
   -  `6.2 Scope <#Scope>`_

-  `7 A Sample Program <#A-Sample-Program>`_

   -  `7.1 ``hello.c`` <#hello_002ec>`_
   -  `7.2 ``system.h`` <#system_002eh>`_

-  `Appendix A Overflow <#Overflow>`_

   -  `A.1 Basics of Integer Overflow <#Integer-Overflow-Basics>`_
   -  `A.2 Examples of Code Assuming Wraparound
      Overflow <#Signed-Overflow-Examples>`_
   -  `A.3 Optimizations That Break Wraparound
      Arithmetic <#Optimization-and-Wraparound>`_
   -  `A.4 Practical Advice for Signed Overflow
      Issues <#Signed-Overflow-Advice>`_
   -  `A.5 Signed Integer Division and Integer
      Overflow <#Signed-Integer-Division>`_

-  `GNU Free Documentation License <#GNU-Free-Documentation-License>`_
-  `Index <#Index>`_

--------------

Next: `Preface <#Preface>`_, Up: `(dir) <#dir>`_

The GNU C Reference Manual
--------------------------

This is the GNU C reference manual.

-  `Preface <#Preface>`_
-  `Lexical Elements <#Lexical-Elements>`_
-  `Data Types <#Data-Types>`_
-  `Expressions and Operators <#Expressions-and-Operators>`_
-  `Statements <#Statements>`_
-  `Functions <#Functions>`_
-  `Program Structure and Scope <#Program-Structure-and-Scope>`_
-  `A Sample Program <#A-Sample-Program>`_
-  `Overflow <#Overflow>`_
-  `GNU Free Documentation License <#GNU-Free-Documentation-License>`_
-  `Index <#Index>`_

--------------

Next: `Lexical Elements <#Lexical-Elements>`_, Previous: `Top <#Top>`_,
Up: `Top <#Top>`_

Preface
-------

This is a reference manual for the C programming language as implemented
by the GNU Compiler Collection (GCC). Specifically, this manual aims to
document:

-  The 1989 ANSI C standard, commonly known as “C89”
-  The 1999 ISO C standard, commonly known as “C99”, to the extent that
   C99 is implemented by GCC
-  The current state of GNU extensions to standard C

This manual describes C89 as its baseline. C99 features and GNU
extensions are explicitly labeled as such.

By default, GCC will compile code as C89 plus GNU-specific extensions.
Much of C99 is supported; once full support is available, the default
compilation dialect will be C99 plus GNU-specific extensions. (Some of
the GNU extensions to C89 ended up, sometimes slightly modified, as
standard language features in C99.)

The C language includes a set of preprocessor directives, which are used
for things such as macro text replacement, conditional compilation, and
file inclusion. Although normally described in a C language manual, the
GNU C preprocessor has been thoroughly documented in The C Preprocessor,
a separate manual which covers preprocessing for C, C++, and Objective-C
programs, so it is not included here.

Credits
~~~~~~~

Contributors who have helped with writing, editing, proofreading, ideas,
typesetting, or administrative details include: Nelson H. F. Beebe, Karl
Berry, Robert Chassell, Andreas Foerster, Denver Gingerich, Lisa
Goldstein, Robert Hansen, Jean-Christophe Helary, Teddy Hogeborn, Joe
Humphries, J. Wren Hunt, Adam Johansen, Steve Morningthunder, Richard
Stallman, J. Otto Tennant, Ole Tetlie, Keith Thompson, T.F. Torrey, and
James Youngman. Trevis Rothwell wrote most of the text and serves as
project maintainer.

Some example programs are based on algorithms in Donald Knuth's The Art
of Computer Programming.

Please send bug reports and suggestions to
`gnu-c-manual@gnu.org <mailto:gnu-c-manual@gnu.org>`_.

--------------

Next: `Data Types <#Data-Types>`_, Previous: `Preface <#Preface>`_, Up:
`Top <#Top>`_

1 Lexical Elements
------------------

This chapter describes the lexical elements that make up C source code
after preprocessing. These elements are called tokens. There are five
types of tokens: keywords, identifiers, constants, operators, and
separators. White space, sometimes required to separate tokens, is also
described in this chapter.

-  `Identifiers <#Identifiers>`_
-  `Keywords <#Keywords>`_
-  `Constants <#Constants>`_
-  `Operators <#Operators>`_
-  `Separators <#Separators>`_
-  `White Space <#White-Space>`_

--------------

Next: `Keywords <#Keywords>`_, Up: `Lexical
Elements <#Lexical-Elements>`_

1.1 Identifiers
~~~~~~~~~~~~~~~

Identifiers are sequences of characters used for naming variables,
functions, new data types, and preprocessor macros. You can include
letters, decimal digits, and the underscore character ‘\_’ in
identifiers.

The first character of an identifier cannot be a digit.

Lowercase letters and uppercase letters are distinct, such that ``foo``
and ``FOO`` are two different identifiers.

When using GNU extensions, you can also include the dollar sign
character ‘$’ in identifiers.

--------------

Next: `Constants <#Constants>`_, Previous:
`Identifiers <#Identifiers>`_, Up: `Lexical
Elements <#Lexical-Elements>`_

1.2 Keywords
~~~~~~~~~~~~

Keywords are special identifiers reserved for use as part of the
programming language itself. You cannot use them for any other purpose.

Here is a list of keywords recognized by ANSI C89:

::

         auto break case char const continue default do double else enum extern
         float for goto if int long register return short signed sizeof static
         struct switch typedef union unsigned void volatile while

ISO C99 adds the following keywords:

::

         inline _Bool _Complex _Imaginary

and GNU extensions add these keywords:

::

         __FUNCTION__ __PRETTY_FUNCTION__ __alignof __alignof__ __asm
         __asm__ __attribute __attribute__ __builtin_offsetof __builtin_va_arg
         __complex __complex__ __const __extension__ __func__ __imag __imag__
         __inline __inline__ __label__ __null __real __real__
         __restrict __restrict__ __signed __signed__ __thread __typeof
         __volatile __volatile__

In both ISO C99 and C89 with GNU extensions, the following is also
recogized as a keyboard:

::

         restrict

--------------

Next: `Operators <#Operators>`_, Previous: `Keywords <#Keywords>`_, Up:
`Lexical Elements <#Lexical-Elements>`_

1.3 Constants
~~~~~~~~~~~~~

A constant is a literal numeric or character value, such as 5 or \`m'.
All constants are of a particular data type; you can use type casting to
explicitly specify the type of a constant, or let the compiler use the
default type based on the value of the constant.

-  `Integer Constants <#Integer-Constants>`_
-  `Character Constants <#Character-Constants>`_
-  `Real Number Constants <#Real-Number-Constants>`_
-  `String Constants <#String-Constants>`_

--------------

Next: `Character Constants <#Character-Constants>`_, Up:
`Constants <#Constants>`_

1.3.1 Integer Constants
^^^^^^^^^^^^^^^^^^^^^^^

An integer constant is a sequence of digits, with an optional prefix to
denote a number base.

If the sequence of digits is preceded by ``0x`` or ``0X`` (zero x or
zero X), then the constant is considered to be hexadecimal (base 16).
Hexadecimal values may use the digits from 0 to 9, as well as the
letters ``a`` to ``f`` and ``A`` to ``F``. Here are some examples:

::

         0x2f
         0x88
         0xAB43
         0xAbCd
         0x1

If the first digit is 0 (zero), and the next character is not ‘x’ or
‘X’, then the constant is considered to be octal (base 8). Octal values
may only use the digits from 0 to 7; 8 and 9 are not allowed. Here are
some examples:

::

         057
         012
         03
         0241

In all other cases, the sequence of digits is assumed to be decimal
(base 10). Decimal values may use the digits from 0 to 9. Here are some
examples:

::

         459
         23901
         8
         12

There are various integer data types, for short integers, long integers,
signed integers, and unsigned integers. You can force an integer
constant to be of a long and/or unsigned integer type by appending a
sequence of one or more letters to the end of the constant:

``u``

``U``

Unsigned integer type.

``l``

``L``

Long integer type.

For example, ``45U`` is an ``unsigned int`` constant. You can also
combine letters: ``45UL`` is an ``unsigned long int`` constant. (The
letters may be used in any order.)

Both ISO C99 and GNU C extensions add the integer types
``long long int`` and ``unsigned long long int``. You can use two ‘L’s
to get a ``long long int`` constant; add a ‘U’ to that and you have an
``unsigned long long int`` constant. For example: ``45ULL``.

--------------

Next: `Real Number Constants <#Real-Number-Constants>`_, Previous:
`Integer Constants <#Integer-Constants>`_, Up: `Constants <#Constants>`_

1.3.2 Character Constants
^^^^^^^^^^^^^^^^^^^^^^^^^

A character constant is usually a single character enclosed within
single quotation marks, such as ``'Q'``. A character constant is of type
``int`` by default.

Some characters, such as the single quotation mark character itself,
cannot be represented using only one character. To represent such
characters, there are several “escape sequences” that you can use:

``\\``

Backslash character.

``\?``

Question mark character.

``\'``

Single quotation mark.

``\"``

Double quotation mark.

``\a``

Audible alert.

``\b``

Backspace character.

``\e``

<ESC> character. (This is a GNU extension.)

``\f``

Form feed.

``\n``

Newline character.

``\r``

Carriage return.

``\t``

Horizontal tab.

``\v``

Vertical tab.

``\o, \oo, \ooo``

Octal number.

``\xh, \xhh, \xhhh, ...``

Hexadecimal number.

To use any of these escape sequences, enclose the sequence in single
quotes, and treat it as if it were any other character. For example, the
letter m is ``'m'`` and the newline character is ``'\n'``.

The octal number escape sequence is the backslash character followed by
one, two, or three octal digits (0 to 7). For example, 101 is the octal
equivalent of 65, which is the ASCII character ``'A'``. Thus, the
character constant ``'\101'`` is the same as the character constant
``'A'``.

The hexadecimal escape sequence is the backslash character, followed by
``x`` and an unlimited number of hexadecimal digits (0 to 9, and ``a``
to ``f`` or ``A`` to ``F``).

While the length of possible hexadecimal digit strings is unlimited, the
number of character constants in any given character set is not. (The
much-used extended ASCII character set, for example, has only 256
characters in it.) If you try to use a hexadecimal value that is outside
the range of characters, you will get a compile-time error.

--------------

Next: `String Constants <#String-Constants>`_, Previous: `Character
Constants <#Character-Constants>`_, Up: `Constants <#Constants>`_

1.3.3 Real Number Constants
^^^^^^^^^^^^^^^^^^^^^^^^^^^

A real number constant is a value that represents a fractional (floating
point) number. It consists of a sequence of digits which represents the
integer (or “whole”) part of the number, a decimal point, and a sequence
of digits which represents the fractional part.

Either the integer part or the fractional part may be omitted, but not
both. Here are some examples:

::

         double a, b, c, d, e, f;
         
         a = 4.7;
         
         b = 4.;
         
         c = 4;
         
         d = .7;
         
         e = 0.7;

(In the third assignment statement, the integer constant 4 is
automatically converted from an integer value to a double value.)

Real number constants can also be followed by ``e`` or ``E``, and an
integer exponent. The exponent can be either positive or negative.

::

         double x, y;
         
         x = 5e2;   /* x is 5 * 100, or 500.0. */
         y = 5e-2;  /* y is 5 * (1/100, or 0.05. */

You can append a letter to the end of a real number constant to cause it
to be of a particular type. If you append the letter F (or f) to a real
number constant, then its type is ``float``. If you append the letter L
(or l), then its type is ``long double``. If you do not append any
letters, then its type is ``double``.

--------------

Previous: `Real Number Constants <#Real-Number-Constants>`_, Up:
`Constants <#Constants>`_

1.3.4 String Constants
^^^^^^^^^^^^^^^^^^^^^^

A string constant is a sequence of zero or more characters, digits, and
escape sequences enclosed within double quotation marks. A string
constant is of type “array of characters”. All string constants contain
a null termination character (``\0``) as their last character. Strings
are stored as arrays of characters, with no inherent size attribute. The
null termination character lets string-processing functions know where
the string ends.

Adjacent string constants are concatenated (combined) into one string,
with the null termination character added to the end of the final
concatenated string.

A string cannot contain double quotation marks, as double quotation
marks are used to enclose the string. To include the double quotation
mark character in a string, use the ``\"`` escape sequence. You can use
any of the escape sequences that can be used as character constants in
strings. Here are some example of string constants:

::

         /* This is a single string constant. */
         "tutti frutti ice cream"
         
         /* These string constants will be concatenated, same as above. */
         "tutti " "frutti" " ice " "cream"
         
         /* This one uses two escape sequences. */
         "\"hello, world!\""

If a string is too long to fit on one line, you can use a backslash
``\`` to break it up onto separate lines.

::

         "Today's special is a pastrami sandwich on rye bread with \
         a potato knish and a cherry soda."

Adjacent strings are automatically concatenated, so you can also have
string constants span multiple lines by writing them as separate,
adjacent, strings. For example:

::

         "Tomorrow's special is a corned beef sandwich on "
         "pumpernickel bread with a kasha knish and seltzer water."

is the same as

::

         "Tomorrow's special is a corned beef sandwich on \
         pumpernickel bread with a kasha knish and seltzer water."

To insert a newline character into the string, so that when the string
is printed it will be printed on two different lines, you can use the
newline escape sequence ‘\\n’.

::

         printf ("potato\nknish");

prints

::

         potato
         knish

--------------

Next: `Separators <#Separators>`_, Previous: `Constants <#Constants>`_,
Up: `Lexical Elements <#Lexical-Elements>`_

1.4 Operators
~~~~~~~~~~~~~

An operator is a special token that performs an operation, such as
addition or subtraction, on either one, two, or three operands. Full
coverage of operators can be found in a later chapter. See `Expressions
and Operators <#Expressions-and-Operators>`_.

--------------

Next: `White Space <#White-Space>`_, Previous:
`Operators <#Operators>`_, Up: `Lexical Elements <#Lexical-Elements>`_

1.5 Separators
~~~~~~~~~~~~~~

A separator separates tokens. White space (see next section) is a
separator, but it is not a token. The other separators are all
single-character tokens themselves:

::

         ( ) [ ] { } ; , . :

--------------

Previous: `Separators <#Separators>`_, Up: `Lexical
Elements <#Lexical-Elements>`_

1.6 White Space
~~~~~~~~~~~~~~~

White space is the collective term used for several characters: the
space character, the tab character, the newline character, the vertical
tab character, and the form-feed character. White space is ignored
(outside of string and character constants), and is therefore optional,
except when it is used to separate tokens. This means that

::

         #include <stdio.h>
         
         int
         main()
         {
           printf( "hello, world\n" );
           return 0;
         }

and

::

         #include <stdio.h> int main(){printf("hello, world\n");
         return 0;}

are functionally the same program.

Although you must use white space to separate many tokens, no white
space is required between operators and operands, nor is it required
between other separators and that which they separate.

::

         /* All of these are valid. */
         
         x++;
         x ++ ;
         x=y+z;
         x = y + z ;
         x=array[2];
         x = array [ 2 ] ;
         fraction=numerator / *denominator_ptr;
         fraction = numerator / * denominator_ptr ;

Furthermore, wherever one space is allowed, any amount of white space is
allowed.

::

         /* These two statements are functionally identical. */
         x++;
         
         x
                ++       ;

In string constants, spaces and tabs are not ignored; rather, they are
part of the string. Therefore,

::

         "potato knish"

is not the same as

::

         "potato                        knish"

--------------

Next: `Expressions and Operators <#Expressions-and-Operators>`_,
Previous: `Lexical Elements <#Lexical-Elements>`_, Up: `Top <#Top>`_

2 Data Types
------------

-  `Primitive Types <#Primitive-Types>`_
-  `Enumerations <#Enumerations>`_
-  `Unions <#Unions>`_
-  `Structures <#Structures>`_
-  `Arrays <#Arrays>`_
-  `Pointers <#Pointers>`_
-  `Incomplete Types <#Incomplete-Types>`_
-  `Type Qualifiers <#Type-Qualifiers>`_
-  `Storage Class Specifiers <#Storage-Class-Specifiers>`_
-  `Renaming Types <#Renaming-Types>`_

--------------

Next: `Enumerations <#Enumerations>`_, Up: `Data Types <#Data-Types>`_

2.1 Primitive Data Types
~~~~~~~~~~~~~~~~~~~~~~~~

-  `Integer Types <#Integer-Types>`_
-  `Real Number Types <#Real-Number-Types>`_
-  `Complex Number Types <#Complex-Number-Types>`_

--------------

Next: `Real Number Types <#Real-Number-Types>`_, Up: `Primitive
Types <#Primitive-Types>`_

2.1.1 Integer Types
^^^^^^^^^^^^^^^^^^^

The integer data types range in size from at least 8 bits to at least 32
bits. The C99 standard extends this range to include integer sizes of at
least 64 bits. You should use integer types for storing whole number
values (and the ``char`` data type for storing characters). The sizes
and ranges listed for these types are minimums; depending on your
computer platform, these sizes and ranges may be larger.

While these ranges provide a natural ordering, the standard does not
require that any two types have a different range. For example, it is
common for ``int`` and ``long`` to have the same range. The standard
even allows ``signed char`` and ``long`` to have the same range, though
such platforms are very unusual.

-  ``signed char``
    The 8-bit ``signed char`` data type can hold integer values in the
   range of −128 to 127.
-  ``unsigned char``
    The 8-bit ``unsigned char`` data type can hold integer values in the
   range of 0 to 255.
-  ``char``
    Depending on your system, the ``char`` data type is defined as
   having the same range as either the ``signed char`` or the
   ``unsigned char`` data type (they are three distinct types, however).
   By convention, you should use the ``char`` data type specifically for
   storing ASCII characters (such as ```m'``), including escape
   sequences (such as ```\n'``).
-  ``short int``
    The 16-bit ``short int`` data type can hold integer values in the
   range of −32,768 to 32,767. You may also refer to this data type as
   ``short``, ``signed short int``, or ``signed short``.
-  ``unsigned short int``
    The 16-bit ``unsigned short int`` data type can hold integer values
   in the range of 0 to 65,535. You may also refer to this data type as
   ``unsigned short``.
-  ``int``
    The 32-bit ``int`` data type can hold integer values in the range of
   −2,147,483,648 to 2,147,483,647. You may also refer to this data type
   as ``signed int`` or ``signed``.
-  ``unsigned int``
    The 32-bit ``unsigned int`` data type can hold integer values in the
   range of 0 to 4,294,967,295. You may also refer to this data type
   simply as ``unsigned``.
-  ``long int``
    The 32-bit ``long int`` data type can hold integer values in the
   range of at least −2,147,483,648 to 2,147,483,647. (Depending on your
   system, this data type might be 64-bit, in which case its range is
   identical to that of the ``long long int`` data type.) You may also
   refer to this data type as ``long``, ``signed long int``, or
   ``signed long``.
-  ``unsigned long int``
    The 32-bit ``unsigned long int`` data type can hold integer values
   in the range of at least 0 to 4,294,967,295. (Depending on your
   system, this data type might be 64-bit, in which case its range is
   identical to that of the ``unsigned long long int`` data type.) You
   may also refer to this data type as ``unsigned long``.
-  ``long long int``
    The 64-bit ``long long int`` data type can hold integer values in
   the range of −9,223,372,036,854,775,808 to 9,223,372,036,854,775,807.
   You may also refer to this data type as ``long long``,
   ``signed long long int`` or ``signed long long``. This type is not
   part of C89, but is both part of C99 and a GNU C extension.
-  ``unsigned long long int``
    The 64-bit ``unsigned long long int`` data type can hold integer
   values in the range of at least 0 to 18,446,744,073,709,551,615. You
   may also refer to this data type as ``unsigned long long``. This type
   is not part of C89, but is both part of C99 and a GNU C extension.

Here are some examples of declaring and defining integer variables:

::

         int foo;
         unsigned int bar = 42;
         char quux = 'a';

The first line declares an integer named ``foo`` but does not define its
value; it is left unintialized, and its value should not be assumed to
be anything in particular.

--------------

Next: `Complex Number Types <#Complex-Number-Types>`_, Previous:
`Integer Types <#Integer-Types>`_, Up: `Primitive
Types <#Primitive-Types>`_

2.1.2 Real Number Types
^^^^^^^^^^^^^^^^^^^^^^^

There are three data types that represent fractional numbers. While the
sizes and ranges of these types are consistent across most computer
systems in use today, historically the sizes of these types varied from
system to system. As such, the minimum and maximum values are stored in
macro definitions in the library header file ``float.h``. In this
section, we include the names of the macro definitions in place of their
possible values; check your system's ``float.h`` for specific numbers.

-  ``float``
    The ``float`` data type is the smallest of the three floating point
   types, if they differ in size at all. Its minimum value is stored in
   the ``FLT_MIN``, and should be no greater than ``1e-37``. Its maximum
   value is stored in ``FLT_MAX``, and should be no less than ``1e37``.
-  ``double``
    The ``double`` data type is at least as large as the ``float`` type,
   and it may be larger. Its minimum value is stored in ``DBL_MIN``, and
   its maximum value is stored in ``DBL_MAX``.
-  ``long double``
    The ``long double`` data type is at least as large as the ``float``
   type, and it may be larger. Its minimum value is stored in
   ``LDBL_MIN``, and its maximum value is stored in ``LDBL_MAX``.

All floating point data types are signed; trying to use
``unsigned float``, for example, will cause a compile-time error.

Here are some examples of declaring and defining real number variables:

::

         float foo;
         double bar = 114.3943;

The first line declares a float named ``foo`` but does not define its
value; it is left unintialized, and its value should not be assumed to
be anything in particular.

The real number types provided in C are of finite precision, and
accordingly, not all real numbers can be represented exactly. Most
computer systems that GCC compiles for use a binary representation for
real numbers, which is unable to precisely represent numbers such as,
for example, 4.2. For this reason, we recommend that you consider not
comparing real numbers for exact equality with the ``==`` operator, but
rather check that real numbers are within an acceptable tolerance.

There are other more subtle implications of these imprecise
representations; for more details, see David Goldberg's paper What Every
Computer Scientist Should Know About Floating-Point Arithmetic and
section 4.2.2 of Donald Knuth's The Art of Computer Programming.

--------------

Previous: `Real Number Types <#Real-Number-Types>`_, Up: `Primitive
Types <#Primitive-Types>`_

2.1.3 Complex Number Types
^^^^^^^^^^^^^^^^^^^^^^^^^^

GCC introduced some complex number types as an extension to C89. Similar
features were introduced in C99`\ :sup:`1`\  <#fn-1>`_, but there were a
number of differences. We describe the standard complex number types
first.

-  `Standard Complex Number Types <#Standard-Complex-Number-Types>`_
-  `GNU Extensions for Complex Number
   Types <#GNU-Extensions-for-Complex-Number-Types>`_

--------------

Next: `GNU Extensions for Complex Number
Types <#GNU-Extensions-for-Complex-Number-Types>`_, Up: `Complex Number
Types <#Complex-Number-Types>`_

2.1.3.1 Standard Complex Number Types
'''''''''''''''''''''''''''''''''''''

Complex types were introduced in C99. There are three complex types:

-  ``float _Complex``
-  ``double _Complex``
-  ``long double _Complex``

The names here begin with an underscore and an uppercase letter in order
to avoid conflicts with existing programs' identifiers. However, the C99
standard header file ``<complex.h>`` introduces some macros which make
using complex types easier.

-  ``complex``
    Expands to ``_Complex``. This allows a variable to be declared as
   ``double complex`` which seems more natural.
-  ``I``
    A constant of type ``const float _Complex`` having the value of the
   imaginary unit normally referred to as i.

The ``<complex.h>`` header file also declares a number of functions for
performing computations on complex numbers, for example the ``creal``
and ``cimag`` functions which respectively return the real and imaginary
parts of a ``double complex`` number. Other functions are also provided,
as shown in this example:

::

         #include <complex.h>
         #include <stdio.h>
         
         void example (void)
         {
           complex double z = 1.0 + 3.0*I;
           printf ("Phase is %f, modulus is %f\n", carg (z), cabs (z));
         }

--------------

Previous: `Standard Complex Number
Types <#Standard-Complex-Number-Types>`_, Up: `Complex Number
Types <#Complex-Number-Types>`_

2.1.3.2 GNU Extensions for Complex Number Types
'''''''''''''''''''''''''''''''''''''''''''''''

GCC also introduced complex types as a GNU extension to C89, but the
spelling is different. The floating-point complex types in GCC's C89
extension are:

-  ``__complex__ float``
-  ``__complex__ double``
-  ``__complex__ long double``

GCC's extension allow for complex types other than floating-point, so
that you can declare complex character types and complex integer types;
in fact ``__complex__`` can be used with any of the primitive data
types. We won't give you a complete list of all possibilities, but here
are some examples:

-  ``__complex__ float``
    The ``__complex__ float`` data type has two components: a real part
   and an imaginary part, both of which are of the ``float`` data type.
-  ``__complex__ int``
    The ``__complex__ int`` data type also has two components: a real
   part and an imaginary part, both of which are of the ``int`` data
   type.

To extract the real part of a complex-valued expression, use the keyword
``__real__``, followed by the expression. Likewise, use ``__imag__`` to
extract the imaginary part.

::

         __complex__ float a = 4 + 3i;
         
         float b = __real__ a;          /* b is now 4. */
         float c = __imag__ a;          /* c is now 3. */

This example creates a complex floating point variable ``a``, and
defines its real part as 4 and its imaginary part as 3. Then, the real
part is assigned to the floating point variable ``b``, and the imaginary
part is assigned to the floating point variable ``c``.

--------------

Next: `Unions <#Unions>`_, Previous: `Primitive
Types <#Primitive-Types>`_, Up: `Data Types <#Data-Types>`_

2.2 Enumerations
~~~~~~~~~~~~~~~~

An enumeration is a custom data type used for storing constant integer
values and referring to them by names. By default, these values are of
type ``signed int``; however, you can use the ``-fshort-enums`` GCC
compiler option to cause the smallest possible integer type to be used
instead. Both of these behaviors conform to the C89 standard, but mixing
the use of these options within the same program can produce
incompatibilities.

-  `Defining Enumerations <#Defining-Enumerations>`_
-  `Declaring Enumerations <#Declaring-Enumerations>`_

--------------

Next: `Declaring Enumerations <#Declaring-Enumerations>`_, Up:
`Enumerations <#Enumerations>`_

2.2.1 Defining Enumerations
^^^^^^^^^^^^^^^^^^^^^^^^^^^

You define an enumeration using the ``enum`` keyword, followed by the
name of the enumeration (this is optional), followed by a list of
constant names (separated by commas and enclosed in braces), and ending
with a semicolon.

::

         enum fruit {grape, cherry, lemon, kiwi};

That example defines an enumeration, ``fruit``, which contains four
constant integer values, ``grape``, ``cherry``, ``lemon``, and ``kiwi``,
whose values are, by default, 0, 1, 2, and 3, respectively. You can also
specify one or more of the values explicitly:

::

         enum more_fruit {banana = -17, apple, blueberry, mango};

That example defines ``banana`` to be −17, and the remaining values are
incremented by 1: ``apple`` is −16, ``blueberry`` is −15, and ``mango``
is -14. Unless specified otherwise, an enumeration value is equal to one
more than the previous value (and the first value defaults to 0).

You can also refer to an enumeration value defined earlier in the same
enumeration:

::

         enum yet_more_fruit {kumquat, raspberry, peach,
                              plum = peach + 2};

In that example, ``kumquat`` is 0, ``raspberry`` is 1, ``peach`` is 2,
and ``plum`` is 4.

You can't use the same name for an ``enum`` as a ``struct`` or ``union``
in the same scope.

--------------

Previous: `Defining Enumerations <#Defining-Enumerations>`_, Up:
`Enumerations <#Enumerations>`_

2.2.2 Declaring Enumerations
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can declare variables of an enumeration type both when the
enumeration is defined and afterward. This example declares one
variable, named ``my_fruit`` of type ``enum fruit``, all in a single
statement:

::

         enum fruit {banana, apple, blueberry, mango} my_fruit;

while this example declares the type and variable separately:

::

         enum fruit {banana, apple, blueberry, mango};
         enum fruit my_fruit;

(Of course, you couldn't declare it that way if you hadn't named the
enumeration.)

Although such variables are considered to be of an enumeration type, you
can assign them any value that you could assign to an ``int`` variable,
including values from other enumerations. Furthermore, any variable that
can be assigned an ``int`` value can be assigned a value from an
enumeration.

However, you cannot change the values in an enumeration once it has been
defined; they are constant values. For example, this won't work:

::

         enum fruit {banana, apple, blueberry, mango};
         banana = 15;  /* You can't do this! */

Enumerations are useful in conjunction with the ``switch`` statement,
because the compiler can warn you if you have failed to handle one of
the enumeration values. Using the example above, if your code handles
``banana``, ``apple`` and ``mango`` only but not ``blueberry``, GCC can
generate a warning.

--------------

Next: `Structures <#Structures>`_, Previous:
`Enumerations <#Enumerations>`_, Up: `Data Types <#Data-Types>`_

2.3 Unions
~~~~~~~~~~

A union is a custom data type used for storing several variables in the
same memory space. Although you can access any of those variables at any
time, you should only read from one of them at a time—assigning a value
to one of them overwrites the values in the others.

-  `Defining Unions <#Defining-Unions>`_
-  `Declaring Union Variables <#Declaring-Union-Variables>`_
-  `Accessing Union Members <#Accessing-Union-Members>`_
-  `Size of Unions <#Size-of-Unions>`_

--------------

Next: `Declaring Union Variables <#Declaring-Union-Variables>`_, Up:
`Unions <#Unions>`_

2.3.1 Defining Unions
^^^^^^^^^^^^^^^^^^^^^

You define a union using the ``union`` keyword followed by the
declarations of the union's members, enclosed in braces. You declare
each member of a union just as you would normally declare a
variable—using the data type followed by one or more variable names
separated by commas, and ending with a semicolon. Then end the union
definition with a semicolon after the closing brace.

You should also include a name for the union between the ``union``
keyword and the opening brace. This is syntactically optional, but if
you leave it out, you can't refer to that union data type later on
(without a ``typedef``, see `The typedef
Statement <#The-typedef-Statement>`_).

Here is an example of defining a simple union for holding an integer
value and a floating point value:

::

         union numbers
           {
             int i;
             float f;
           };

That defines a union named ``numbers``, which contains two members,
``i`` and ``f``, which are of type ``int`` and ``float``, respectively.

--------------

Next: `Accessing Union Members <#Accessing-Union-Members>`_, Previous:
`Defining Unions <#Defining-Unions>`_, Up: `Unions <#Unions>`_

2.3.2 Declaring Union Variables
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can declare variables of a union type when both you initially define
the union and after the definition, provided you gave the union type a
name.

-  `Declaring Union Variables at
   Definition <#Declaring-Union-Variables-at-Definition>`_
-  `Declaring Union Variables After
   Definition <#Declaring-Union-Variables-After-Definition>`_
-  `Initializing Union Members <#Initializing-Union-Members>`_

--------------

Next: `Declaring Union Variables After
Definition <#Declaring-Union-Variables-After-Definition>`_, Up:
`Declaring Union Variables <#Declaring-Union-Variables>`_

2.3.2.1 Declaring Union Variables at Definition
'''''''''''''''''''''''''''''''''''''''''''''''

You can declare variables of a union type when you define the union type
by putting the variable names after the closing brace of the union
definition, but before the final semicolon. You can declare more than
one such variable by separating the names with commas.

::

         union numbers
           {
             int i;
             float f;
           } first_number, second_number;

That example declares two variables of type ``union numbers``,
``first_number`` and ``second_number``.

--------------

Next: `Initializing Union Members <#Initializing-Union-Members>`_,
Previous: `Declaring Union Variables at
Definition <#Declaring-Union-Variables-at-Definition>`_, Up: `Declaring
Union Variables <#Declaring-Union-Variables>`_

2.3.2.2 Declaring Union Variables After Definition
''''''''''''''''''''''''''''''''''''''''''''''''''

You can declare variables of a union type after you define the union by
using the ``union`` keyword and the name you gave the union type,
followed by one or more variable names separated by commas.

::

         union numbers
           {
             int i;
             float f;
           };
         union numbers first_number, second_number;

That example declares two variables of type ``union numbers``,
``first_number`` and ``second_number``.

--------------

Previous: `Declaring Union Variables After
Definition <#Declaring-Union-Variables-After-Definition>`_, Up:
`Declaring Union Variables <#Declaring-Union-Variables>`_

2.3.2.3 Initializing Union Members
''''''''''''''''''''''''''''''''''

You can initialize the first member of a union variable when you declare
it:

::

         union numbers
           {
             int i;
             float f;
           };
         union numbers first_number = { 5 };

In that example, the ``i`` member of ``first_number`` gets the value 5.
The ``f`` member is left alone.

Another way to initialize a union member is to specify the name of the
member to initialize. This way, you can initialize whichever member you
want to, not just the first one. There are two methods that you can
use—either follow the member name with a colon, and then its value, like
this:

::

         union numbers first_number = { f: 3.14159 };

or precede the member name with a period and assign a value with the
assignment operator, like this:

::

         union numbers first_number = { .f = 3.14159 };

You can also initialize a union member when you declare the union
variable during the definition:

::

         union numbers
           {
             int i;
             float f;
           } first_number = { 5 };

--------------

Next: `Size of Unions <#Size-of-Unions>`_, Previous: `Declaring Union
Variables <#Declaring-Union-Variables>`_, Up: `Unions <#Unions>`_

2.3.3 Accessing Union Members
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can access the members of a union variable using the member access
operator. You put the name of the union variable on the left side of the
operator, and the name of the member on the right side.

::

         union numbers
           {
             int i;
             float f;
           };
         union numbers first_number;
         first_number.i = 5;
         first_number.f = 3.9;

Notice in that example that giving a value to the ``f`` member overrides
the value stored in the ``i`` member.

--------------

Previous: `Accessing Union Members <#Accessing-Union-Members>`_, Up:
`Unions <#Unions>`_

2.3.4 Size of Unions
^^^^^^^^^^^^^^^^^^^^

This size of a union is equal to the size of its largest member.
Consider the first union example from this section:

::

         union numbers
           {
             int i;
             float f;
           };

The size of the union data type is the same as ``sizeof (float)``,
because the ``float`` type is larger than the ``int`` type. Since all of
the members of a union occupy the same memory space, the union data type
size doesn't need to be large enough to hold the sum of all their sizes;
it just needs to be large enough to hold the largest member.

--------------

Next: `Arrays <#Arrays>`_, Previous: `Unions <#Unions>`_, Up: `Data
Types <#Data-Types>`_

2.4 Structures
~~~~~~~~~~~~~~

A structure is a programmer-defined data type made up of variables of
other data types (possibly including other structure types).

-  `Defining Structures <#Defining-Structures>`_
-  `Declaring Structure Variables <#Declaring-Structure-Variables>`_
-  `Accessing Structure Members <#Accessing-Structure-Members>`_
-  `Bit Fields <#Bit-Fields>`_
-  `Size of Structures <#Size-of-Structures>`_

--------------

Next: `Declaring Structure Variables <#Declaring-Structure-Variables>`_,
Up: `Structures <#Structures>`_

2.4.1 Defining Structures
^^^^^^^^^^^^^^^^^^^^^^^^^

You define a structure using the ``struct`` keyword followed by the
declarations of the structure's members, enclosed in braces. You declare
each member of a structure just as you would normally declare a
variable—using the data type followed by one or more variable names
separated by commas, and ending with a semicolon. Then end the structure
definition with a semicolon after the closing brace.

You should also include a name for the structure in between the
``struct`` keyword and the opening brace. This is optional, but if you
leave it out, you can't refer to that structure data type later on
(without a ``typedef``, see `The typedef
Statement <#The-typedef-Statement>`_).

Here is an example of defining a simple structure for holding the X and
Y coordinates of a point:

::

         struct point
           {
             int x, y;
           };

That defines a structure type named ``struct point``, which contains two
members, ``x`` and ``y``, both of which are of type ``int``.

Structures (and unions) may contain instances of other structures and
unions, but of course not themselves. It is possible for a structure or
union type to contain a field which is a pointer to the same type (see
`Incomplete Types <#Incomplete-Types>`_).

--------------

Next: `Accessing Structure Members <#Accessing-Structure-Members>`_,
Previous: `Defining Structures <#Defining-Structures>`_, Up:
`Structures <#Structures>`_

2.4.2 Declaring Structure Variables
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can declare variables of a structure type when both you initially
define the structure and after the definition, provided you gave the
structure type a name.

-  `Declaring Structure Variables at
   Definition <#Declaring-Structure-Variables-at-Definition>`_
-  `Declaring Structure Variables After
   Definition <#Declaring-Structure-Variables-After-Definition>`_
-  `Initializing Structure Members <#Initializing-Structure-Members>`_

--------------

Next: `Declaring Structure Variables After
Definition <#Declaring-Structure-Variables-After-Definition>`_, Up:
`Declaring Structure Variables <#Declaring-Structure-Variables>`_

2.4.2.1 Declaring Structure Variables at Definition
'''''''''''''''''''''''''''''''''''''''''''''''''''

You can declare variables of a structure type when you define the
structure type by putting the variable names after the closing brace of
the structure definition, but before the final semicolon. You can
declare more than one such variable by separating the names with commas.

::

         struct point
           {
             int x, y;
           } first_point, second_point;

That example declares two variables of type ``struct point``,
``first_point`` and ``second_point``.

--------------

Next: `Initializing Structure
Members <#Initializing-Structure-Members>`_, Previous: `Declaring
Structure Variables at
Definition <#Declaring-Structure-Variables-at-Definition>`_, Up:
`Declaring Structure Variables <#Declaring-Structure-Variables>`_

2.4.2.2 Declaring Structure Variables After Definition
''''''''''''''''''''''''''''''''''''''''''''''''''''''

You can declare variables of a structure type after defining the
structure by using the ``struct`` keyword and the name you gave the
structure type, followed by one or more variable names separated by
commas.

::

         struct point
           {
             int x, y;
           };
         struct point first_point, second_point;

That example declares two variables of type ``struct point``,
``first_point`` and ``second_point``.

--------------

Previous: `Declaring Structure Variables After
Definition <#Declaring-Structure-Variables-After-Definition>`_, Up:
`Declaring Structure Variables <#Declaring-Structure-Variables>`_

2.4.2.3 Initializing Structure Members
''''''''''''''''''''''''''''''''''''''

You can initialize the members of a structure type to have certain
values when you declare structure variables.

If you do not initialize a structure variable, the effect depends on
whether it is has static storage (see `Storage Class
Specifiers <#Storage-Class-Specifiers>`_) or not. If it is, members with
integral types are initialized with 0 and pointer members are
initialized to NULL; otherwise, the value of the structure's members is
indeterminate.

One way to initialize a structure is to specify the values in a set of
braces and separated by commas. Those values are assigned to the
structure members in the same order that the members are declared in the
structure in definition.

::

         struct point
           {
             int x, y;
           };
         struct point first_point = { 5, 10 };

In that example, the ``x`` member of ``first_point`` gets the value 5,
and the ``y`` member gets the value 10.

Another way to initialize the members is to specify the name of the
member to initialize. This way, you can initialize the members in any
order you like, and even leave some of them uninitialized. There are two
methods that you can use. The first method is available in C99 and as a
C89 extension in GCC:

::

         struct point first_point = { .y = 10, .x = 5 };

You can also omit the period and use a colon instead of ‘=’, though this
is a GNU C extension:

::

         struct point first_point = { y: 10, x: 5 };

You can also initialize the structure variable's members when you
declare the variable during the structure definition:

::

         struct point
           {
             int x, y;
           } first_point = { 5, 10 };

You can also initialize fewer than all of a structure variable's
members:

::

         struct pointy
           {
             int x, y;
             char *p;
           };
         struct pointy first_pointy = { 5 };

Here, ``x`` is initialized with 5, ``y`` is initialized with 0, and
``p`` is initialized with NULL. The rule here is that ``y`` and ``p``
are initialized just as they would be if they were static variables.

Here is another example that initializes a structure's members which are
structure variables themselves:

::

         struct point
           {
             int x, y;
           };
         
         struct rectangle
           {
             struct point top_left, bottom_right;
           };
         
         struct rectangle my_rectangle = { {0, 5}, {10, 0} };

That example defines the ``rectangle`` structure to consist of two
``point`` structure variables. Then it declares one variable of type
``struct rectangle`` and initializes its members. Since its members are
structure variables, we used an extra set of braces surrounding the
members that belong to the ``point`` structure variables. However, those
extra braces are not necessary; they just make the code easier to read.

--------------

Next: `Bit Fields <#Bit-Fields>`_, Previous: `Declaring Structure
Variables <#Declaring-Structure-Variables>`_, Up:
`Structures <#Structures>`_

2.4.3 Accessing Structure Members
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can access the members of a structure variable using the member
access operator. You put the name of the structure variable on the left
side of the operator, and the name of the member on the right side.

::

         struct point
           {
             int x, y;
           };
         
         struct point first_point;
         
         first_point.x = 0;
         first_point.y = 5;

You can also access the members of a structure variable which is itself
a member of a structure variable.

::

         struct rectangle
           {
             struct point top_left, bottom_right;
           };
         
         struct rectangle my_rectangle;
         
         my_rectangle.top_left.x = 0;
         my_rectangle.top_left.y = 5;
         
         my_rectangle.bottom_right.x = 10;
         my_rectangle.bottom_right.y = 0;

--------------

Next: `Size of Structures <#Size-of-Structures>`_, Previous: `Accessing
Structure Members <#Accessing-Structure-Members>`_, Up:
`Structures <#Structures>`_

2.4.4 Bit Fields
^^^^^^^^^^^^^^^^

You can create structures with integer members of nonstandard sizes,
called *bit fields*. You do this by specifying an integer (``int``,
``char``, ``long int``, etc.) member as usual, and inserting a colon and
the number of bits that the member should occupy in between the member's
name and the semicolon.

::

         struct card
           {
             unsigned int suit : 2;
             unsigned int face_value : 4;
           };

That example defines a structure type with two bit fields, ``suit`` and
``face_value``, which take up 2 bits and 4 bits, respectively. ``suit``
can hold values from 0 to 3, and ``face_value`` can hold values from 0
to 15. Notice that these bit fields were declared as ``unsigned int``;
had they been signed integers, then their ranges would have been from −2
to 1, and from −8 to 7, respectively.

More generally, the range of an unsigned bit field of N bits is from 0
to 2^N - 1, and the range of a signed bit field of N bits is from -(2^N)
/ 2 to ((2^N) / 2) - 1.

Bit fields can be specified without a name in order to control which
actual bits within the containing unit are used. However, the effect of
this is not very portable and it is rarely useful. You can also specify
a bit field of size 0, which indicates that subsequent bit fields not
further bit fields should be packed into the unit containing the
previous bit field. This is likewise not generally useful.

You may not take the address of a bit field with the address operator
``&`` (see `Pointer Operators <#Pointer-Operators>`_).

--------------

Previous: `Bit Fields <#Bit-Fields>`_, Up: `Structures <#Structures>`_

2.4.5 Size of Structures
^^^^^^^^^^^^^^^^^^^^^^^^

The size of a structure type is equal to the sum of the size of all of
its members, possibly including padding to cause the structure type to
align to a particular byte boundary. The details vary depending on your
computer platform, but it would not be atypical to see structures padded
to align on four- or eight-byte boundaries. This is done in order to
speed up memory accesses of instances of the structure type.

As a GNU extension, GCC allows structures with no members. Such
structures have zero size.

If you wish to explicitly omit padding from your structure types (which
may, in turn, decrease the speed of structure memory accesses), then GCC
provides multiple methods of turning packing off. The quick and easy
method is to use the ``-fpack-struct`` compiler option. For more details
on omitting packing, please see the GCC manual which corresponds to your
version of the compiler.

--------------

Next: `Pointers <#Pointers>`_, Previous: `Structures <#Structures>`_,
Up: `Data Types <#Data-Types>`_

2.5 Arrays
~~~~~~~~~~

An array is a data structure that lets you store one or more elements
consecutively in memory. In C, array elements are indexed beginning at
position zero, not one.

-  `Declaring Arrays <#Declaring-Arrays>`_
-  `Initializing Arrays <#Initializing-Arrays>`_
-  `Accessing Array Elements <#Accessing-Array-Elements>`_
-  `Multidimensional Arrays <#Multidimensional-Arrays>`_
-  `Arrays as Strings <#Arrays-as-Strings>`_
-  `Arrays of Unions <#Arrays-of-Unions>`_
-  `Arrays of Structures <#Arrays-of-Structures>`_

--------------

Next: `Initializing Arrays <#Initializing-Arrays>`_, Up:
`Arrays <#Arrays>`_

2.5.1 Declaring Arrays
^^^^^^^^^^^^^^^^^^^^^^

You declare an array by specifying the data type for its elements, its
name, and the number of elements it can store. Here is an example that
declares an array that can store ten integers:

::

         int my_array[10];

For standard C code, the number of elements in an array must be
positive.

As a GNU extension, the number of elements can be as small as zero.
Zero-length arrays are useful as the last element of a structure which
is really a header for a variable-length object:

::

         struct line
         {
           int length;
           char contents[0];
         };
         
         {
           struct line *this_line = (struct line *)
             malloc (sizeof (struct line) + this_length);
           this_line -> length = this_length;
         }

Another GNU extension allows you to declare an array size using
variables, rather than only constants. For example, here is a function
definition that declares an array using its parameter as the number of
elements:

::

         int
         my_function (int number)
         {
           int my_array[number];
           ...;
         }

--------------

Next: `Accessing Array Elements <#Accessing-Array-Elements>`_, Previous:
`Declaring Arrays <#Declaring-Arrays>`_, Up: `Arrays <#Arrays>`_

2.5.2 Initializing Arrays
^^^^^^^^^^^^^^^^^^^^^^^^^

You can initialize the elements in an array when you declare it by
listing the initializing values, separated by commas, in a set of
braces. Here is an example:

::

         int my_array[5] = { 0, 1, 2, 3, 4 };

You don't have to initialize all of the array elements. For example,
this code initializes only the first three elements:

::

         int my_array[5] = { 0, 1, 2 };

Items that are not explicitly initialized will have an indeterminate
value unless the array is of static storage duration. For arrays of
static storage duration, arithmetic types are initialized as zero and
pointers are initialized as NULL.

So, in the example above, if the definition is at file level or is
preceded by ``static``, the final two elements will be 0. Otherwise, the
final two elements will have an indeterminate value.

When using either ISO C99, or C89 with GNU extensions, you can
initialize array elements out of order, by specifying which array
indices to initialize. To do this, include the array index in brackets,
and optionally the assignment operator, before the value. Here is an
example:

::

         int my_array[5] = { [2] 5, [4] 9 };

Or, using the assignment operator:

::

         int my_array[5] = { [2] = 5, [4] = 9 };

Both of those examples are equivalent to:

::

         int my_array[5] = { 0, 0, 5, 0, 9 };

When using GNU extensions, you can initialize a range of elements to the
same value, by specifying the first and last indices, in the form
`` [``first``] ... [``last``] ``. Here is an example:

::

         int new_array[100] = { [0 ... 9] = 1, [10 ... 98] = 2, 3 };

That initializes elements 0 through 9 to 1, elements 10 through 98 to 2,
and element 99 to 3. (You also could explicitly write ``[99] = 3``.)
Also, notice that you *must* have spaces on both sides of the ‘...’.

If you initialize every element of an array, then you do not have to
specify its size; its size is determined by the number of elements you
initialize. Here is an example:

::

         int my_array[] = { 0, 1, 2, 3, 4 };

Although this does not explicitly state that the array has five elements
using ``my_array[5]``, it initializes five elements, so that is how many
it has.

Alternately, if you specify which elements to initialize, then the size
of the array is equal to the highest element number initialized, plus
one. For example:

::

         int my_array[] = { 0, 1, 2, [99] = 99 };

In that example, only four elements are initialized, but the last one
initialized is element number 99, so there are 100 elements.

--------------

Next: `Multidimensional Arrays <#Multidimensional-Arrays>`_, Previous:
`Initializing Arrays <#Initializing-Arrays>`_, Up: `Arrays <#Arrays>`_

2.5.3 Accessing Array Elements
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can access the elements of an array by specifying the array name,
followed by the element index, enclosed in brackets. Remember that the
array elements are numbered starting with zero. Here is an example:

::

         my_array[0] = 5;

That assigns the value 5 to the first element in the array, at position
zero. You can treat individual array elements like variables of whatever
data type the array is made up of. For example, if you have an array
made of a structure data type, you can access the structure elements
like this:

::

         struct point
         {
           int x, y;
         };
         struct point point_array[2] = { {4, 5}, {8, 9} };
         point_array[0].x = 3;

--------------

Next: `Arrays as Strings <#Arrays-as-Strings>`_, Previous: `Accessing
Array Elements <#Accessing-Array-Elements>`_, Up: `Arrays <#Arrays>`_

2.5.4 Multidimensional Arrays
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can make multidimensional arrays, or “arrays of arrays”. You do this
by adding an extra set of brackets and array lengths for every
additional dimension you want your array to have. For example, here is a
declaration for a two-dimensional array that holds five elements in each
dimension (a two-element array consisting of five-element arrays):

::

         int two_dimensions[2][5] { {1, 2, 3, 4, 5}, {6, 7, 8, 9, 10} };

Multidimensional array elements are accessed by specifying the desired
index of both dimensions:

::

         two_dimensions[1][3] = 12;

In our example, ``two_dimensions[0]`` is itself an array. The element
``two_dimensions[0][2]`` is followed by ``two_dimensions[0][3]``, not by
``two_dimensions[1][2]``.

--------------

Next: `Arrays of Unions <#Arrays-of-Unions>`_, Previous:
`Multidimensional Arrays <#Multidimensional-Arrays>`_, Up:
`Arrays <#Arrays>`_

2.5.5 Arrays as Strings
^^^^^^^^^^^^^^^^^^^^^^^

You can use an array of characters to hold a string (see `String
Constants <#String-Constants>`_). The array may be built of either
signed or unsigned characters.

When you declare the array, you can specify the number of elements it
will have. That number will be the maximum number of characters that
should be in the string, including the null character used to end the
string. If you choose this option, then you do not have to initialize
the array when you declare it. Alternately, you can simply initialize
the array to a value, and its size will then be exactly large enough to
hold whatever string you used to initialize it.

There are two different ways to initialize the array. You can specify of
comma-delimited list of characters enclosed in braces, or you can
specify a string literal enclosed in double quotation marks.

Here are some examples:

::

         char blue[26];
         char yellow[26] = {'y', 'e', 'l', 'l', 'o', 'w', '\0'};
         char orange[26] = "orange";
         char gray[] = {'g', 'r', 'a', 'y', '\0'};
         char salmon[] = "salmon";

In each of these cases, the null character ``\0`` is included at the end
of the string, even when not explicitly stated. (Note that if you
initialize a string using an array of individual characters, then the
null character is *not* guaranteed to be present. It might be, but such
an occurrence would be one of chance, and should not be relied upon.)

After initialization, you cannot assign a new string literal to an array
using the assignment operator. For example, this *will not work*:

::

         char lemon[26] = "custard";
         lemon = "steak sauce";      /* Fails! */

However, there are functions in the GNU C library that perform
operations (including copy) on string arrays. You can also change one
character at a time, by accessing individual string elements as you
would any other array:

::

         char name[] = "bob";
         name[0] = 'r';

It is possible for you to explicitly state the number of elements in the
array, and then initialize it using a string that has more characters
than there are elements in the array. This is not a good thing. The
larger string will *not* override the previously specified size of the
array, and you will get a compile-time warning. Since the original array
size remains, any part of the string that exceeds that original size is
being written to a memory location that was not allocated for it.

--------------

Next: `Arrays of Structures <#Arrays-of-Structures>`_, Previous: `Arrays
as Strings <#Arrays-as-Strings>`_, Up: `Arrays <#Arrays>`_

2.5.6 Arrays of Unions
^^^^^^^^^^^^^^^^^^^^^^

You can create an array of a union type just as you can an array of a
primitive data type.

::

         union numbers
           {
             int i;
             float f;
           };
         union numbers number_array [3];

That example creates a 3-element array of ``union numbers`` variables
called ``number_array``. You can also initialize the first members of
the elements of a number array:

::

         struct point point_array [3] = { {3}, {4}, {5} };

The additional inner grouping braces are optional.

After initialization, you can still access the union members in the
array using the member access operator. You put the array name and
element number (enclosed in brackets) to the left of the operator, and
the member name to the right.

::

         union numbers number_array [3];
         number_array[0].i = 2;

--------------

Previous: `Arrays of Unions <#Arrays-of-Unions>`_, Up:
`Arrays <#Arrays>`_

2.5.7 Arrays of Structures
^^^^^^^^^^^^^^^^^^^^^^^^^^

You can create an array of a structure type just as you can an array of
a primitive data type.

::

         struct point
           {
             int x, y;
           };
         struct point point_array [3];

That example creates a 3-element array of ``struct point`` variables
called ``point_array``. You can also initialize the elements of a
structure array:

::

         struct point point_array [3] = { {2, 3}, {4, 5}, {6, 7} };

As with initializing structures which contain structure members, the
additional inner grouping braces are optional. But, if you use the
additional braces, then you can partially initialize some of the
structures in the array, and fully initialize others:

::

         struct point point_array [3] = { {2}, {4, 5}, {6, 7} };

In that example, the first element of the array has only its ``x``
member initialized. Because of the grouping braces, the value 4 is
assigned to the ``x`` member of the second array element, *not* to the
``y`` member of the first element, as would be the case without the
grouping braces.

After initialization, you can still access the structure members in the
array using the member access operator. You put the array name and
element number (enclosed in brackets) to the left of the operator, and
the member name to the right.

::

         struct point point_array [3];
         point_array[0].x = 2;
         point_array[0].y = 3;

--------------

Next: `Incomplete Types <#Incomplete-Types>`_, Previous:
`Arrays <#Arrays>`_, Up: `Data Types <#Data-Types>`_

2.6 Pointers
~~~~~~~~~~~~

Pointers hold memory addresses of stored constants or variables. For any
data type, including both primitive types and custom types, you can
create a pointer that holds the memory address of an instance of that
type.

-  `Declaring Pointers <#Declaring-Pointers>`_
-  `Initializing Pointers <#Initializing-Pointers>`_
-  `Pointers to Unions <#Pointers-to-Unions>`_
-  `Pointers to Structures <#Pointers-to-Structures>`_

--------------

Next: `Initializing Pointers <#Initializing-Pointers>`_, Up:
`Pointers <#Pointers>`_

2.6.1 Declaring Pointers
^^^^^^^^^^^^^^^^^^^^^^^^

You declare a pointer by specifying a name for it and a data type. The
data type indicates of what type of variable the pointer will hold
memory addresses.

To declare a pointer, include the indirection operator (see `Pointer
Operators <#Pointer-Operators>`_) before the identifier. Here is the
general form of a pointer declaration:

::

         data-type * name;

White space is not significant around the indirection operator:

::

         data-type *name;
         data-type* name;

Here is an example of declaring a pointer to hold the address of an
``int`` variable:

::

         int *ip;

Be careful, though: when declaring multiple pointers in the same
statement, you must explicitly declare each as a pointer, using the
indirection operator:

::

         int *foo, *bar;  /* Two pointers. */
         int *baz, quux;   /* A pointer and an integer variable. */

--------------

Next: `Pointers to Unions <#Pointers-to-Unions>`_, Previous: `Declaring
Pointers <#Declaring-Pointers>`_, Up: `Pointers <#Pointers>`_

2.6.2 Initializing Pointers
^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can initialize a pointer when you first declare it by specifying a
variable address to store in it. For example, the following code
declares an ``int`` variable ‘i’, and a pointer which is initialized
with the address of ‘i’:

::

         int i;
         int *ip = &i;

Note the use of the address operator (see `Pointer
Operators <#Pointer-Operators>`_), used to get the memory address of a
variable. After you declare a pointer, you do *not* use the indirection
operator with the pointer's name when assigning it a new address to
point to. On the contrary, that would change the value of the variable
that the points to, not the value of the pointer itself. For example:

::

         int i, j;
         int *ip = &i;  /* ‘ip’ now holds the address of ‘i’. */
         ip = &j;       /* ‘ip’ now holds the address of ‘j’. */
         *ip = &i;      /* ‘j’ now holds the address of ‘i’. */

The value stored in a pointer is an integral number: a location within
the computer's memory space. If you are so inclined, you can assign
pointer values explicitly using literal integers, casting them to the
appropriate pointer type. However, we do not recommend this practice
unless you need to have extremely fine-tuned control over what is stored
in memory, and you know exactly what you are doing. It would be all too
easy to accidentally overwrite something that you did not intend to.
Most uses of this technique are also non-portable.

It is important to note that declaring a pointer variable does not have
the side effect of reserving any storage. If you do not initialize a
pointer with the address of some other existing object, it points
nowhere in particular and will likely make your program crash if you use
it (formally, this kind of thing is called undefined behavior).

--------------

Next: `Pointers to Structures <#Pointers-to-Structures>`_, Previous:
`Initializing Pointers <#Initializing-Pointers>`_, Up:
`Pointers <#Pointers>`_

2.6.3 Pointers to Unions
^^^^^^^^^^^^^^^^^^^^^^^^

You can create a pointer to a union type just as you can a pointer to a
primitive data type.

::

         union numbers
           {
             int i;
             float f;
           };
         union numbers foo = {4};
         union numbers *number_ptr = &foo;

That example creates a new union type, ``union numbers``, and declares
(and initializes the first member of) a variable of that type named
``foo``. Finally, it declares a pointer to the type ``union numbers``,
and gives it the address of ``foo``.

You can access the members of a union variable through a pointer, but
you can't use the regular member access operator anymore. Instead, you
have to use the indirect member access operator (see `Member Access
Expressions <#Member-Access-Expressions>`_). Continuing with the
previous example, the following example will change the value of the
first member of ``foo``:

::

         number_ptr -> i = 450;

Now the ``i`` member in ``foo`` is 450.

--------------

Previous: `Pointers to Unions <#Pointers-to-Unions>`_, Up:
`Pointers <#Pointers>`_

2.6.4 Pointers to Structures
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can create a pointer to a structure type just as you can a pointer
to a primitive data type.

::

         struct fish
           {
             float length, weight;
           };
         struct fish salmon = {4.3, 5.8};
         struct fish *fish_ptr = &salmon;

That example creates a new structure type, ``struct fish``, and declares
(and initializes) a variable of that type named ``salmon``. Finally, it
declares a pointer to the type ``struct fish``, and gives it the address
of ``salmon``.

You can access the members of a structure variable through a pointer,
but you can't use the regular member access operator anymore. Instead,
you have to use the indirect member access operator (see `Member Access
Expressions <#Member-Access-Expressions>`_). Continuing with the
previous example, the following example will change the values of the
members of ``salmon``:

::

         fish_ptr -> length = 5.1;
         fish_ptr -> weight = 6.2;

Now the ``length`` and ``width`` members in ``salmon`` are 5.1 and 6.2,
respectively.

--------------

Next: `Type Qualifiers <#Type-Qualifiers>`_, Previous:
`Pointers <#Pointers>`_, Up: `Data Types <#Data-Types>`_

2.7 Incomplete Types
~~~~~~~~~~~~~~~~~~~~

You can define structures, unions, and enumerations without listing
their members (or values, in the case of enumerations). Doing so results
in an incomplete type. You can't declare variables of incomplete types,
but you can work with pointers to those types.

::

         struct point;

At some time later in your program you will want to complete the type.
You do this by defining it as you usually would:

::

         struct point
           {
             int x, y;
           };

This technique is commonly used to for linked lists:

::

         struct singly_linked_list
           {
             struct singly_linked_list *next;
             int x;
             /* other members here perhaps */
           };
         struct singly_linked_list *list_head;

--------------

Next: `Storage Class Specifiers <#Storage-Class-Specifiers>`_, Previous:
`Incomplete Types <#Incomplete-Types>`_, Up: `Data Types <#Data-Types>`_

2.8 Type Qualifiers
~~~~~~~~~~~~~~~~~~~

There are two type qualifiers that you can prepend to your variable
declarations which change how the variables may be accessed: ``const``
and ``volatile``.

``const`` causes the variable to be read-only; after initialization, its
value may not be changed.

::

         const float pi = 3.14159f;

In addition to helping to prevent accidental value changes, declaring
variables with ``const`` can aid the compiler in code optimization.

``volatile`` tells the compiler that the variable is explicitly
changeable, and seemingly useless accesses of the variable (for
instance, via pointers) should not be optimized away. You might use
``volatile`` variables to store data that is updated via callback
functions or signal handlers. `Sequence Points and Signal
Delivery <#Sequence-Points-and-Signal-Delivery>`_.

::

         volatile float currentTemperature = 40.0;

--------------

Next: `Renaming Types <#Renaming-Types>`_, Previous: `Type
Qualifiers <#Type-Qualifiers>`_, Up: `Data Types <#Data-Types>`_

2.9 Storage Class Specifiers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

There are four storage class specifiers that you can prepend to your
variable declarations which change how the variables are stored in
memory: ``auto``, ``extern``, ``register``, and ``static``.

You use ``auto`` for variables which are local to a function, and whose
values should be discarded upon return from the function in which they
are declared. This is the default behavior for variables declared within
functions.

::

         void
         foo (int value)
         {
           auto int x = value;
           ...
           return;
         }

``register`` is nearly identical in purpose to ``auto``, except that it
also suggests to the compiler that the variable will be heavily used,
and, if possible, should be stored in a register. You cannot use the
address-of operator to obtain the address of a variable declared with
``register``. This means that you cannot refer to the elements of an
array declared with storage class ``register``. In fact the only thing
you can do with such an array is measure its size with ``sizeof``. GCC
normally makes good choices about which values to hold in registers, and
so ``register`` is not often used.

``static`` is essentially the opposite of ``auto``: when applied to
variables within a function or block, these variables will retain their
value even when the function or block is finished. This is known as
static storage duration.

::

         int
         sum (int x)
         {
           static int sumSoFar = 0;
           sumSoFar = sumSoFar + x;
           return sumSoFar;
         }

You can also declare variables (or functions) at the top level (that is,
not inside a function) to be ``static``; such variables are visible
(global) to the current source file (but not other source files). This
gives an unfortunate double meaning to ``static``; this second meaning
is known as static linkage. Two functions or variables having static
linkage in separate files are entirely separate; neither is visible
outside the file in which it is declared.

Uninitialized variables that are declared as ``extern`` are given
default values of ``0``, ``0.0``, or ``NULL``, depending on the type.
Uninitialized variables that are declared as ``auto`` or ``register``
(including the default usage of ``auto``) are left uninitialized, and
hence should not be assumed to hold any particular value.

``extern`` is useful for declaring variables that you want to be visible
to all source files that are linked into your project. You cannot
initialize a variable in an ``extern`` declaration, as no space is
actually allocated during the declaration. You must make both an
``extern`` declaration (typically in a header file that is included by
the other source files which need to access the variable) and a
non-``extern`` declaration which is where space is actually allocated to
store the variable. The ``extern`` declaration may be repeated multiple
times.

::

         extern int numberOfClients;
         
         ...
         
         int numberOfClients = 0;

See `Program Structure and Scope <#Program-Structure-and-Scope>`_, for
related information.

--------------

Previous: `Storage Class Specifiers <#Storage-Class-Specifiers>`_, Up:
`Data Types <#Data-Types>`_

2.10 Renaming Types
~~~~~~~~~~~~~~~~~~~

Sometimes it is convenient to give a new name to a type. You can do this
using the ``typedef`` statement. See `The typedef
Statement <#The-typedef-Statement>`_, for more information.

--------------

Next: `Statements <#Statements>`_, Previous: `Data
Types <#Data-Types>`_, Up: `Top <#Top>`_

3 Expressions and Operators
---------------------------

-  `Expressions <#Expressions>`_
-  `Assignment Operators <#Assignment-Operators>`_
-  `Incrementing and Decrementing <#Incrementing-and-Decrementing>`_
-  `Arithmetic Operators <#Arithmetic-Operators>`_
-  `Complex Conjugation <#Complex-Conjugation>`_
-  `Comparison Operators <#Comparison-Operators>`_
-  `Logical Operators <#Logical-Operators>`_
-  `Bit Shifting <#Bit-Shifting>`_
-  `Bitwise Logical Operators <#Bitwise-Logical-Operators>`_
-  `Pointer Operators <#Pointer-Operators>`_
-  `The sizeof Operator <#The-sizeof-Operator>`_
-  `Type Casts <#Type-Casts>`_
-  `Array Subscripts <#Array-Subscripts>`_
-  `Function Calls as Expressions <#Function-Calls-as-Expressions>`_
-  `The Comma Operator <#The-Comma-Operator>`_
-  `Member Access Expressions <#Member-Access-Expressions>`_
-  `Conditional Expressions <#Conditional-Expressions>`_
-  `Statements and Declarations in
   Expressions <#Statements-and-Declarations-in-Expressions>`_
-  `Operator Precedence <#Operator-Precedence>`_
-  `Order of Evaluation <#Order-of-Evaluation>`_

--------------

Next: `Assignment Operators <#Assignment-Operators>`_, Up: `Expressions
and Operators <#Expressions-and-Operators>`_

3.1 Expressions
~~~~~~~~~~~~~~~

An expression consists of at least one operand and zero or more
operators. Operands typed objects such as constants, variables, and
function calls that return values. Here are some examples:

::

         47
         2 + 2
         cosine(3.14159) /* We presume this returns a floating point value. */

Parentheses group subexpressions:

::

         ( 2 * ( ( 3 + 10 ) - ( 2 * 6 ) ) )

Innermost expressions are evaluated first. In the above example,
``3 + 10`` and ``2 * 6`` evaluate to ``13`` and ``12``, respectively.
Then ``12`` is subtracted from ``13``, resulting in ``1``. Finally,
``1`` is multiplied by ``2``, resulting in ``2``. The outermost
parentheses are completely optional.

An operator specifies an operation to be performed on its operand(s).
Operators may have one, two, or three operands, depending on the
operator.

--------------

Next: `Incrementing and Decrementing <#Incrementing-and-Decrementing>`_,
Previous: `Expressions <#Expressions>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.2 Assignment Operators
~~~~~~~~~~~~~~~~~~~~~~~~

Assignment operators store values in variables. C provides several
variations of assignment operators.

The standard assignment operator ``=`` simply stores the value of its
right operand in the variable specified by its left operand. As with all
assignment operators, the left operand (commonly referred to as the
“lvalue”) cannot be a literal or constant value.

::

         int x = 10;
         float y = 45.12 + 2.0;
         int z = (2 * (3 + function () ));
         
         struct foo {
           int bar;
           int baz;
         } quux = {3, 4, 5};

Note that, unlike the other assignment operators described below, you
can use the plain assignment operator to store values of a structure
type.

Compound assignment operators perform an operation involving both the
left and right operands, and then assign the resulting expression to the
left operand. Here is a list of the compound assignment operators, and a
brief description of what they do:

-  ``+=``
   Adds the two operands together, and then assign the result of the
   addition to the left operand.
-  ``-=``
   Subtract the right operand from the left operand, and then assign the
   result of the subtraction to the left operand.
-  ``*=``
   Multiply the two operands together, and then assign the result of the
   multiplication to the left operand.
-  ``/=``
   Divide the left operand by the right operand, and assign the result
   of the division to the left operand.
-  ``%=``
   Perform modular division on the two operands, and assign the result
   of the division to the left operand.
-  ``<<=``
   Perform a left shift operation on the left operand, shifting by the
   number of bits specified by the right operand, and assign the result
   of the shift to the left operand.
-  ``>>=``
   Perform a right shift operation on the left operand, shifting by the
   number of bits specified by the right operand, and assign the result
   of the shift to the left operand.
-  ``&=``
   Perform a bitwise conjunction operation on the two operands, and
   assign the result of the operation to the left operand.
-  ``^=``
   Performs a bitwise exclusive disjunction operation on the two
   operands, and assign the result of the operation to the left operand.
-  ``|=``
   Performs a bitwise inclusive disjunction operation on the two
   operands, and assign the result of the operation to the left operand.

Here is an example of using one of the compound assignment operators:

::

         x += y;

Since there are no side effects wrought by evaluating the variable ``x``
asn an lvalue, the above code produces the same result as:

::

         x = x + y;

--------------

Next: `Arithmetic Operators <#Arithmetic-Operators>`_, Previous:
`Assignment Operators <#Assignment-Operators>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.3 Incrementing and Decrementing
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The increment operator ``++`` adds 1 to its operand. The operand must be
a either a variable of one of the primitive data types, a pointer, or an
enumeration variable. You can apply the increment operator either before
or after the operand. Here are some examples:

::

         char w = '1';
         int x = 5;
         char y = 'B';
         float z = 5.2;
         int *p = &x;
         
         x++;   /* x is now 6. */
         ++y;   /* y is now `C' (on ASCII systems). */
         ++w;   /* y is now the character `2' (not the value 2). */
         z++;   /* z is now 6.2. */
         ++p;   /* p is now &x + sizeof(int). */

(Note that incrementing a pointer only makes sense if you have reason to
believe that the new pointer value will be a valid memory address.)

A prefix increment adds 1 before the operand is evaluated. A postfix
increment adds 1 after the operand is evaluated. In the previous
examples, changing the position of the operator would make no
difference. However, there are cases where it does make a difference:

::

         int x = 5;
         printf ("%d \n", x++);    /* Print x and then increment it. */
         /* x is now equal to 6. */
         printf ("%d \n", ++x);    /* Increment x and then print it. */

The output of the above example is:

::

         5
         7

Likewise, you can subtract 1 from an operand using the decrement
operator:

::

         int x = 5;
         
         x--; /* x is now 4. */

The concepts of prefix and postfix application apply here as with the
increment operator.

--------------

Next: `Complex Conjugation <#Complex-Conjugation>`_, Previous:
`Incrementing and Decrementing <#Incrementing-and-Decrementing>`_, Up:
`Expressions and Operators <#Expressions-and-Operators>`_

3.4 Arithmetic Operators
~~~~~~~~~~~~~~~~~~~~~~~~

C provides operators for standard arithmetic operations: addition,
subtraction, multiplication, and division, along with modular division
and negation. Usage of these operators is straightforward; here are some
examples:

::

         /* Addition. */
         x = 5 + 3;
         y = 10.23 + 37.332;
         quux_pointer = foo_pointer + bar_pointer;

::

         /* Subtraction. */
         x = 5 - 3;
         y = 57.223 - 10.903;
         quux_pointer = foo_pointer - bar_pointer;

You can add and subtract memory pointers, but you cannot multiply or
divide them.

::

         /* Multiplication. */
         x = 5 * 3;
         y = 47.4 * 1.001;

::

         /* Division. */
         x = 5 / 3;
         y = 940.0 / 20.2;

Integer division of positive values truncates towards zero, so 5/3 is 1.
However, if either operand is negative, the direction of rounding is
implementation-defined. `Signed Integer
Division <#Signed-Integer-Division>`_ for information about overflow in
signed integer division.

You use the modulus operator ``%`` to obtain the remainder produced by
dividing its two operands. You put the operands on either side of the
operator, and it does matter which operand goes on which side: ``3 % 5``
and ``5 % 3`` do not have the same result. The operands must be
expressions of a primitive data type.

::

         /* Modular division. */
         x = 5 % 3;
         y = 74 % 47;

Modular division returns the remainder produced after performing integer
division on the two operands. The operands must be of a primitive
integer type.

::

         /* Negation. */
         int x = -5;
         float y = -3.14159;

If the operand you use with the negative operator is of an unsigned data
type, then the result cannot negative, but rather is the maximum value
of the unsigned data type, minus the value of the operand.

Many systems use twos-complement arithmetic, and on such systems the
most negative value a signed type can hold is further away from zero
than the most positive value. For example, on one platform, this
program:

::

         #include <limits.h>
         #include <stdio.h>
         
         int main (int argc, char *argv[])
         {
           int x;
           x = INT_MAX;
           printf("INT_MAX  = %d\n", x);
           x = INT_MIN;
           printf("INT_MIN  = %d\n", x);
           x = -x;
           printf("-INT_MIN = %d\n", x);
           return 0;
         }

Produces this output:

::

         INT_MAX  = 2147483647
         INT_MIN  = -2147483648
         -INT_MIN = -2147483648

Trivially, you can also apply a positive operator to a numeric
expression:

::

         int x = +42;

Numeric values are assumed to be positive unless explicitly made
negative, so this operator has no effect on program operation.

--------------

Next: `Comparison Operators <#Comparison-Operators>`_, Previous:
`Arithmetic Operators <#Arithmetic-Operators>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.5 Complex Conjugation
~~~~~~~~~~~~~~~~~~~~~~~

As a GNU extension, you can use the complex conjugation operator ``~``
to perform complex conjugation on its operand — that is, it reverses the
sign of its imaginary component. The operand must be an expression of a
complex number type. Here is an example:

::

         __complex__ int x = 5 + 17i;
         
         printf ("%d  \n", (x * ~x));

Since an imaginary number (a + bi) multiplied by its conjugate is equal
to a^2 + b^2, the above ``printf`` statement will print 314, which is
equal to 25 + 289.

--------------

Next: `Logical Operators <#Logical-Operators>`_, Previous: `Complex
Conjugation <#Complex-Conjugation>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.6 Comparison Operators
~~~~~~~~~~~~~~~~~~~~~~~~

You use the comparison operators to determine how two operands relate to
each other: are they equal to each other, is one larger than the other,
is one smaller than the other, and so on. When you use any of the
comparison operators, the result is either 1 or 0, meaning true or
false, respectively.

(In the following code examples, the variables ``x`` and ``y`` stand for
any two expressions of arithmetic types, or pointers.)

The equal-to operator ``==`` tests its two operands for equality. The
result is 1 if the operands are equal, and 0 if the operands are not
equal.

::

         if (x == y)
           puts (``x is equal to y'');
         else
           puts (``x is not equal to y'');

The not-equal-to operator ``!=`` tests its two operands for inequality.
The result is 1 if the operands are not equal, and 0 if the operands
*are* equal.

::

         if (x != y)
           puts (``x is not equal to y'');
         else
           puts (``x is equal to y'');

Comparing floating-point values for exact equality or inequality can
produce unexpected results. `Real Number Types <#Real-Number-Types>`_
for more information.

You can compare function pointers for equality or inequality; the
comparison tests if two function pointers point to the same function or
not.

Beyond equality and inequality, there are operators you can use to test
if one value is less than, greater than, less-than-or-equal-to, or
greater-than-or-equal-to another value. Here are some code samples that
exemplify usage of these operators:

::

         if (x < y)
           puts (``x is less than y'');

::

         if (x <= y)
           puts (``x is less than or equal to y'');

::

         if (x > y)
           puts (``x is greater than y'');

::

         if (x >= y)
           puts (``x is greater than or equal to y'');

--------------

Next: `Bit Shifting <#Bit-Shifting>`_, Previous: `Comparison
Operators <#Comparison-Operators>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.7 Logical Operators
~~~~~~~~~~~~~~~~~~~~~

Logical operators test the truth value of a pair of operands. Any
nonzero expression is considered true in C, while an expression that
evaluates to zero is considered false.

The logical conjunction operator ``&&`` tests if two expressions are
both true. If the first expression is false, then the second expression
is not evaluated.

::

         if ((x == 5) && (y == 10))
           printf (``x is 5 and y is 10'');

The logical conjunction operator ``||`` tests if at least one of two
expressions it true. If the first expression is true, then the second
expression is not evaluated.

::

         if ((x == 5) || (y == 10))
            printf (``x is 5 or y is 10'');

You can prepend a logical expression with a negation operator ``!`` to
flip the truth value:

::

         if (!(x == 5))
           printf (``x is not 5'');

Since the second operand in a logical expression pair is not necessarily
evaluated, you can write code with perhaps unintuitive results:

::

         if (foo && x++)
           bar();

If ``foo`` is ever zero, then not only would ``bar`` not be called, but
``x`` would not be incremented. If you intend to increment ``x``
regardless of the value of ``foo``, you should do so outside of the
conjunction expression.

--------------

Next: `Bitwise Logical Operators <#Bitwise-Logical-Operators>`_,
Previous: `Logical Operators <#Logical-Operators>`_, Up: `Expressions
and Operators <#Expressions-and-Operators>`_

3.8 Bit Shifting
~~~~~~~~~~~~~~~~

You use the left-shift operator ``<<`` to shift its first operand's bits
to the left. The second operand denotes the number of bit places to
shift. Bits shifted off the left side of the value are discarded; new
bits added on the right side will all be 0.

::

         x = 47;    /* 47 is 00101111 in binary. */
         x << 1;    /* 00101111 << 1 is 01011110. */

Similarly, you use the right-shift operator ``>>`` to shift its first
operand's bits to the right. Bits shifted off the right side are
discarded; new bits added on the left side are *usually* 0, but if the
first operand is a signed negative value, then the added bits will be
either 0 *or* whatever value was previously in the leftmost bit
position.

::

         x = 47;   /* 47 is 00101111 in binary. */
         x >> 1;   /* 00101111 >> 1 is 00010111. */

For both ``<<`` and ``>>``, if the second operand is greater than the
bit-width of the first operand, or the second operand is negative, the
behavior is undefined.

You can use the shift operators to perform a variety of interesting
hacks. For example, given a date with the day of the month numbered as
``d``, the month numbered as ``m``, and the year ``y``, you can store
the entire date in a single number ``x``:

::

         int d = 12;
         int m = 6;
         int y = 1983;
         int x = ((y << 4) + m) << 5) +  d;

You can then extract the original day, month, and year out of ``x``
using a combination of shift operators and modular division:

::

         d = x % 32;
         m = (x >> 5) % 16;
         y = x >> 9;

--------------

Next: `Pointer Operators <#Pointer-Operators>`_, Previous: `Bit
Shifting <#Bit-Shifting>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.9 Bitwise Logical Operators
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

C provides operators for performing bitwise conjunction, inclusive
disjunction, exclusive disjunction, and negation (complement).

Biwise conjunction examines each bit in its two operands, and when two
corresponding bits are both 1, the resulting bit is 1. All other
resulting bits are 0. Here is an example of how this works, using binary
numbers:

::

         11001001 & 10011011 = 10001001

Bitwise inclusive disjunction examines each bit in its two operands, and
when two corresponding bits are both 0, the resulting bit is 0. All
other resulting bits are 1.

::

         11001001 | 10011011 = 11011011

Bitwise exclusive disjunction examines each bit in its two operands, and
when two corresponding bits are different, the resulting bit is 1. All
other resulting bits are 0.

::

         11001001 ^ 10011011 = 01010000

Bitwise negation reverses each bit in its operand:

::

         ~11001001 = 00110110

In C, you can only use these operators with operands of an integer (or
character) type, and for maximum portability, you should only use the
bitwise negation operator with unsigned integer types. Here are some
examples of using these operators in C code:

::

         unsigned int foo = 42;
         unsigned int bar = 57;
         unsigned int quux;
         
         quux = foo & bar;
         quux = foo | bar;
         quux = foo ^ bar;
         quux = ~foo;

--------------

Next: `The sizeof Operator <#The-sizeof-Operator>`_, Previous: `Bitwise
Logical Operators <#Bitwise-Logical-Operators>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.10 Pointer Operators
~~~~~~~~~~~~~~~~~~~~~~

You can use the address operator ``&`` to obtain the memory address of
an object.

::

         int x = 5;
         int *pointer_to_x = &x;

It is not necessary to use this operator to obtain the address of a
function, although you can:

::

         extern int foo (void);
         int (*fp1) (void) = foo; /* fp1 points to foo */
         int (*fp2) (void) = &foo; /* fp1 also points to foo */

Function pointers and data pointers are not compatible, in the sense
that you cannot expect to store the address of a function into a data
pointer, and then copy that into a function pointer and call it
successfully. It might work on some systems, but it's not a portable
technique.

As a GNU extension to C89, you can also obtain the address of a label
with the label address operator ``&&``. The result is a ``void*``
pointer which can be used with ``goto``. See `The goto
Statement <#The-goto-Statement>`_.

Given a memory address stored in a pointer, you can use the indirection
operator ``*`` to obtain the value stored at the address. (This is
called dereferencing the pointer.)

::

         int x = 5;
         int y;
         int *ptr;
         
         ptr = &x;    /* ptr now holds the address of x. */
         
         y = *ptr;    /* y gets the value stored at the address
                         stored in ptr. */

Avoid using dereferencing pointers that have not been initialized to a
known memory location.

--------------

Next: `Type Casts <#Type-Casts>`_, Previous: `Pointer
Operators <#Pointer-Operators>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.11 The sizeof Operator
~~~~~~~~~~~~~~~~~~~~~~~~

You can use the ``sizeof`` operator to obtain the size (in bytes) of the
data type of its operand. The operand may be an actual type specifier
(such as ``int`` or ``float``), as well as any valid expression. When
the operand is a type name, it must be enclosed in parentheses. Here are
some examples:

::

         size_t a = sizeof(int);
         size_t b = sizeof(float);
         size_t c = sizeof(5);
         size_t d = sizeof(5.143);
         size_t e = sizeof a;

The result of the ``sizeof`` operator is of a type called ``size_t``,
which is defined in the header file ``<stddef.h>``. ``size_t`` is an
unsigned integer type, perhaps identical to ``unsigned int`` or
``unsigned long int``; it varies from system to system.

The ``size_t`` type is often a convenient type for a loop index, since
it is guaranteed to be able to hold the number of elements in any array;
this is not the case with ``int``, for example.

The ``sizeof`` operator can be used to automatically compute the number
of elements in an array:

::

         #include <stddef.h>
         #include <stdio.h>
         
         static const int values[] = { 1, 2, 48, 681 };
         #define ARRAYSIZE(x) (sizeof x/sizeof x[0])
         
         int main (int argc, char *argv[])
         {
             size_t i;
             for (i = 0; i < ARRAYSIZE(values); i++)
             {
                 printf("%d\n", values[i]);
             }
             return 0;
         }

There are two cases where this technique does not work. The first is
where the array element has zero size (GCC supports zero-sized
structures as a GNU extension). The second is where the array is in fact
a function parameter (see `Function
Parameters <#Function-Parameters>`_).

--------------

Next: `Array Subscripts <#Array-Subscripts>`_, Previous: `The sizeof
Operator <#The-sizeof-Operator>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.12 Type Casts
~~~~~~~~~~~~~~~

You can use a type cast to explicitly cause an expression to be of a
specified data type. A type cast consists of a type specifier enclosed
in parentheses, followed by an expression. To ensure proper casting, you
should also enclose the expression that follows the type specifier in
parentheses. Here is an example:

::

         float x;
         int y = 7;
         int z = 3;
         x = (float) (y / z);

In that example, since ``y`` and ``z`` are both integers, integer
division is performed, and even though ``x`` is a floating-point
variable, it receives the value 2. Explicitly casting the result of the
division to ``float`` does no good, because the computed value of
``y/z`` is already 2.

To fix this problem, you need to convert one of the operands to a
floating-point type before the division takes place:

::

         float x;
         int y = 7;
         int z = 3;
         x = (y / (float)z);

Here, a floating-point value close to 2.333... is assigned to ``x``.

Type casting only works with scalar types (that is, integer,
floating-point or pointer types). Therefore, this is not allowed:

::

         struct fooTag { /* members ... */ };
         struct fooTag foo;
         unsigned char byteArray[8];
         
         foo = (struct fooType) byteArray; /* Fail! */

--------------

Next: `Function Calls as Expressions <#Function-Calls-as-Expressions>`_,
Previous: `Type Casts <#Type-Casts>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.13 Array Subscripts
~~~~~~~~~~~~~~~~~~~~~

You can access array elements by specifying the name of the array, and
the array subscript (or index, or element number) enclosed in brackets.
Here is an example, supposing an integer array called ``my_array``:

::

         my_array[0] = 5;

The array subscript expression ``A[i]`` is defined as being identical to
the expression ``(*((A)+(i)))``. This means that many uses of an array
name are equivalent to a pointer expression. It also means that you
cannot subscript an array having the ``register`` storage class.

--------------

Next: `The Comma Operator <#The-Comma-Operator>`_, Previous: `Array
Subscripts <#Array-Subscripts>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.14 Function Calls as Expressions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

A call to any function which returns a value is an expression.

::

         int function(void);
         ...
         a = 10 + function();

--------------

Next: `Member Access Expressions <#Member-Access-Expressions>`_,
Previous: `Function Calls as
Expressions <#Function-Calls-as-Expressions>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.15 The Comma Operator
~~~~~~~~~~~~~~~~~~~~~~~

You use the comma operator ``,`` to separate two (ostensibly related)
expressions. For instance, the first expression might produce a value
that is used by the second expression:

::

         x++, y = x * x;

More commonly, the comma operator is used in ``for`` statements, like
this:

::

         /* Using the comma operator in a for statement. */
         
         for (x = 1, y = 10;  x <=10 && y >=1;  x++, y--)
           {
             ...
           }

This lets you conveniently set, monitor, and modify multiple control
expressions for the ``for`` statement.

A comma is also used to separate function parameters; however, this is
*not* the comma operator in action. In fact, if the comma operator is
used as we have discussed here in a function call, then the compiler
will interpret that as calling the function with an extra parameter.

If you want to use the comma operator in a function argument, you need
to put parentheses around it. That's because commas in a function
argument list have a different meaning: they separate arguments. Thus,

::

         foo (x,  y=47,  x,  z);

is interpreted as a function call with four arguments, but

::

         foo (x,  (y=47,  x),  z);

is a function call with just three arguments. (The second argument is
``(y=47, x)``.)

--------------

Next: `Conditional Expressions <#Conditional-Expressions>`_, Previous:
`The Comma Operator <#The-Comma-Operator>`_, Up: `Expressions and
Operators <#Expressions-and-Operators>`_

3.16 Member Access Expressions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can use the member access operator ``.`` to access the members of a
structure or union variable. You put the name of the structure variable
on the left side of the operator, and the name of the member on the
right side.

::

         struct point
         {
           int x, y;
         };
         
         struct point first_point;
         
         first_point.x = 0;
         first_point.y = 5;

You can also access the members of a structure or union variable via a
pointer by using the indirect member access operator ``->``. ``x->y`` is
equivalent to ``(*x).y``.

::

         struct fish
           {
             int length, weight;
           };
         
         struct fish salmon;
         
         struct fish *fish_pointer = &salmon;
         
         fish_pointer->length = 3;
         fish_pointer->weight = 9;

See `Pointers <#Pointers>`_.

--------------

Next: `Statements and Declarations in
Expressions <#Statements-and-Declarations-in-Expressions>`_, Previous:
`Member Access Expressions <#Member-Access-Expressions>`_, Up:
`Expressions and Operators <#Expressions-and-Operators>`_

3.17 Conditional Expressions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You use the conditional operator to cause the entire conditional
expression to evaluate to either its second or its third operand, based
on the truth value of its first operand. Here's an example:

::

         a ? b : c

If expression ``a`` is true, then expression ``b`` is evaluated and the
result is the value of ``b``. Otherwise, expression ``c`` is evaluated
and the result is ``c``.

Expressions ``b`` and ``c`` must be compatible. That is, they must both
be

#. arithmetic types
#. compatible ``struct`` or ``union`` types
#. pointers to compatible types (one of which might be the NULL pointer)

Alternatively, one operand is a pointer and the other is a ``void*``
pointer.

Here is an example

::

         a = (x == 5) ? y : z;

Here, if ``x`` equals 5, then ``a`` will receive the value of ``y``.
Otherwise, ``a`` will receive the value of ``z``. This can be considered
a shorthand method for writing a simple ``if``...``else`` statement. The
following example will accomplish the same task as the previous one:

::

         if (x == 5)
             a = y;
         else
             a = z;

If the first operand of the conditional operator is true, then the third
operand is never evaluated. Similarly, if the first operand is false,
then the second operand is never evaluated. The first operand is always
evaluated.

--------------

Next: `Operator Precedence <#Operator-Precedence>`_, Previous:
`Conditional Expressions <#Conditional-Expressions>`_, Up: `Expressions
and Operators <#Expressions-and-Operators>`_

3.18 Statements and Declarations in Expressions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

As a GNU C extension, you can build an expression using compound
statement enclosed in parentheses. This allows you to included loops,
switches, and local variables within an expression.

Recall that a compound statement (also known as a block) is a sequence
of statements surrounded by braces. In this construct, parentheses go
around the braces. Here is an example:

::

         ({ int y = function (); int z;
             if (y > 0) z = y;
            else z = - y;
            z; })

That is a valid (though slightly more complex than necessary) expression
for the absolute value of ``function ()``.

The last thing in the compound statement should be an expression
followed by a semicolon; the value of this subexpression serves as the
value of the entire construct. (If you use some other kind of statement
last within the braces, the construct has type ``void``, and thus
effectively no value.)

This feature is especially useful in making macro definitions “safe” (so
that they evaluate each operand exactly once). For example, the
“maximum” function is commonly defined as a macro in standard C as
follows:

::

         #define max(a,b) ((a) > (b) ? (a) : (b))

But this definition computes either ``a`` or ``b`` twice, with bad
results if the operand has side effects. In GNU C, if you know the type
of the operands (here let's assume ``int``), you can define the macro
safely as follows:

::

         #define maxint(a,b) \
           ({int _a = (a), _b = (b); _a > _b ? _a : _b; })

If you don't know the type of the operand, you can still do this, but
you must use ``typeof`` expressions or type naming.

Embedded statements are not allowed in constant expressions, such as the
value of an enumeration constant, the width of a bit field, or the
initial value of a static variable.

--------------

Next: `Order of Evaluation <#Order-of-Evaluation>`_, Previous:
`Statements and Declarations in
Expressions <#Statements-and-Declarations-in-Expressions>`_, Up:
`Expressions and Operators <#Expressions-and-Operators>`_

3.19 Operator Precedence
~~~~~~~~~~~~~~~~~~~~~~~~

When an expression contains multiple operators, such as ``a + b * f()``,
the operators are grouped based on rules of precedence. For instance,
the meaning of that expression is to call the function ``f`` with no
arguments, multiply the result by ``b``, then add that result to ``a``.
That's what the C rules of operator precedence determine for this
expression.

The following is a list of types of expressions, presented in order of
highest precedence first. Sometimes two or more operators have equal
precedence; all those operators are applied from left to right unless
stated otherwise.

#. Function calls, array subscripting, and membership access operator
   expressions.
#. Unary operators, including logical negation, bitwise complement,
   increment, decrement, unary positive, unary negative, indirection
   operator, address operator, type casting, and ``sizeof`` expressions.
   When several unary operators are consecutive, the later ones are
   nested within the earlier ones: ``!-x`` means ``!(-x)``.
#. Multiplication, division, and modular division expressions.
#. Addition and subtraction expressions.
#. Bitwise shifting expressions.
#. Greater-than, less-than, greater-than-or-equal-to, and
   less-than-or-equal-to
    expressions.
#. Equal-to and not-equal-to expressions.
#. Bitwise AND expressions.
#. Bitwise exclusive OR expressions.
#. Bitwise inclusive OR expressions.
#. Logical AND expressions.
#. Logical OR expressions.
#. Conditional expressions (using ``?:``). When used as subexpressions,
   these are evaluated right to left.
#. All assignment expressions, including compound assignment. When
   multiple assignment statements appear as subexpressions in a single
   larger expression, they are evaluated right to left.
#. Comma operator expressions.

The above list is somewhat dry and is apparently straightforward, but it
does hide some pitfalls. Take this example:

::

         foo = *p++;

Here ``p`` is incremented as a side effect of the expression, but
``foo`` takes the value of ``*(p++)`` rather than ``(*p)++``, since the
unary operators bind right to left. There are other examples of
potential surprises lurking behind the C precedence table. For this
reason if there is the slightest risk of the reader misunderstanding the
meaning of the program, you should use parentheses to make your meaning
clear.

--------------

Previous: `Operator Precedence <#Operator-Precedence>`_, Up:
`Expressions and Operators <#Expressions-and-Operators>`_

3.20 Order of Evaluation
~~~~~~~~~~~~~~~~~~~~~~~~

In C you cannot assume that multiple subexpressions are evaluated in the
order that seems natural. For instance, consider the expression
``++a * f()``. Does this increment ``a`` before or after calling the
function ``f``? The compiler could do it in either order, so you cannot
make assumptions.

This manual explains the semantics of the C language in the abstract.
However, an actual compiler translates source code into specific actions
in an actual computer, and may re-order operations for the sake of
efficiency. The correspondence between the program you write and the
things the computer actually does are specified in terms of *side
effects* and *sequence points*.

-  `Side Effects <#Side-Effects>`_
-  `Sequence Points <#Sequence-Points>`_
-  `Sequence Points Constrain
   Expressions <#Sequence-Points-Constrain-Expressions>`_
-  `Sequence Points and Signal
   Delivery <#Sequence-Points-and-Signal-Delivery>`_

--------------

Next: `Sequence Points <#Sequence-Points>`_, Up: `Order of
Evaluation <#Order-of-Evaluation>`_

3.20.1 Side Effects
^^^^^^^^^^^^^^^^^^^

A side effect is one of the following:

#. accessing a ``volatile`` object
#. modifying an object
#. modifying a file
#. a call to a function which performs any of the above side effects

These are essentially the externally-visible effects of running a
program. They are called side effects because they are effects of
expression evalation beyond the expression's actual resulting value.

The compiler is allowed to perform the operations of your program in an
order different to the order implied by the source of your program,
provided that in the end all the necessary side effects actually take
place. The compiler is also allowed to entirely omit some operations;
for example it's allowed to skip evaluating part of an expression if it
can be certain that the value is not used and evaluating that part of
the expression won't produce any needed side effects.

--------------

Next: `Sequence Points Constrain
Expressions <#Sequence-Points-Constrain-Expressions>`_, Previous: `Side
Effects <#Side-Effects>`_, Up: `Order of
Evaluation <#Order-of-Evaluation>`_

3.20.2 Sequence Points
^^^^^^^^^^^^^^^^^^^^^^

Another requirement on the compiler is that side effects should take
place in the correct order. In order to provide this without
over-constraining the compiler, the C89 and C90 standards specfy a list
of sequence points. A sequence point is one of the following:

#. a call to a function (after argument evaluation is complete)
#. the end of the left-hand operand of the and operator ``&&``
#. the end of the left-hand operand of the or operator ``||``
#. the end of the left-hand operand of the comma operator ``,``
#. the end of the first operand of the ternary operator ``a ? b : c``
#. the end of a full declarator `\ :sup:`2`\  <#fn-2>`_
#. the end of an initialisation expression
#. the end of an expression statement (i.e. an expression followed by
   ``;``)
#. the end of the controlling expression of an ``if`` or ``switch``
   statement
#. the end of the controlling expression of a ``while`` or
   ``do``statement
#. the end of any of the three controlling expressions of a ``for``
   statement
#. the end of the expression in a return statement
#. immediately before the return of a library function
#. after the actions associated with an item of formatted I/O (as used
   for example with the ``strftime`` or the ``printf`` and ``scanf``
   famlies of functions).
#. immediately before and after a call to a comparison function (as
   called for example by ``qsort``)

At a sequence point, all the side effects of previous expression
evaluations must be complete, and no side effects of later evaluations
may have taken place.

This may seem a little hard to grasp, but there is another way to
consider this. Imagine you wrote a library (some of whose functions are
external and perhaps others not) and compiled it, allowing someone else
to call one of your functions from their code. The definitions above
ensure that, at the time they call your function, the data they pass in
has values which are consistent with the behaviour specified by the
abstract machine, and any data returned by your function has a state
which is also consistent with the abstract machine. This includes data
accessible via pointers (i.e. not just function parameters and
identifiers with external linkage).

The above is a slight simplification, since compilers exist that perform
whole-program optimisation at link time. Importantly however, although
they might perform optimisations, the visible side effects of the
program must be the same as if they were produced by the abstract
machine.

--------------

Next: `Sequence Points and Signal
Delivery <#Sequence-Points-and-Signal-Delivery>`_, Previous: `Sequence
Points <#Sequence-Points>`_, Up: `Order of
Evaluation <#Order-of-Evaluation>`_

3.20.3 Sequence Points Constrain Expressions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The code fragment

::

         i = i + 1;

is quite normal and no doubt occurs in many programs. However, the quite
similar code fragment

::

         i = ++i + 1;

is a little harder to understand; what is the final value of ``i``? The
C standards (both C89 and C99) both forbid this construct in conforming
programs.

Between two sequence points,

#. an object may have its stored value modified at most once by the
   evaluation of an expression
#. the prior value of the object shall be read only to determine the
   value to be stored.

The first of these two conditions forbids expressions like
``foo(x=2, ++x)``. The second condition forbids expressions like
``a[i++] = i``.

``int x=0; foo(++x, ++x)``

Not allowed in a conforming program; modifies ``x`` twice before
argument evaluation is complete.

``int x=0; bar((++x,++x))``

Allowed; the function ``bar`` takes one argument (the value 2 is passed
here), and there is a sequence point at the comma operator.

``*p++ || *p++``

Allowed; there is a sequence point at ``||``.

``int x = 1, y = x++;``

Allowed; there is a sequence point after the full declarator of ``x``.

``x=2; x++;``

Allowed; there is a sequence point at the end of the first expression
statement.

``if (x++ > MAX) x = 0;``

Allowed; there is a sequence point at the end of the controlling
expression of the ``if```\ :sup:`3`\  <#fn-3>`_.

``(x=y) ? ++x : x--;``

Allowed; there is a sequence point before the ``?``, and only one of the
two following expressions is evaluated.

``int *p=malloc(sizeof(*p)), *q=p;  *p=foo(); bar((*p)++,(*q)++);``

Not allowed; the object at ``p`` is being modified twice before the
evaluation of the arguments to ``bar`` is complete. The fact that this
is done once via ``p`` and once via ``q`` is irrelevant, since they both
point to the same object.

Let's go back to the example we used to introduce the problem of the
order of evaluation, ``++a * f()``. Suppose the code actually looks like
this:

::

         static int a = 1;
         
         static int f (void)
         {
           a = 100;
           return 3;
         }
         
         int foo (void)
         {
            return ++a * f();
         }

Is this code allowed in a standard-conforming program? Although the
expression in ``foo`` modifies ``a`` twice, this is not a problem. Let's
look at the two possible cases.

The right operand ``f()`` is evaluated first

Since ``f`` returns a value other than void, it must contain a
``return`` statement. Therefore, there is a sequence point at the end of
the return expression. That comes between the modification to ``a`` that
``f`` makes and the evaluation of the left operand.

The left operand ``++a`` is evaluated first

First, ``a`` is incremented. Then the arguments to ``f`` are evaluated
(there are zero of them). Then there is a sequence point before ``f`` is
actually called.

So, we see that our program is standard-conforming. Notice that the
above argument does not actually depend on the details of the body of
the function ``f``. It only depends on the function containing something
ending in a sequence point – in our example this is a return statement,
but an expression statement or a full declarator would do just as well.

However, the result of executing this code depends on the order of
evaluation of the operands of ``*``. If the left-hand operand is
evaluated first, ``foo`` returns 6. Otherwise, it returns 303. The C
standard does not specify in which order the operands should be
evaluated, and also does not require an implementation either to
document the order or even to stick to one order. The effect of this
code is unspecified, meaning that one of several specific things will
happen, but the C standards do not say which.

--------------

Previous: `Sequence Points Constrain
Expressions <#Sequence-Points-Constrain-Expressions>`_, Up: `Order of
Evaluation <#Order-of-Evaluation>`_

3.20.4 Sequence Points and Signal Delivery
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Singals are mainly documented in the GNU C Library manual rather than
this document, even though the C standards consider the compiler and the
C library together to be “the implementation”.

When a signal is received, this will happen between sequence points.
Side effects on ``volatile`` objects prior to the previous sequence
point will have occurred, but other updates may not have occurred yet.
This even applies to straight assignments, such as ``x=0;``, because the
code generated for that statement may require more than one instruction,
meaning that it can be interrupted part-way through by the delivery of a
signal.

The C standard is quite restrictive about what data access can occur
within a signal handler. They can of course use ``auto`` variables, but
in terms of reading or writing other objects, they must be
``volatile sig_atomic_t``. The ``volatile`` type qualifier ensures that
access to the variable in the other parts of the program doesn't span
sequence points and the use of the ``sig_atomic_t`` type ensures that
changes to the variable are atomic with respect to signal delivery.

The POSIX standard also allows a small number of library functions to be
called from a signal handler. These functions are referred to as the set
of async-signal-safe functions. If your program is intended to run on a
POSIX system but not on other systems, you can safely call these from
your signal handler too.

--------------

Next: `Functions <#Functions>`_, Previous: `Expressions and
Operators <#Expressions-and-Operators>`_, Up: `Top <#Top>`_

4 Statements
------------

You write statements to cause actions and to control flow within your
programs. You can also write statements that do not do anything at all,
or do things that are uselessly trivial.

-  `Labels <#Labels>`_
-  `Expression Statements <#Expression-Statements>`_
-  `The if Statement <#The-if-Statement>`_
-  `The switch Statement <#The-switch-Statement>`_
-  `The while Statement <#The-while-Statement>`_
-  `The do Statement <#The-do-Statement>`_
-  `The for Statement <#The-for-Statement>`_
-  `Blocks <#Blocks>`_
-  `The Null Statement <#The-Null-Statement>`_
-  `The goto Statement <#The-goto-Statement>`_
-  `The break Statement <#The-break-Statement>`_
-  `The continue Statement <#The-continue-Statement>`_
-  `The return Statement <#The-return-Statement>`_
-  `The typedef Statement <#The-typedef-Statement>`_

--------------

Next: `Expression Statements <#Expression-Statements>`_, Up:
`Statements <#Statements>`_

4.1 Labels
~~~~~~~~~~

You can use labels to identify a section of source code for use with a
later ``goto`` (see `The goto Statement <#The-goto-Statement>`_). A
label consists of an identifier (such as those used for variable names)
followed by a colon. Here is an example:

::

         treet:

You should be aware that label names do not interfere with other
identifier names:

::

         int treet = 5;    /* treet the variable. */
         treet:            /* treet the label. */

The ISO C standard mandates that a label must be followed by at least
one statement, possibly a null statement (see `The Null
Statement <#The-Null-Statement>`_). GCC will compile code that does not
meet this requirement, but be aware that if you violate it, your code
may have portability issues.

--------------

Next: `The if Statement <#The-if-Statement>`_, Previous:
`Labels <#Labels>`_, Up: `Statements <#Statements>`_

4.2 Expression Statements
~~~~~~~~~~~~~~~~~~~~~~~~~

You can turn any expression into a statement by adding a semicolon to
the end of the expression. Here are some examples:

::

         5;
         2 + 2;
         10 >= 9;

In each of those, all that happens is that each expression is evaluated.
However, they are useless because they do not store a value anywhere,
nor do they actually do anything, other than the evaluation itself. The
compiler is free to ignore such statements.

Expression statements are only useful when they have some kind of side
effect, such as storing a value, calling a function, or (this is
esoteric) causing a fault in the program. Here are some more useful
examples:

::

         x++;
         y = x + 25;
         puts ("Hello, user!");
         *cucumber;

The last of those statements, ``*cucumber;``, could potentially cause a
fault in the program if the value of ``cucumber`` is both not a valid
pointer and has been declared as ``volatile``.

--------------

Next: `The switch Statement <#The-switch-Statement>`_, Previous:
`Expression Statements <#Expression-Statements>`_, Up:
`Statements <#Statements>`_

4.3 The ``if`` Statement
~~~~~~~~~~~~~~~~~~~~~~~~

You can use the ``if`` statement to conditionally execute part of your
program, based on the truth value of a given expression. Here is the
general form of an ``if`` statement:

::

         if (test)
           then-statement
         else
           else-statement

If test evaluates to true, then then-statement is executed and
else-statement is not. If test evaluates to false, then else-statement
is executed and then-statement is not. The ``else`` clause is optional.

Here is an actual example:

::

         if (x == 10)
           puts ("x is 10");

If ``x == 10`` evaluates to true, then the statement
``puts ("x is 10");`` is executed. If ``x == 10`` evaluates to false,
then the statement ``puts ("x is 10");`` is not executed.

Here is an example using ``else``:

::

         if (x == 10)
           puts ("x is 10");
         else
           puts ("x is not 10");

You can use a series of ``if`` statements to test for multiple
conditions:

::

         if (x == 1)
           puts ("x is 1");
         else if (x == 2)
           puts ("x is 2");
         else if (x == 3)
           puts ("x is 3");
         else
           puts ("x is something else");

This function calculates and displays the date of Easter for the given
year ``y``:

::

         void
         easterDate (int y)
         {
           int n = 0;
           int g = (y % 19) + 1;
           int c = (y / 100) + 1;
           int x = ((3 * c) / 4) - 12;
           int z = (((8 * c) + 5) / 25) - 5;
           int d = ((5 * y) / 4) - x - 10;
           int e = ((11 * g) + 20 + z - x) % 30;
         
           if (((e == 25) && (g > 11)) || (e == 24))
             e++;
         
           n = 44 - e;
         
           if (n < 21)
             n += 30;
         
           n = n + 7 - ((d + n) % 7);
         
           if (n > 31)
             printf ("Easter: %d April %d", n - 31, y);
           else
             printf ("Easter: %d March %d", n, y);
         }

--------------

Next: `The while Statement <#The-while-Statement>`_, Previous: `The if
Statement <#The-if-Statement>`_, Up: `Statements <#Statements>`_

4.4 The ``switch`` Statement
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can use the ``switch`` statement to compare one expression with
others, and then execute a series of sub-statements based on the result
of the comparisons. Here is the general form of a ``switch`` statement:

::

         switch (test)
           {
             case compare-1:
               if-equal-statement-1
             case compare-2:
               if-equal-statement-2
             ...
             default:
               default-statement
           }

The ``switch`` statement compares test to each of the compare
expressions, until it finds one that is equal to test. Then, the
statements following the successful case are executed. All of the
expressions compared must be of an integer type, and the compare-N
expressions must be of a constant integer type (e.g., a literal integer
or an expression built of literal integers).

Optionally, you can specify a default case. If test doesn't match any of
the specific cases listed prior to the default case, then the statements
for the default case are executed. Traditionally, the default case is
put after the specific cases, but that isn't required.

::

         switch (x)
           {
             case 0:
               puts ("x is 0");
               break;
             case 1:
               puts ("x is 1");
               break;
             default:
               puts ("x is something else");
               break;
           }

Notice the usage of the ``break`` statement in each of the cases. This
is because, once a matching case is found, not only are its statements
executed, but so are the statements for all following cases:

::

         int x = 0;
         switch (x)
           {
             case 0:
               puts ("x is 0");
             case 1:
               puts ("x is 1");
             default:
               puts ("x is something else");
           }

The output of that example is:

::

         x is 0
         x is 1
         x is something else

This is often not desired. Including a ``break`` statement at the end of
each case redirects program flow to after the ``switch`` statement.

As a GNU C extension, you can also specify a range of consecutive
integer values in a single ``case`` label, like this:

::

         case low ... high:

This has the same effect as the corresponding number of individual
``case`` labels, one for each integer value from low to high, inclusive.

This feature is especially useful for ranges of ASCII character codes:

::

         case 'A' ... 'Z':

Be careful to include spaces around the ``...``; otherwise it may be
parsed incorrectly when you use it with integer values. For example,
write this:

::

         case 1 ... 5:

instead of this:

::

         case 1...5:

It is common to use a ``switch`` statement to handle various possible
values of ``errno``. In this case a portable program should watch out
for the possibility that two macros for ``errno`` values in fact have
the same value, for example ``EWOULDBLOCK`` and ``EAGAIN``.

--------------

Next: `The do Statement <#The-do-Statement>`_, Previous: `The switch
Statement <#The-switch-Statement>`_, Up: `Statements <#Statements>`_

4.5 The ``while`` Statement
~~~~~~~~~~~~~~~~~~~~~~~~~~~

The ``while`` statement is a loop statement with an exit test at the
beginning of the loop. Here is the general form of the ``while``
statement:

::

         while (test)
           statement

The ``while`` statement first evaluates test. If test evaluates to true,
statement is executed, and then test is evaluated again. statement
continues to execute repeatedly as long as test is true after each
execution of statement.

This example prints the integers from zero through nine:

::

         int counter = 0;
         while (counter < 10)
           printf ("%d ", counter++);

A ``break`` statement can also cause a ``while`` loop to exit.

--------------

Next: `The for Statement <#The-for-Statement>`_, Previous: `The while
Statement <#The-while-Statement>`_, Up: `Statements <#Statements>`_

4.6 The ``do`` Statement
~~~~~~~~~~~~~~~~~~~~~~~~

The ``do`` statement is a loop statement with an exit test at the end of
the loop. Here is the general form of the ``do`` statement:

::

         do
           statement
         while (test);

The ``do`` statement first executes statement. After that, it evaluates
test. If test is true, then statement is executed again. statement
continues to execute repeatedly as long as test is true after each
execution of statement.

This example also prints the integers from zero through nine:

::

         int x = 0;
         do
           printf ("%d ", x++);
         while (x < 10);

A ``break`` statement can also cause a ``do`` loop to exit.

--------------

Next: `Blocks <#Blocks>`_, Previous: `The do
Statement <#The-do-Statement>`_, Up: `Statements <#Statements>`_

4.7 The ``for`` Statement
~~~~~~~~~~~~~~~~~~~~~~~~~

The ``for`` statement is a loop statement whose structure allows easy
variable initialization, expression testing, and variable modification.
It is very convenient for making counter-controlled loops. Here is the
general form of the ``for`` statement:

::

         for (initialize; test; step)
           statement

The ``for`` statement first evaluates the expression initialize. Then it
evaluates the expression test. If test is false, then the loop ends and
program control resumes after statement. Otherwise, if test is true,
then statement is executed. Finally, step is evaluated, and the next
iteration of the loop begins with evaluating test again.

Most often, initialize assigns values to one or more variables, which
are generally used as counters, test compares those variables to a
predefined expression, and step modifies those variables' values. Here
is another example that prints the integers from zero through nine:

::

         int x;
         for (x = 0; x < 10; x++)
           printf ("%d ", x);

First, it evaluates initialize, which assigns ``x`` the value 0. Then,
as long as ``x`` is less than 10, the value of ``x`` is printed (in the
body of the loop). Then ``x`` is incremented in the step clause and the
test re-evaluated.

All three of the expressions in a ``for`` statement are optional, and
any combination of the three is valid. Since the first expression is
evaluated only once, it is perhaps the most commonly omitted expression.
You could also write the above example as:

::

         int x = 1;
         for (; x <= 10; x++)
           printf ("%d ", x);

In this example, ``x`` receives its value prior to the beginning of the
``for`` statement.

If you leave out the test expression, then the ``for`` statement is an
infinite loop (unless you put a ``break`` or ``goto`` statement
somewhere in statement). This is like using ``1`` as test; it is never
false.

This ``for`` statement starts printing numbers at 1 and then continues
indefinitely, always printing ``x`` incremented by 1:

::

         for (x = 1; ; x++)
           printf ("%d ", x);

If you leave out the step expression, then no progress is made toward
completing the loop—at least not as is normally expected with a ``for``
statement.

This example prints the number 1 over and over, indefinitely:

::

         for (x = 1; x <= 10;)
           printf ("%d ", x);

Perhaps confusingly, you cannot use the comma operator (see `The Comma
Operator <#The-Comma-Operator>`_) for monitoring and modifying multiple
variables in a ``for`` statement, because as usual the comma operator
discards the result of its left operand. This loop:

::

         int x, y;
         for (x = 1, y = 10; x <= 10, y >= 1; x+=2, y--)
           printf ("%d %d\n", x, y);

Outputs:

::

         1 10
         3 9
         5 8
         7 7
         9 6
         11 5
         13 4
         15 3
         17 2
         19 1

If you need to test two conditions, you will need to use the ``&&``
operator:

::

         int x, y;
         for (x = 1, y = 10; x <= 10 && y >= 1; x+=2, y--)
           printf ("%d %d\n", x, y);

A ``break`` statement can also cause a ``for`` loop to exit.

Here is an example of a function that computes the summation of squares,
given a starting integer to square and an ending integer to square:

::

         int
         sum_of_squares (int start, int end)
         {
           int i, sum = 0;
           for (i = start; i <= end; i++)
             sum += i * i;
           return sum;
         }

--------------

Next: `The Null Statement <#The-Null-Statement>`_, Previous: `The for
Statement <#The-for-Statement>`_, Up: `Statements <#Statements>`_

4.8 Blocks
~~~~~~~~~~

A block is a set of zero or more statements enclosed in braces. Blocks
are also known as compound statements. Often, a block is used as the
body of an ``if`` statement or a loop statement, to group statements
together.

::

         for (x = 1; x <= 10; x++)
           {
             printf ("x is %d\n", x);
         
             if ((x % 2) == 0)
               printf ("%d is even\n", x);
             else
               printf ("%d is odd\n", x);
           }

You can also put blocks inside other blocks:

::

         for (x = 1; x <= 10; x++)
           {
             if ((x % 2) == 0)
               {
                 printf ("x is %d\n", x);
                 printf ("%d is even\n", x);
               }
             else
               {
                 printf ("x is %d\n", x);
                 printf ("%d is odd\n", x);
               }
           }

You can declare variables inside a block; such variables are local to
that block. In C89, declarations must occur before other statements, and
so sometimes it is useful to introduce a block simply for this purpose:

::

         {
           int x = 5;
           printf ("%d\n", x);
         }
         printf ("%d\n", x);   /* Compilation error! x exists only
                                in the preceding block. */

--------------

Next: `The goto Statement <#The-goto-Statement>`_, Previous:
`Blocks <#Blocks>`_, Up: `Statements <#Statements>`_

4.9 The Null Statement
~~~~~~~~~~~~~~~~~~~~~~

The null statement is merely a semicolon alone.

::

         ;

A null statement does not do anything. It does not store a value
anywhere. It does not cause time to pass during the execution of your
program.

Most often, a null statement is used as the body of a loop statement, or
as one or more of the expressions in a ``for`` statement. Here is an
example of a ``for`` statement that uses the null statement as the body
of the loop (and also calculates the integer square root of ``n``, just
for fun):

::

         for (i = 1; i*i < n; i++)
           ;

Here is another example that uses the null statement as the body of a
``for`` loop and also produces output:

::

         for (x = 1; x <= 5; printf ("x is now %d\n", x), x++)
           ;

A null statement is also sometimes used to follow a label that would
otherwise be the last thing in a block.

--------------

Next: `The break Statement <#The-break-Statement>`_, Previous: `The Null
Statement <#The-Null-Statement>`_, Up: `Statements <#Statements>`_

4.10 The ``goto`` Statement
~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can use the ``goto`` statement to unconditionally jump to a
different place in the program. Here is the general form of a ``goto``
statement:

::

         goto label;

You have to specify a label to jump to; when the ``goto`` statement is
executed, program control jumps to that label. See `Labels <#Labels>`_.
Here is an example:

::

         goto end_of_program;
         ...
         end_of_program:

The label can be anywhere in the same function as the ``goto`` statement
that jumps to it, but a ``goto`` statement cannot jump to a label in a
different function.

You *can* use ``goto`` statements to simulate loop statements, but we do
not recommend it—it makes the program harder to read, and GCC cannot
optimize it as well. You should use ``for``, ``while``, and ``do``
statements instead of ``goto`` statements, when possible.

As an extension, GCC allows a goto statement to jump to an address
specified by a ``void*`` variable. To make this work, you also need to
take the address of a label by using the unary operator ``&&`` (not
``&``). Here is a contrived example:

::

         enum Play { ROCK=0, PAPER=1, SCISSORS=2 };
         enum Result { WIN, LOSE, DRAW };
         
         static enum Result turn (void)
         {
           const void * const jumptable[] = {&&rock, &&paper, &&scissors};
           enum Play opp;                /* opponent's play */
           goto *jumptable[select_option (&opp)];
          rock:
           return opp == ROCK ? DRAW : (opp == PAPER ? LOSE : WIN);
          paper:
           return opp == ROCK ? WIN  : (opp == PAPER ? DRAW : LOSE);
          scissors:
           return opp == ROCK ? LOSE : (opp == PAPER ? WIN  : DRAW);
         }

--------------

Next: `The continue Statement <#The-continue-Statement>`_, Previous:
`The goto Statement <#The-goto-Statement>`_, Up:
`Statements <#Statements>`_

4.11 The ``break`` Statement
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can use the ``break`` statement to terminate a ``while``, ``do``,
``for``, or ``switch`` statement. Here is an example:

::

         int x;
         for (x = 1; x <= 10; x++)
           {
             if (x == 8)
               break;
             else
               printf ("%d ", x);
           }

That example prints numbers from 1 to 7. When ``x`` is incremented to 8,
``x == 8`` is true, so the ``break`` statement is executed, terminating
the ``for`` loop prematurely.

If you put a ``break`` statement inside of a loop or ``switch``
statement which itself is inside of a loop or ``switch`` statement, the
``break`` only terminates the innermost loop or ``switch`` statement.

--------------

Next: `The return Statement <#The-return-Statement>`_, Previous: `The
break Statement <#The-break-Statement>`_, Up:
`Statements <#Statements>`_

4.12 The ``continue`` Statement
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can use the ``continue`` statement in loops to terminate an
iteration of the loop and begin the next iteration. Here is an example:

::

         for (x = 0; x < 100; x++)
           {
             if (x % 2 == 0)
               continue;
             else
               sum_of_odd_numbers + = x;
           }

If you put a ``continue`` statement inside a loop which itself is inside
a loop, then it affects only the innermost loop.

--------------

Next: `The typedef Statement <#The-typedef-Statement>`_, Previous: `The
continue Statement <#The-continue-Statement>`_, Up:
`Statements <#Statements>`_

4.13 The ``return`` Statement
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can use the ``return`` statement to end the execution of a function
and return program control to the function that called it. Here is the
general form of the ``return`` statement:

::

         return return-value;

return-value is an optional expression to return. If the function's
return type is ``void``, then it is invalid to return an expression. You
can, however, use the ``return`` statement without a return value.

If the function's return type is not the same as the type of
return-value, and automatic type conversion cannot be performed, then
returning return-value is invalid.

If the function's return type is not ``void`` and no return value is
specified, then the ``return`` statement is valid unless the function is
called in a context that requires a return value. For example:

::

         x = cosine (y);

In that case, the function ``cosine`` was called in a context that
required a return value, so the value could be assigned to ``x``.

Even in contexts where a return value is not required, it is a bad idea
for a non-``void`` function to omit the return value. With GCC, you can
use the command line option ``-Wreturn-type`` to issue a warning if you
omit the return value in such functions.

Here are some examples of using the ``return`` statement, in both a
``void`` and non-``void`` function:

::

         void
         print_plus_five (int x)
         {
           printf ("%d ", x + 5);
           return;
         }

::

         int
         square_value (int x)
         {
           return x * x;
         }

--------------

Previous: `The return Statement <#The-return-Statement>`_, Up:
`Statements <#Statements>`_

4.14 The ``typedef`` Statement
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can use the ``typedef`` statement to create new names for data
types. Here is the general form of the ``typedef`` statement:

::

         typedef old-type-name new-type-name

old-type-name is the existing name for the type, and may consist of more
than one token (e.g., ``unsigned long int``). new-type-name is the
resulting new name for the type, and must be a single identifier.
Creating this new name for the type does not cause the old name to cease
to exist. Here are some examples:

::

         typedef unsigned char byte_type;
         typedef double real_number_type;

In the case of custom data types, you can use ``typedef`` to make a new
name for the type while defining the type:

::

         typedef struct fish
         {
           float weight;
           float length;
           float probability_of_being_caught;
         } fish_type;

To make a type definition of an array, you first provide the type of the
element, and then establish the number of elements at the end of the
type definition:

::

         typedef char array_of_bytes [5];
         array_of_bytes five_bytes = {0, 1, 2, 3, 4};

When selecting names for types, you should avoid ending your type names
with a ``_t`` suffix. The compiler will allow you to do this, but the
POSIX standard reserves use of the ``_t`` suffix for standard library
type names.

--------------

Next: `Program Structure and Scope <#Program-Structure-and-Scope>`_,
Previous: `Statements <#Statements>`_, Up: `Top <#Top>`_

5 Functions
-----------

You can write functions to separate parts of your program into distinct
subprocedures. To write a function, you must at least create a function
definition. It is a good idea also to have an explicit function
declaration; you don't have to, but if you leave it out, then the
default implicit declaration might not match the function itself, and
you will get some compile-time warnings.

Every program requires at least one function, called ``main``. That is
where the program's execution begins.

-  `Function Declarations <#Function-Declarations>`_
-  `Function Definitions <#Function-Definitions>`_
-  `Calling Functions <#Calling-Functions>`_
-  `Function Parameters <#Function-Parameters>`_
-  `Variable Length Parameter Lists <#Variable-Length-Parameter-Lists>`_
-  `Calling Functions Through Function
   Pointers <#Calling-Functions-Through-Function-Pointers>`_
-  `The main Function <#The-main-Function>`_
-  `Recursive Functions <#Recursive-Functions>`_
-  `Static Functions <#Static-Functions>`_
-  `Nested Functions <#Nested-Functions>`_

--------------

Next: `Function Definitions <#Function-Definitions>`_, Up:
`Functions <#Functions>`_

5.1 Function Declarations
~~~~~~~~~~~~~~~~~~~~~~~~~

You write a function declaration to specify the name of a function, a
list of parameters, and the function's return type. A function
declaration ends with a semicolon. Here is the general form:

::

         return-type function-name (parameter-list);

return-type indicates the data type of the value returned by the
function. You can declare a function that doesn't return anything by
using the return type ``void``.

function-name can be any valid identifier (see
`Identifiers <#Identifiers>`_).

parameter-list consists of zero or more parameters, separated by commas.
A typical parameter consists of a data type and an optional name for the
parameter. You can also declare a function that has a variable number of
parameters (see `Variable Length Parameter
Lists <#Variable-Length-Parameter-Lists>`_), or no parameters using
``void``. Leaving out parameter-list entirely also indicates no
parameters, but it is better to specify it explicitly with ``void``.

Here is an example of a function declaration with two parameters:

::

         int foo (int, double);

If you include a name for a parameter, the name immediately follows the
data type, like this:

::

         int foo (int x, double y);

The parameter names can be any identifier (see
`Identifiers <#Identifiers>`_), and if you have more than one parameter,
you can't use the same name more than once within a single declaration.
The parameter names in the declaration need not match the names in the
definition.

You should write the function declaration above the first use of the
function. You can put it in a header file and use the ``#include``
directive to include that function declaration in any source code files
that use the function.

--------------

Next: `Calling Functions <#Calling-Functions>`_, Previous: `Function
Declarations <#Function-Declarations>`_, Up: `Functions <#Functions>`_

5.2 Function Definitions
~~~~~~~~~~~~~~~~~~~~~~~~

You write a function definition to specify what a function actually
does. A function definition consists of information regarding the
function's name, return type, and types and names of parameters, along
with the body of the function. The function body is a series of
statements enclosed in braces; in fact it is simply a block (see
`Blocks <#Blocks>`_).

Here is the general form of a function definition:

::

         return-type
         function-name (parameter-list)
         {
           function-body
         }

return-type and function-name are the same as what you use in the
function declaration (see `Function
Declarations <#Function-Declarations>`_).

parameter-list is the same as the parameter list used in the function
declaration (see `Function Declarations <#Function-Declarations>`_),
except you *must* include names for the parameters in a function
definition.

Here is an simple example of a function definition—it takes two integers
as its parameters and returns the sum of them as its return value:

::

         int
         add_values (int x, int y)
         {
           return x + y;
         }

For compatibility with the original design of C, you can also specify
the type of the function parameters *after* the closing parenthesis of
the parameter list, like this:

::

         int
         add_values (x, y)
             int x, int y;
         {
           return x + y;
         }

However, we strongly discourage this style of coding; it can cause
subtle problems with type casting, among other problems.

--------------

Next: `Function Parameters <#Function-Parameters>`_, Previous: `Function
Definitions <#Function-Definitions>`_, Up: `Functions <#Functions>`_

5.3 Calling Functions
~~~~~~~~~~~~~~~~~~~~~

You can call a function by using its name and supplying any needed
parameters. Here is the general form of a function call:

::

         function-name (parameters)

A function call can make up an entire statement, or it can be used as a
subexpression. Here is an example of a standalone function call:

::

         foo (5);

In that example, the function ‘foo’ is called with the parameter ``5``.

Here is an example of a function call used as a subexpression:

::

         a = square (5);

Supposing that the function ‘square’ squares its parameter, the above
example assigns the value 25 to ``a``.

If a parameter takes more than one argument, you separate parameters
with commas:

::

         a = quux (5, 10);

--------------

Next: `Variable Length Parameter
Lists <#Variable-Length-Parameter-Lists>`_, Previous: `Calling
Functions <#Calling-Functions>`_, Up: `Functions <#Functions>`_

5.4 Function Parameters
~~~~~~~~~~~~~~~~~~~~~~~

Function parameters can be any expression—a literal value, a value
stored in variable, an address in memory, or a more complex expression
built by combining these.

Within the function body, the parameter is a local copy of the value
passed into the function; you cannot change the value passed in by
changing the local copy.

::

         int x = 23;
         foo (x);
         ...
         /* Definition for function foo. */
         int foo (int a)
         {
           a = 2 * a;
           return a;
         }

In that example, even though the parameter ``a`` is modified in the
function ‘foo’, the variable ``x`` that is passed to the function does
not change. If you wish to use the function to change the original value
of ``x``, then you would have to incorporate the function call into an
assignment statement:

::

         x = foo (x);

If the value that you pass to a function is a memory address (that is, a
pointer), then you can access (and change) the data stored at the memory
address. This achieves an effect similar to pass-by-reference in other
languages, but is not the same: the memory address is simply a value,
just like any other value, and cannot itself be changed. The difference
between passing a pointer and passing an integer lies in what you can do
using the value within the function.

Here is an example of calling a function with a pointer parameter:

::

         void
         foo (int *x)
         {
           *x = *x + 42;
         }
         ...
         int a = 15;
         foo (&a);

The formal parameter for the function is of type pointer-to-``int``, and
we call the function by passing it the address of a variable of type
``int``. By dereferencing the pointer within the function body, we can
both see and change the value stored in the address. The above changes
the value of ``a`` to ‘57’.

Even if you don't want to change the value stored in the address,
passing the address of a variable rather than the variable itself can be
useful if the variable type is large and you need to conserve memory
space or limit the performance impact of parameter copying. For example:

::

         struct foo
         {
           int x;
           float y;
           double z;
         };
         
         void bar (const struct foo *a);

In this case, unless you are working on a computer with very large
memory addresses, it will take less memory to pass a pointer to the
structure than to pass an instance of the structure.

One type of parameter that is always passed as a pointer is any sort of
array:

::

         void foo (int a[]);
         ...
         int x[100];
         foo (x);

In this example, calling the function ``foo`` with the parameter ``a``
does not copy the entire array into a new local parameter within
``foo``; rather, it passes ``x`` as a pointer to the first element in
``x``. Be careful, though: within the function, you cannot use
``sizeof`` to determine the size of the array ``x``—``sizeof`` instead
tells you the size of the pointer ``x``. Indeed, the above code is
equivalent to:

::

         void foo (int *a);
         ...
         int x[100];
         foo (x);

Explicitly specifying the length of the array in the parameter
declaration will not help. If you really need to pass an array by value,
you can wrap it in a ``struct``, though doing this will rarely be useful
(passing a ``const``-qualified pointer is normally sufficient to
indicate that the caller should not modify the array).

--------------

Next: `Calling Functions Through Function
Pointers <#Calling-Functions-Through-Function-Pointers>`_, Previous:
`Function Parameters <#Function-Parameters>`_, Up:
`Functions <#Functions>`_

5.5 Variable Length Parameter Lists
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can write a function that takes a variable number of arguments;
these are called variadic functions. To do this, the function needs to
have at least one parameter of a known data type, but the remaining
parameters are optional, and can vary in both quantity and data type.

You list the initial parameters as normal, but then after that, use an
ellipsis: ‘...’. Here is an example function prototype:

::

         int add_multiple_values (int number, ...);

To work with the optional parameters in the function definition, you
need to use macros that are defined in the library header file
‘<stdarg.h>’, so you must ``#include`` that file. For a detailed
description of these macros, see The GNU C Library manual's section on
variadic functions.

Here is an example:

::

         int
         add_multiple_values (int number, ...)
         {
           int counter, total = 0;
         
           /* Declare a variable of type ‘va_list’. */
           va_list parameters;
         
           /* Call the ‘va_start’ function. */
           va_start (parameters, number);
         
           for (counter = 0; counter < number; counter++)
             {
               /* Get the values of the optional parameters. */
               total += va_arg (parameters, int);
             }
         
           /* End use of the ‘parameters’ variable. */
           va_end (parameters);
         
           return total;
         }

To use optional parameters, you need to have a way to know how many
there are. This can vary, so it can't be hard-coded, but if you don't
know how many optional parameters you have, then you could have
difficulty knowing when to stop using the ‘va\_arg’ function. In the
above example, the first parameter to the ‘add\_multiple\_values’
function, ‘number’, is the number of optional parameters actually
passed. So, we might call the function like this:

::

         sum = add_multiple_values (3, 12, 34, 190);

The first parameter indicates how many optional parameters follow it.

Also, note that you don't actually need to use ‘va\_end’ function. In
fact, with GCC it doesn't do anything at all. However, you might want to
include it to maximize compatibility with other compilers.

See `Variadic Functions <libc.html#Variadic-Functions>`_.

--------------

Next: `The main Function <#The-main-Function>`_, Previous: `Variable
Length Parameter Lists <#Variable-Length-Parameter-Lists>`_, Up:
`Functions <#Functions>`_

5.6 Calling Functions Through Function Pointers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can also call a function identified by a pointer. The indirection
operator ``*`` is optional when doing this.

::

         #include <stdio.h>
         
         void foo (int i)
         {
           printf ("foo %d!\n", i);
         }
         
         void bar (int i)
         {
           printf ("%d bar!\n", i);
         }
         
         void message (void (*func)(int), int times)
         {
           int j;
           for (j=0; j<times; ++j)
             func (j);  /* (*func) (j); would be equivalent. */
         }
         
         void example (int want_foo)
         {
           void (*pf)(int) = &bar; /* The & is optional. */
           if (want_foo)
             pf = foo;
           message (pf, 5);
         }

--------------

Next: `Recursive Functions <#Recursive-Functions>`_, Previous: `Calling
Functions Through Function
Pointers <#Calling-Functions-Through-Function-Pointers>`_, Up:
`Functions <#Functions>`_

5.7 The ``main`` Function
~~~~~~~~~~~~~~~~~~~~~~~~~

Every program requires at least one function, called ‘main’. This is
where the program begins executing. You do not need to write a
declaration or prototype for ``main``, but you do need to define it.

The return type for ``main`` is always ``int``. You do not have to
specify the return type for ``main``, but you can. However, you *cannot*
specify that it has a return type other than ``int``.

In general, the return value from ``main`` indicates the program's exit
status. A value of zero or EXIT\_SUCCESS indicates success and
EXIT\_FAILURE indicates an error. Otherwise, the significance of the
value returned is implementation-defined.

Reaching the ``}`` at the end of ``main`` without a return, or executing
a ``return`` statement with no value (that is, ``return;``) are both
equivalent. In C89, the effect of this is undefined, but in C99 the
effect is equivalent to ``return 0;``.

You can write your ``main`` function to have no parameters (that is, as
``int main (void)``, or to accept parameters from the command line. Here
is a very simple ``main`` function with no parameters:

::

         int
         main (void)
         {
           puts ("Hi there!");
           return 0;
         }

To accept command line parameters, you need to have two parameters in
the ``main`` function, ``int argc`` followed by ``char *argv[]``. You
can change the names of those parameters, but they must have those data
types—``int`` and array of pointers to ``char``. ``argc`` is the number
of command line parameters, including the name of the program itself.
``argv`` is an array of the parameters, as character strings.
``argv[0]``, the first element in the array, is the name of the program
as typed at the command line`\ :sup:`4`\  <#fn-4>`_; any following array
elements are the parameters that followed the name of the program.

Here is an example ``main`` function that accepts command line
parameters, and prints out what those parameters are:

::

         int
         main (int argc, char *argv[])
         {
           int counter;
         
           for (counter = 0; counter < argc; counter++)
             printf ("%s\n", argv[counter]);
         
           return 0;
         }

--------------

Next: `Static Functions <#Static-Functions>`_, Previous: `The main
Function <#The-main-Function>`_, Up: `Functions <#Functions>`_

5.8 Recursive Functions
~~~~~~~~~~~~~~~~~~~~~~~

You can write a function that is recursive—a function that calls itself.
Here is an example that computes the factorial of an integer:

::

         int
         factorial (int x)
         {
           if (x < 1)
             return x;
           else
             return (x * factorial (x - 1));
         }

Be careful that you do not write a function that is infinitely
recursive. In the above example, once ``x`` is 1, the recursion stops.
However, in the following example, the recursion does not stop until the
program is interrupted or runs out of memory:

::

         int
         watermelon (int x)
         {
           return (watermelon (x));
         }

Functions can also be indirectly recursive, of course.

--------------

Next: `Nested Functions <#Nested-Functions>`_, Previous: `Recursive
Functions <#Recursive-Functions>`_, Up: `Functions <#Functions>`_

5.9 Static Functions
~~~~~~~~~~~~~~~~~~~~

You can define a function to be static if you want it to be callable
only within the source file where it is defined:

::

         static int
         foo (int x)
         {
           return x + 42;
         }

This is useful if you are building a reusable library of functions and
need to include some subroutines that should not be callable by the end
user.

Functions which are defined in this way are said to have static linkage.
Unfortunately the ``static`` keyword has multiple meanings; `Storage
Class Specifiers <#Storage-Class-Specifiers>`_.

--------------

Previous: `Static Functions <#Static-Functions>`_, Up:
`Functions <#Functions>`_

5.10 Nested Functions
~~~~~~~~~~~~~~~~~~~~~

As a GNU C extension, you can define functions within other functions, a
technique known as nesting functions.

Here is an example of a tail-recursive factorial function, defined using
a nested function:

::

         int
         factorial (int x)
         {
           int
           factorial_helper (int a, int b)
           {
             if (a < 1)
             {
               return b;
             }
             else
             {
               return factorial_helper ((a - 1), (a * b));
             }
           }
         
          return factorial_helper (x, 1);
         }

Note that nested functions must be defined along with variable
declarations at the beginning of a function, and all other statements
follow.

--------------

Next: `A Sample Program <#A-Sample-Program>`_, Previous:
`Functions <#Functions>`_, Up: `Top <#Top>`_

6 Program Structure and Scope
-----------------------------

Now that we have seen all of the fundamental elements of C programs,
it's time to look at the big picture.

-  `Program Structure <#Program-Structure>`_
-  `Scope <#Scope>`_

--------------

Next: `Scope <#Scope>`_, Up: `Program Structure and
Scope <#Program-Structure-and-Scope>`_

6.1 Program Structure
~~~~~~~~~~~~~~~~~~~~~

A C program may exist entirely within a single source file, but more
commonly, any non-trivial program will consist of several custom header
files and source files, and will also include and link with files from
existing libraries.

By convention, header files (with a “.h” extension) contain variable and
function declarations, and source files (with a “.c” extension) contain
the corresponding definitions. Source files may also store declarations,
if these declarations are not for objects which need to be seen by other
files. However, header files almost certainly should not contain any
definitions.

For example, if you write a function that computes square roots, and you
wanted this function to be accessible to files other than where you
define the function, then you would put the function declaration into a
header file (with a “.h” file extension):

::

         /* sqrt.h */
         
         double
         computeSqrt (double x);

This header file could be included by other source files which need to
use your function, but do not need to know how it was implemented.

The implementation of the function would then go into a corresponding
source file (with a “.c” file extension):

::

         /* sqrt.c */
         #include "sqrt.h"
         
         double
         computeSqrt (double x)
         {
           double result;
           ...
           return result;
         }

--------------

Previous: `Program Structure <#Program-Structure>`_, Up: `Program
Structure and Scope <#Program-Structure-and-Scope>`_

6.2 Scope
~~~~~~~~~

Scope refers to what parts of the program can “see” a declared object. A
declared object can be visible only within a particular function, or
within a particular file, or may be visible to an entire set of files by
way of including header files and using ``extern`` declarations.

Unless explicitly stated otherwise, declarations made at the top-level
of a file (i.e., not within a function) are visible to the entire file,
including from within functions, but are not visible outside of the
file.

Declarations made within functions are visible only within those
functions.

A declaration is not visible to declarations that came before it; for
example:

::

         int x = 5;
         int y = x + 10;

will work, but:

::

         int x = y + 10;
         int y = 5;

will not.

See `Storage Class Specifiers <#Storage-Class-Specifiers>`_, for more
information on changing the scope of declared objects. Also see `Static
Functions <#Static-Functions>`_.

--------------

Next: `Overflow <#Overflow>`_, Previous: `Program Structure and
Scope <#Program-Structure-and-Scope>`_, Up: `Top <#Top>`_

7 A Sample Program
------------------

To conclude our description of C, here is a complete program written in
C, consisting of both a C source file and a header file. This program is
an expanded version of the quintessential “hello world” program, and
serves as an example of how to format and structure C code for use in
programs for FSF Project GNU. (You can always download the most recent
version of this program, including sample makefiles and other examples
of how to produce GNU software, from
``http://www.gnu.org/software/hello``.)

This program uses features of the preprocessor; for a description of
preprocessor macros, see The C Preprocessor, available as part of the
GCC documentation.

-  `hello.c <#hello_002ec>`_
-  `system.h <#system_002eh>`_

--------------

Next: `system.h <#system_002eh>`_, Up: `A Sample
Program <#A-Sample-Program>`_

7.1 ``hello.c``
~~~~~~~~~~~~~~~

::

         /* hello.c -- print a greeting message and exit.
         
            Copyright (C) 1992, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002,
            2005, 2006, 2007 Free Software Foundation, Inc.
         
            This program is free software; you can redistribute it and/or modify
            it under the terms of the GNU General Public License as published by
            the Free Software Foundation; either version 3, or (at your option)
            any later version.
         
            This program is distributed in the hope that it will be useful,
            but WITHOUT ANY WARRANTY; without even the implied warranty of
            MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
            GNU General Public License for more details.
         
            You should have received a copy of the GNU General Public License
            along with this program; if not, write to the Free Software Foundation,
            Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.  */
         
         #include <config.h>
         #include "system.h"
         
         /* String containing name the program is called with.  */
         const char *program_name;
         
         static const struct option longopts[] =
         {
           { "greeting", required_argument, NULL, 'g' },
           { "help", no_argument, NULL, 'h' },
           { "next-generation", no_argument, NULL, 'n' },
           { "traditional", no_argument, NULL, 't' },
           { "version", no_argument, NULL, 'v' },
           { NULL, 0, NULL, 0 }
         };
         
         static void print_help (void);
         static void print_version (void);
         
         int
         main (int argc, char *argv[])
         {
           int optc;
           int t = 0, n = 0, lose = 0;
           const char *greeting = NULL;
         
           program_name = argv[0];
         
           /* Set locale via LC_ALL.  */
           setlocale (LC_ALL, "");
         
         #if ENABLE_NLS
           /* Set the text message domain.  */
           bindtextdomain (PACKAGE, LOCALEDIR);
           textdomain (PACKAGE);
         #endif
         
           /* Even exiting has subtleties.  The /dev/full device on GNU/Linux
              can be used for testing whether writes are checked properly.  For
              instance, hello >/dev/full should exit unsuccessfully.  On exit,
              if any writes failed, change the exit status.  This is
              implemented in the Gnulib module "closeout".  */
           atexit (close_stdout);
         
           while ((optc = getopt_long (argc, argv, "g:hntv", longopts, NULL)) != -1)
             switch (optc)
               {
               /* One goal here is having --help and --version exit immediately,
                  per GNU coding standards.  */
               case 'v':
                 print_version ();
                 exit (EXIT_SUCCESS);
                 break;
               case 'g':
                 greeting = optarg;
                 break;
               case 'h':
                 print_help ();
                 exit (EXIT_SUCCESS);
                 break;
               case 'n':
                 n = 1;
                 break;
               case 't':
                 t = 1;
                 break;
               default:
                 lose = 1;
                 break;
               }
         
           if (lose || optind < argc)
             {
               /* Print error message and exit.  */
               if (optind < argc)
                 fprintf (stderr, _("%s: extra operand: %s\n"),
                 program_name, argv[optind]);
               fprintf (stderr, _("Try `%s --help' for more information.\n"),
                        program_name);
               exit (EXIT_FAILURE);
             }
         
           /* Print greeting message and exit. */
           if (t)
             printf (_("hello, world\n"));
         
           else if (n)
             /* TRANSLATORS: Use box drawing characters or other fancy stuff
                if your encoding (e.g., UTF-8) allows it.  If done so add the
                following note, please:
         
                [Note: For best viewing results use a UTF-8 locale, please.]
             */
            printf (_("\
         +---------------+\n\
         | Hello, world! |\n\
         +---------------+\n\
         "));
         
           else
             {
               if (!greeting)
                 greeting = _("Hello, world!");
               puts (greeting);
             }
         
           exit (EXIT_SUCCESS);
         }
         
         
         
         /* Print help info.  This long message is split into
            several pieces to help translators be able to align different
            blocks and identify the various pieces.  */
         
         static void
         print_help (void)
         {
           /* TRANSLATORS: --help output 1 (synopsis)
              no-wrap */
                 printf (_("\
         Usage: %s [OPTION]...\n"), program_name);
         
           /* TRANSLATORS: --help output 2 (brief description)
              no-wrap */
           fputs (_("\
         Print a friendly, customizable greeting.\n"), stdout);
         
           puts ("");
           /* TRANSLATORS: --help output 3: options 1/2
              no-wrap */
           fputs (_("\
           -h, --help          display this help and exit\n\
           -v, --version       display version information and exit\n"), stdout);
         
           puts ("");
           /* TRANSLATORS: --help output 4: options 2/2
              no-wrap */
           fputs (_("\
           -t, --traditional       use traditional greeting format\n\
           -n, --next-generation   use next-generation greeting format\n\
           -g, --greeting=TEXT     use TEXT as the greeting message\n"), stdout);
         
           printf ("\n");
           /* TRANSLATORS: --help output 5 (end)
              TRANSLATORS: the placeholder indicates the bug-reporting address
              for this application.  Please add _another line_ with the
              address for translation bugs.
              no-wrap */
           printf (_("\
         Report bugs to <%s>.\n"), PACKAGE_BUGREPORT);
         }
         
         
         
         /* Print version and copyright information.  */
         
         static void
         print_version (void)
         {
           printf ("hello (GNU %s) %s\n", PACKAGE, VERSION);
           /* xgettext: no-wrap */
           puts ("");
         
           /* It is important to separate the year from the rest of the message,
              as done here, to avoid having to retranslate the message when a new
              year comes around.  */
           printf (_("\
         Copyright (C) %s Free Software Foundation, Inc.\n\
         License GPLv3+: GNU GPL version 3 or later\
         <http://gnu.org/licenses/gpl.html>\n\
         This is free software: you are free to change and redistribute it.\n\
         There is NO WARRANTY, to the extent permitted by law.\n"),
                       "2007");
         }

--------------

Previous: `hello.c <#hello_002ec>`_, Up: `A Sample
Program <#A-Sample-Program>`_

7.2 ``system.h``
~~~~~~~~~~~~~~~~

::

         /* system.h: system-dependent declarations; include this first.
            Copyright (C) 1996, 2005, 2006, 2007 Free Software Foundation, Inc.
         
            This program is free software; you can redistribute it and/or modify
            it under the terms of the GNU General Public License as published by
            the Free Software Foundation; either version 3, or (at your option)
            any later version.
         
            This program is distributed in the hope that it will be useful,
            but WITHOUT ANY WARRANTY; without even the implied warranty of
            MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
            GNU General Public License for more details.
         
            You should have received a copy of the GNU General Public License
            along with this program; if not, write to the Free Software Foundation,
            Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.  */
         
         #ifndef HELLO_SYSTEM_H
         #define HELLO_SYSTEM_H
         
         /* Assume ANSI C89 headers are available.  */
         #include <locale.h>
         #include <stdio.h>
         #include <stdlib.h>
         #include <string.h>
         
         /* Use POSIX headers.  If they are not available, we use the substitute
            provided by gnulib.  */
         #include <getopt.h>
         #include <unistd.h>
         
         /* Internationalization.  */
         #include "gettext.h"
         #define _(str) gettext (str)
         #define N_(str) gettext_noop (str)
         
         /* Check for errors on write.  */
         #include "closeout.h"
         
         #endif /* HELLO_SYSTEM_H */

--------------

Next: `GNU Free Documentation
License <#GNU-Free-Documentation-License>`_, Previous: `A Sample
Program <#A-Sample-Program>`_, Up: `Top <#Top>`_

Appendix A Overflow
-------------------

[This appendix, written principally by Paul Eggert, is from the GNU
Autoconf manual. We thought that it would be helpful to include here.
–TJR]

In practice many portable C programs assume that signed integer overflow
wraps around reliably using two's complement arithmetic. Yet the C
standard says that program behavior is undefined on overflow, and in a
few cases C programs do not work on some modern implementations because
their overflows do not wrap around as their authors expected.
Conversely, in signed integer remainder, the C standard requires
overflow behavior that is commonly not implemented.

-  `Integer Overflow Basics <#Integer-Overflow-Basics>`_: Why integer
   overflow is a problem
-  `Signed Overflow Examples <#Signed-Overflow-Examples>`_: Examples of
   code assuming wraparound
-  `Optimization and Wraparound <#Optimization-and-Wraparound>`_:
   Optimizations that break uses of wraparound
-  `Signed Overflow Advice <#Signed-Overflow-Advice>`_: Practical advice
   for signed overflow issues
-  `Signed Integer Division <#Signed-Integer-Division>`_:
   ``INT_MIN / -1`` and ``INT_MIN % -1``

--------------

Next: `Signed Overflow Examples <#Signed-Overflow-Examples>`_, Up:
`Overflow <#Overflow>`_

A.1 Basics of Integer Overflow
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In languages like C, unsigned integer overflow reliably wraps around;
e.g., ``UINT_MAX + 1`` yields zero. This is guaranteed by the C standard
and is portable in practice, unless you specify aggressive, nonstandard
optimization options suitable only for special applications.

In contrast, the C standard says that signed integer overflow leads to
undefined behavior where a program can do anything, including dumping
core or overrunning a buffer. The misbehavior can even precede the
overflow. Such an overflow can occur during addition, subtraction,
multiplication, division, and left shift.

Despite this requirement of the standard, many C programs assume that
signed integer overflow silently wraps around modulo a power of two,
using two's complement arithmetic, so long as you cast the resulting
value to a signed integer type or store it into a signed integer
variable. If you use conservative optimization flags, such programs are
generally portable to the vast majority of modern platforms, with a few
exceptions discussed later.

For historical reasons the C standard also allows implementations with
ones' complement or signed magnitude arithmetic, but it is safe to
assume two's complement nowadays.

Also, overflow can occur when converting an out-of-range value to a
signed integer type. Here a standard implementation must define what
happens, but this might include raising an exception. In practice all
known implementations support silent wraparound in this case, so you
need not worry about other possibilities.

--------------

Next: `Optimization and Wraparound <#Optimization-and-Wraparound>`_,
Previous: `Integer Overflow Basics <#Integer-Overflow-Basics>`_, Up:
`Overflow <#Overflow>`_

A.2 Examples of Code Assuming Wraparound Overflow
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

There has long been a tension between what the C standard requires for
signed integer overflow, and what C programs commonly assume. The
standard allows aggressive optimizations based on assumptions that
overflow never occurs, but many practical C programs rely on overflow
wrapping around. These programs do not conform to the standard, but they
commonly work in practice because compiler writers are understandably
reluctant to implement optimizations that would break many programs,
unless perhaps a user specifies aggressive optimization.

The C Standard says that if a program has signed integer overflow its
behavior is undefined, and the undefined behavior can even precede the
overflow. To take an extreme example:

::

         if (password == expected_password)
           allow_superuser_privileges ();
         else if (counter++ == INT_MAX)
           abort ();
         else
           printf ("%d password mismatches\n", counter);

If the ``int`` variable ``counter`` equals ``INT_MAX``, ``counter++``
must overflow and the behavior is undefined, so the C standard allows
the compiler to optimize away the test against ``INT_MAX`` and the
``abort`` call. Worse, if an earlier bug in the program lets the
compiler deduce that ``counter == INT_MAX`` or that ``counter``
previously overflowed, the C standard allows the compiler to optimize
away the password test and generate code that allows superuser
privileges unconditionally.

Despite this requirement by the standard, it has long been common for C
code to assume wraparound arithmetic after signed overflow, and all
known practical C implementations support some C idioms that assume
wraparound signed arithmetic, even if the idioms do not conform strictly
to the standard. If your code looks like the following examples it will
almost surely work with real-world compilers.

Here is an example derived from the 7th Edition Unix implementation of
``atoi`` (1979-01-10):

::

         char *p;
         int f, n;
         ...
         while (*p >= '0' && *p <= '9')
           n = n * 10 + *p++ - '0';
         return (f ? -n : n);

Even if the input string is in range, on most modern machines this has
signed overflow when computing the most negative integer (the ``-n``
overflows) or a value near an extreme integer (the first ``+``
overflows).

Here is another example, derived from the 7th Edition implementation of
``rand`` (1979-01-10). Here the programmer expects both multiplication
and addition to wrap on overflow:

::

         static long int randx = 1;
         ...
         randx = randx * 1103515245 + 12345;
         return (randx >> 16) & 077777;

In the following example, derived from the GNU C Library 2.5
implementation of ``mktime`` (2006-09-09), the code assumes wraparound
arithmetic in ``+`` to detect signed overflow:

::

         time_t t, t1, t2;
         int sec_requested, sec_adjustment;
         ...
         t1 = t + sec_requested;
         t2 = t1 + sec_adjustment;
         if (((t1 < t) != (sec_requested < 0))
             | ((t2 < t1) != (sec_adjustment < 0)))
           return -1;

If your code looks like these examples, it is probably safe even though
it does not strictly conform to the C standard. This might lead one to
believe that one can generally assume wraparound on overflow, but that
is not always true, as can be seen in the next section.

--------------

Next: `Signed Overflow Advice <#Signed-Overflow-Advice>`_, Previous:
`Signed Overflow Examples <#Signed-Overflow-Examples>`_, Up:
`Overflow <#Overflow>`_

A.3 Optimizations That Break Wraparound Arithmetic
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Compilers sometimes generate code that is incompatible with wraparound
integer arithmetic. A simple example is an algebraic simplification: a
compiler might translate ``(i * 2000) / 1000`` to ``i * 2`` because it
assumes that ``i * 2000`` does not overflow. The translation is not
equivalent to the original when overflow occurs: e.g., in the typical
case of 32-bit signed two's complement wraparound ``int``, if ``i`` has
type ``int`` and value ``1073742``, the original expression returns
−2147483 but the optimized version returns the mathematically correct
value 2147484.

More subtly, loop induction optimizations often exploit the undefined
behavior of signed overflow. Consider the following contrived function
``sumc``:

::

         int
         sumc (int lo, int hi)
         {
           int sum = 0;
           int i;
           for (i = lo; i <= hi; i++)
             sum ^= i * 53;
           return sum;
         }

To avoid multiplying by 53 each time through the loop, an optimizing
compiler might internally transform ``sumc`` to the equivalent of the
following:

::

         int
         transformed_sumc (int lo, int hi)
         {
           int sum = 0;
           int hic = hi * 53;
           int ic;
           for (ic = lo * 53; ic <= hic; ic += 53)
             sum ^= ic;
           return sum;
         }

This transformation is allowed by the C standard, but it is invalid for
wraparound arithmetic when ``INT_MAX / 53 < hi``, because then the
overflow in computing expressions like ``hi * 53`` can cause the
expression ``i <= hi`` to yield a different value from the transformed
expression ``ic <= hic``.

For this reason, compilers that use loop induction and similar
techniques often do not support reliable wraparound arithmetic when a
loop induction variable like ``ic`` is involved. Since loop induction
variables are generated by the compiler, and are not visible in the
source code, it is not always trivial to say whether the problem affects
your code.

Hardly any code actually depends on wraparound arithmetic in cases like
these, so in practice these loop induction optimizations are almost
always useful. However, edge cases in this area can cause problems. For
example:

::

         int j;
         for (j = 1; 0 < j; j *= 2)
           test (j);

Here, the loop attempts to iterate through all powers of 2 that ``int``
can represent, but the C standard allows a compiler to optimize away the
comparison and generate an infinite loop, under the argument that
behavior is undefined on overflow. As of this writing this optimization
is not done by any production version of GCC with -O2, but it might be
performed by other compilers, or by more aggressive GCC optimization
options, and the GCC developers have not decided whether it will
continue to work with GCC and -O2.

--------------

Next: `Signed Integer Division <#Signed-Integer-Division>`_, Previous:
`Optimization and Wraparound <#Optimization-and-Wraparound>`_, Up:
`Overflow <#Overflow>`_

A.4 Practical Advice for Signed Overflow Issues
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ideally the safest approach is to avoid signed integer overflow
entirely. For example, instead of multiplying two signed integers, you
can convert them to unsigned integers, multiply the unsigned values,
then test whether the result is in signed range.

Rewriting code in this way will be inconvenient, though, particularly if
the signed values might be negative. Also, it may hurt performance.
Using unsigned arithmetic to check for overflow is particularly painful
to do portably and efficiently when dealing with an integer type like
``uid_t`` whose width and signedness vary from platform to platform.

Furthermore, many C applications pervasively assume wraparound behavior
and typically it is not easy to find and remove all these assumptions.
Hence it is often useful to maintain nonstandard code that assumes
wraparound on overflow, instead of rewriting the code. The rest of this
section attempts to give practical advice for this situation.

If your code wants to detect signed integer overflow in ``sum = a + b``,
it is generally safe to use an expression like ``(sum < a) != (b < 0)``.

If your code uses a signed loop index, make sure that the index cannot
overflow, along with all signed expressions derived from the index. Here
is a contrived example of problematic code with two instances of
overflow.

::

         for (i = INT_MAX - 10; i <= INT_MAX; i++)
           if (i + 1 < 0)
             {
               report_overflow ();
               break;
             }

Because of the two overflows, a compiler might optimize away or
transform the two comparisons in a way that is incompatible with the
wraparound assumption.

If your code uses an expression like ``(i * 2000) / 1000`` and you
actually want the multiplication to wrap around on overflow, use
unsigned arithmetic to do it, e.g., ``((int) (i * 2000u)) / 1000``.

If your code assumes wraparound behavior and you want to insulate it
against any GCC optimizations that would fail to support that behavior,
you should use GCC's -fwrapv option, which causes signed overflow to
wrap around reliably (except for division and remainder, as discussed in
the next section).

If you need to port to platforms where signed integer overflow does not
reliably wrap around (e.g., due to hardware overflow checking, or to
highly aggressive optimizations), you should consider debugging with
GCC's -ftrapv option, which causes signed overflow to raise an
exception.

--------------

Previous: `Signed Overflow Advice <#Signed-Overflow-Advice>`_, Up:
`Overflow <#Overflow>`_

A.5 Signed Integer Division and Integer Overflow
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Overflow in signed integer division is not always harmless: for example,
on CPUs of the i386 family, dividing ``INT_MIN`` by ``-1`` yields a
SIGFPE signal which by default terminates the program. Worse, taking the
remainder of these two values typically yields the same signal on these
CPUs, even though the C standard requires ``INT_MIN % -1`` to yield zero
because the expression does not overflow.

--------------

Next: `Index <#Index>`_, Previous: `Overflow <#Overflow>`_, Up:
`Top <#Top>`_

GNU Free Documentation License
------------------------------

Version 1.3, 3 November 2008

::

         Copyright © 2000, 2001, 2002, 2007, 2008 Free Software Foundation, Inc.
         http://fsf.org/
         
         Everyone is permitted to copy and distribute verbatim copies
         of this license document, but changing it is not allowed.

0.  PREAMBLE

    The purpose of this License is to make a manual, textbook, or other
    functional and useful document free in the sense of freedom: to
    assure everyone the effective freedom to copy and redistribute it,
    with or without modifying it, either commercially or
    noncommercially. Secondarily, this License preserves for the author
    and publisher a way to get credit for their work, while not being
    considered responsible for modifications made by others.

    This License is a kind of “copyleft”, which means that derivative
    works of the document must themselves be free in the same sense. It
    complements the GNU General Public License, which is a copyleft
    license designed for free software.

    We have designed this License in order to use it for manuals for
    free software, because free software needs free documentation: a
    free program should come with manuals providing the same freedoms
    that the software does. But this License is not limited to software
    manuals; it can be used for any textual work, regardless of subject
    matter or whether it is published as a printed book. We recommend
    this License principally for works whose purpose is instruction or
    reference.

1.  APPLICABILITY AND DEFINITIONS

    This License applies to any manual or other work, in any medium,
    that contains a notice placed by the copyright holder saying it can
    be distributed under the terms of this License. Such a notice grants
    a world-wide, royalty-free license, unlimited in duration, to use
    that work under the conditions stated herein. The “Document”, below,
    refers to any such manual or work. Any member of the public is a
    licensee, and is addressed as “you”. You accept the license if you
    copy, modify or distribute the work in a way requiring permission
    under copyright law.

    A “Modified Version” of the Document means any work containing the
    Document or a portion of it, either copied verbatim, or with
    modifications and/or translated into another language.

    A “Secondary Section” is a named appendix or a front-matter section
    of the Document that deals exclusively with the relationship of the
    publishers or authors of the Document to the Document's overall
    subject (or to related matters) and contains nothing that could fall
    directly within that overall subject. (Thus, if the Document is in
    part a textbook of mathematics, a Secondary Section may not explain
    any mathematics.) The relationship could be a matter of historical
    connection with the subject or with related matters, or of legal,
    commercial, philosophical, ethical or political position regarding
    them.

    The “Invariant Sections” are certain Secondary Sections whose titles
    are designated, as being those of Invariant Sections, in the notice
    that says that the Document is released under this License. If a
    section does not fit the above definition of Secondary then it is
    not allowed to be designated as Invariant. The Document may contain
    zero Invariant Sections. If the Document does not identify any
    Invariant Sections then there are none.

    The “Cover Texts” are certain short passages of text that are
    listed, as Front-Cover Texts or Back-Cover Texts, in the notice that
    says that the Document is released under this License. A Front-Cover
    Text may be at most 5 words, and a Back-Cover Text may be at most 25
    words.

    A “Transparent” copy of the Document means a machine-readable copy,
    represented in a format whose specification is available to the
    general public, that is suitable for revising the document
    straightforwardly with generic text editors or (for images composed
    of pixels) generic paint programs or (for drawings) some widely
    available drawing editor, and that is suitable for input to text
    formatters or for automatic translation to a variety of formats
    suitable for input to text formatters. A copy made in an otherwise
    Transparent file format whose markup, or absence of markup, has been
    arranged to thwart or discourage subsequent modification by readers
    is not Transparent. An image format is not Transparent if used for
    any substantial amount of text. A copy that is not “Transparent” is
    called “Opaque”.

    Examples of suitable formats for Transparent copies include plain
    ascii without markup, Texinfo input format, LaTeX input format, SGML
    or XML using a publicly available DTD, and standard-conforming
    simple HTML, PostScript or PDF designed for human modification.
    Examples of transparent image formats include PNG, XCF and JPG.
    Opaque formats include proprietary formats that can be read and
    edited only by proprietary word processors, SGML or XML for which
    the DTD and/or processing tools are not generally available, and the
    machine-generated HTML, PostScript or PDF produced by some word
    processors for output purposes only.

    The “Title Page” means, for a printed book, the title page itself,
    plus such following pages as are needed to hold, legibly, the
    material this License requires to appear in the title page. For
    works in formats which do not have any title page as such, “Title
    Page” means the text near the most prominent appearance of the
    work's title, preceding the beginning of the body of the text.

    The “publisher” means any person or entity that distributes copies
    of the Document to the public.

    A section “Entitled XYZ” means a named subunit of the Document whose
    title either is precisely XYZ or contains XYZ in parentheses
    following text that translates XYZ in another language. (Here XYZ
    stands for a specific section name mentioned below, such as
    “Acknowledgements”, “Dedications”, “Endorsements”, or “History”.) To
    “Preserve the Title” of such a section when you modify the Document
    means that it remains a section “Entitled XYZ” according to this
    definition.

    The Document may include Warranty Disclaimers next to the notice
    which states that this License applies to the Document. These
    Warranty Disclaimers are considered to be included by reference in
    this License, but only as regards disclaiming warranties: any other
    implication that these Warranty Disclaimers may have is void and has
    no effect on the meaning of this License.

2.  VERBATIM COPYING

    You may copy and distribute the Document in any medium, either
    commercially or noncommercially, provided that this License, the
    copyright notices, and the license notice saying this License
    applies to the Document are reproduced in all copies, and that you
    add no other conditions whatsoever to those of this License. You may
    not use technical measures to obstruct or control the reading or
    further copying of the copies you make or distribute. However, you
    may accept compensation in exchange for copies. If you distribute a
    large enough number of copies you must also follow the conditions in
    section 3.

    You may also lend copies, under the same conditions stated above,
    and you may publicly display copies.

3.  COPYING IN QUANTITY

    If you publish printed copies (or copies in media that commonly have
    printed covers) of the Document, numbering more than 100, and the
    Document's license notice requires Cover Texts, you must enclose the
    copies in covers that carry, clearly and legibly, all these Cover
    Texts: Front-Cover Texts on the front cover, and Back-Cover Texts on
    the back cover. Both covers must also clearly and legibly identify
    you as the publisher of these copies. The front cover must present
    the full title with all words of the title equally prominent and
    visible. You may add other material on the covers in addition.
    Copying with changes limited to the covers, as long as they preserve
    the title of the Document and satisfy these conditions, can be
    treated as verbatim copying in other respects.

    If the required texts for either cover are too voluminous to fit
    legibly, you should put the first ones listed (as many as fit
    reasonably) on the actual cover, and continue the rest onto adjacent
    pages.

    If you publish or distribute Opaque copies of the Document numbering
    more than 100, you must either include a machine-readable
    Transparent copy along with each Opaque copy, or state in or with
    each Opaque copy a computer-network location from which the general
    network-using public has access to download using public-standard
    network protocols a complete Transparent copy of the Document, free
    of added material. If you use the latter option, you must take
    reasonably prudent steps, when you begin distribution of Opaque
    copies in quantity, to ensure that this Transparent copy will remain
    thus accessible at the stated location until at least one year after
    the last time you distribute an Opaque copy (directly or through
    your agents or retailers) of that edition to the public.

    It is requested, but not required, that you contact the authors of
    the Document well before redistributing any large number of copies,
    to give them a chance to provide you with an updated version of the
    Document.

4.  MODIFICATIONS

    You may copy and distribute a Modified Version of the Document under
    the conditions of sections 2 and 3 above, provided that you release
    the Modified Version under precisely this License, with the Modified
    Version filling the role of the Document, thus licensing
    distribution and modification of the Modified Version to whoever
    possesses a copy of it. In addition, you must do these things in the
    Modified Version:

    #. Use in the Title Page (and on the covers, if any) a title
       distinct from that of the Document, and from those of previous
       versions (which should, if there were any, be listed in the
       History section of the Document). You may use the same title as a
       previous version if the original publisher of that version gives
       permission.
    #. List on the Title Page, as authors, one or more persons or
       entities responsible for authorship of the modifications in the
       Modified Version, together with at least five of the principal
       authors of the Document (all of its principal authors, if it has
       fewer than five), unless they release you from this requirement.
    #. State on the Title page the name of the publisher of the Modified
       Version, as the publisher.
    #. Preserve all the copyright notices of the Document.
    #. Add an appropriate copyright notice for your modifications
       adjacent to the other copyright notices.
    #. Include, immediately after the copyright notices, a license
       notice giving the public permission to use the Modified Version
       under the terms of this License, in the form shown in the
       Addendum below.
    #. Preserve in that license notice the full lists of Invariant
       Sections and required Cover Texts given in the Document's license
       notice.
    #. Include an unaltered copy of this License.
    #. Preserve the section Entitled “History”, Preserve its Title, and
       add to it an item stating at least the title, year, new authors,
       and publisher of the Modified Version as given on the Title Page.
       If there is no section Entitled “History” in the Document, create
       one stating the title, year, authors, and publisher of the
       Document as given on its Title Page, then add an item describing
       the Modified Version as stated in the previous sentence.
    #. Preserve the network location, if any, given in the Document for
       public access to a Transparent copy of the Document, and likewise
       the network locations given in the Document for previous versions
       it was based on. These may be placed in the “History” section.
       You may omit a network location for a work that was published at
       least four years before the Document itself, or if the original
       publisher of the version it refers to gives permission.
    #. For any section Entitled “Acknowledgements” or “Dedications”,
       Preserve the Title of the section, and preserve in the section
       all the substance and tone of each of the contributor
       acknowledgements and/or dedications given therein.
    #. Preserve all the Invariant Sections of the Document, unaltered in
       their text and in their titles. Section numbers or the equivalent
       are not considered part of the section titles.
    #. Delete any section Entitled “Endorsements”. Such a section may
       not be included in the Modified Version.
    #. Do not retitle any existing section to be Entitled “Endorsements”
       or to conflict in title with any Invariant Section.
    #. Preserve any Warranty Disclaimers.

    If the Modified Version includes new front-matter sections or
    appendices that qualify as Secondary Sections and contain no
    material copied from the Document, you may at your option designate
    some or all of these sections as invariant. To do this, add their
    titles to the list of Invariant Sections in the Modified Version's
    license notice. These titles must be distinct from any other section
    titles.

    You may add a section Entitled “Endorsements”, provided it contains
    nothing but endorsements of your Modified Version by various
    parties—for example, statements of peer review or that the text has
    been approved by an organization as the authoritative definition of
    a standard.

    You may add a passage of up to five words as a Front-Cover Text, and
    a passage of up to 25 words as a Back-Cover Text, to the end of the
    list of Cover Texts in the Modified Version. Only one passage of
    Front-Cover Text and one of Back-Cover Text may be added by (or
    through arrangements made by) any one entity. If the Document
    already includes a cover text for the same cover, previously added
    by you or by arrangement made by the same entity you are acting on
    behalf of, you may not add another; but you may replace the old one,
    on explicit permission from the previous publisher that added the
    old one.

    The author(s) and publisher(s) of the Document do not by this
    License give permission to use their names for publicity for or to
    assert or imply endorsement of any Modified Version.

5.  COMBINING DOCUMENTS

    You may combine the Document with other documents released under
    this License, under the terms defined in section 4 above for
    modified versions, provided that you include in the combination all
    of the Invariant Sections of all of the original documents,
    unmodified, and list them all as Invariant Sections of your combined
    work in its license notice, and that you preserve all their Warranty
    Disclaimers.

    The combined work need only contain one copy of this License, and
    multiple identical Invariant Sections may be replaced with a single
    copy. If there are multiple Invariant Sections with the same name
    but different contents, make the title of each such section unique
    by adding at the end of it, in parentheses, the name of the original
    author or publisher of that section if known, or else a unique
    number. Make the same adjustment to the section titles in the list
    of Invariant Sections in the license notice of the combined work.

    In the combination, you must combine any sections Entitled “History”
    in the various original documents, forming one section Entitled
    “History”; likewise combine any sections Entitled
    “Acknowledgements”, and any sections Entitled “Dedications”. You
    must delete all sections Entitled “Endorsements.”

6.  COLLECTIONS OF DOCUMENTS

    You may make a collection consisting of the Document and other
    documents released under this License, and replace the individual
    copies of this License in the various documents with a single copy
    that is included in the collection, provided that you follow the
    rules of this License for verbatim copying of each of the documents
    in all other respects.

    You may extract a single document from such a collection, and
    distribute it individually under this License, provided you insert a
    copy of this License into the extracted document, and follow this
    License in all other respects regarding verbatim copying of that
    document.

7.  AGGREGATION WITH INDEPENDENT WORKS

    A compilation of the Document or its derivatives with other separate
    and independent documents or works, in or on a volume of a storage
    or distribution medium, is called an “aggregate” if the copyright
    resulting from the compilation is not used to limit the legal rights
    of the compilation's users beyond what the individual works permit.
    When the Document is included in an aggregate, this License does not
    apply to the other works in the aggregate which are not themselves
    derivative works of the Document.

    If the Cover Text requirement of section 3 is applicable to these
    copies of the Document, then if the Document is less than one half
    of the entire aggregate, the Document's Cover Texts may be placed on
    covers that bracket the Document within the aggregate, or the
    electronic equivalent of covers if the Document is in electronic
    form. Otherwise they must appear on printed covers that bracket the
    whole aggregate.

8.  TRANSLATION

    Translation is considered a kind of modification, so you may
    distribute translations of the Document under the terms of section
    4. Replacing Invariant Sections with translations requires special
    permission from their copyright holders, but you may include
    translations of some or all Invariant Sections in addition to the
    original versions of these Invariant Sections. You may include a
    translation of this License, and all the license notices in the
    Document, and any Warranty Disclaimers, provided that you also
    include the original English version of this License and the
    original versions of those notices and disclaimers. In case of a
    disagreement between the translation and the original version of
    this License or a notice or disclaimer, the original version will
    prevail.

    If a section in the Document is Entitled “Acknowledgements”,
    “Dedications”, or “History”, the requirement (section 4) to Preserve
    its Title (section 1) will typically require changing the actual
    title.

9.  TERMINATION

    You may not copy, modify, sublicense, or distribute the Document
    except as expressly provided under this License. Any attempt
    otherwise to copy, modify, sublicense, or distribute it is void, and
    will automatically terminate your rights under this License.

    However, if you cease all violation of this License, then your
    license from a particular copyright holder is reinstated (a)
    provisionally, unless and until the copyright holder explicitly and
    finally terminates your license, and (b) permanently, if the
    copyright holder fails to notify you of the violation by some
    reasonable means prior to 60 days after the cessation.

    Moreover, your license from a particular copyright holder is
    reinstated permanently if the copyright holder notifies you of the
    violation by some reasonable means, this is the first time you have
    received notice of violation of this License (for any work) from
    that copyright holder, and you cure the violation prior to 30 days
    after your receipt of the notice.

    Termination of your rights under this section does not terminate the
    licenses of parties who have received copies or rights from you
    under this License. If your rights have been terminated and not
    permanently reinstated, receipt of a copy of some or all of the same
    material does not give you any rights to use it.

10. FUTURE REVISIONS OF THIS LICENSE

    The Free Software Foundation may publish new, revised versions of
    the GNU Free Documentation License from time to time. Such new
    versions will be similar in spirit to the present version, but may
    differ in detail to address new problems or concerns. See
    `http://www.gnu.org/copyleft/ <http://www.gnu.org/copyleft/>`_.

    Each version of the License is given a distinguishing version
    number. If the Document specifies that a particular numbered version
    of this License “or any later version” applies to it, you have the
    option of following the terms and conditions either of that
    specified version or of any later version that has been published
    (not as a draft) by the Free Software Foundation. If the Document
    does not specify a version number of this License, you may choose
    any version ever published (not as a draft) by the Free Software
    Foundation. If the Document specifies that a proxy can decide which
    future versions of this License can be used, that proxy's public
    statement of acceptance of a version permanently authorizes you to
    choose that version for the Document.

11. RELICENSING

    “Massive Multiauthor Collaboration Site” (or “MMC Site”) means any
    World Wide Web server that publishes copyrightable works and also
    provides prominent facilities for anybody to edit those works. A
    public wiki that anybody can edit is an example of such a server. A
    “Massive Multiauthor Collaboration” (or “MMC”) contained in the site
    means any set of copyrightable works thus published on the MMC site.

    “CC-BY-SA” means the Creative Commons Attribution-Share Alike 3.0
    license published by Creative Commons Corporation, a not-for-profit
    corporation with a principal place of business in San Francisco,
    California, as well as future copyleft versions of that license
    published by that same organization.

    “Incorporate” means to publish or republish a Document, in whole or
    in part, as part of another Document.

    An MMC is “eligible for relicensing” if it is licensed under this
    License, and if all works that were first published under this
    License somewhere other than this MMC, and subsequently incorporated
    in whole or in part into the MMC, (1) had no cover texts or
    invariant sections, and (2) were thus incorporated prior to November
    1, 2008.

    The operator of an MMC Site may republish an MMC contained in the
    site under CC-BY-SA on the same site at any time before August 1,
    2009, provided the MMC is eligible for relicensing.

ADDENDUM: How to use this License for your documents
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To use this License in a document you have written, include a copy of
the License in the document and put the following copyright and license
notices just after the title page:

::

           Copyright (C)  year  your name.
           Permission is granted to copy, distribute and/or modify this document
           under the terms of the GNU Free Documentation License, Version 1.3
           or any later version published by the Free Software Foundation;
           with no Invariant Sections, no Front-Cover Texts, and no Back-Cover
           Texts.  A copy of the license is included in the section entitled ``GNU
           Free Documentation License''.

If you have Invariant Sections, Front-Cover Texts and Back-Cover Texts,
replace the “with...Texts.” line with this:

::

             with the Invariant Sections being list their titles, with
             the Front-Cover Texts being list, and with the Back-Cover Texts
             being list.

If you have Invariant Sections without Cover Texts, or some other
combination of the three, merge those two alternatives to suit the
situation.

If your document contains nontrivial examples of program code, we
recommend releasing these examples in parallel under your choice of free
software license, such as the GNU General Public License, to permit
their use in free software.

--------------

Previous: `GNU Free Documentation
License <#GNU-Free-Documentation-License>`_, Up: `Top <#Top>`_

Index
-----

-  `accessing array elements <#index-accessing-array-elements-100>`_:
   `Accessing Array Elements <#Accessing-Array-Elements>`_
-  `accessing structure
   members <#index-accessing-structure-members-87>`_: `Accessing
   Structure Members <#Accessing-Structure-Members>`_
-  `accessing union members <#index-accessing-union-members-70>`_:
   `Accessing Union Members <#Accessing-Union-Members>`_
-  `arithmetic operators <#index-arithmetic-operators-150>`_:
   `Arithmetic Operators <#Arithmetic-Operators>`_
-  `array elements,
   accessing <#index-array-elements_002c-accessing-101>`_: `Accessing
   Array Elements <#Accessing-Array-Elements>`_
-  `array subscripts <#index-array-subscripts-165>`_: `Array
   Subscripts <#Array-Subscripts>`_
-  `arrays <#index-arrays-93>`_: `Arrays <#Arrays>`_
-  `arrays as strings <#index-arrays-as-strings-104>`_: `Arrays as
   Strings <#Arrays-as-Strings>`_
-  `arrays of structures <#index-arrays-of-structures-112>`_: `Arrays of
   Structures <#Arrays-of-Structures>`_
-  `arrays of unions <#index-arrays-of-unions-110>`_: `Arrays of
   Unions <#Arrays-of-Unions>`_
-  `arrays, declaring <#index-arrays_002c-declaring-97>`_: `Declaring
   Arrays <#Declaring-Arrays>`_
-  `arrays, initializing <#index-arrays_002c-initializing-99>`_:
   `Initializing Arrays <#Initializing-Arrays>`_
-  `arrays,
   multidimensional <#index-arrays_002c-multidimensional-103>`_:
   `Multidimensional Arrays <#Multidimensional-Arrays>`_
-  `assignment operators <#index-assignment-operators-144>`_:
   `Assignment Operators <#Assignment-Operators>`_
-  ```auto`` storage class
   specifier <#index-g_t_0040code_007bauto_007d-storage-class-specifier-136>`_:
   `Storage Class Specifiers <#Storage-Class-Specifiers>`_
-  `bit fields <#index-bit-fields-89>`_: `Bit Fields <#Bit-Fields>`_
-  `bit shifting <#index-bit-shifting-157>`_: `Bit
   Shifting <#Bit-Shifting>`_
-  `bitwise logical operators <#index-bitwise-logical-operators-159>`_:
   `Bitwise Logical Operators <#Bitwise-Logical-Operators>`_
-  `blocks <#index-blocks-195>`_: `Blocks <#Blocks>`_
-  ```break``
   statement <#index-g_t_0040code_007bbreak_007d-statement-200>`_: `The
   break Statement <#The-break-Statement>`_
-  `calling functions <#index-calling-functions-209>`_: `Calling
   Functions <#Calling-Functions>`_
-  `casts <#index-casts-164>`_: `Type Casts <#Type-Casts>`_
-  ```char`` data
   type <#index-g_t_0040code_007bchar_007d-data-type-29>`_: `Integer
   Types <#Integer-Types>`_
-  `character constants <#index-character-constants-8>`_: `Character
   Constants <#Character-Constants>`_
-  `comma operator <#index-comma-operator-167>`_: `The Comma
   Operator <#The-Comma-Operator>`_
-  `comparison operators <#index-comparison-operators-154>`_:
   `Comparison Operators <#Comparison-Operators>`_
-  `complex conjugation <#index-complex-conjugation-152>`_: `Complex
   Conjugation <#Complex-Conjugation>`_
-  `complex number types <#index-complex-number-types-47>`_: `Complex
   Number Types <#Complex-Number-Types>`_
-  `compound statements <#index-compound-statements-196>`_:
   `Blocks <#Blocks>`_
-  `conditional expressions <#index-conditional-expressions-170>`_:
   `Conditional Expressions <#Conditional-Expressions>`_
-  `conjugation <#index-conjugation-153>`_: `Complex
   Conjugation <#Complex-Conjugation>`_
-  ```const`` type
   qualifier <#index-g_t_0040code_007bconst_007d-type-qualifier-132>`_:
   `Type Qualifiers <#Type-Qualifiers>`_
-  `constants <#index-constants-5>`_: `Constants <#Constants>`_
-  `constants, character <#index-constants_002c-character-9>`_:
   `Character Constants <#Character-Constants>`_
-  `constants, floating
   point <#index-constants_002c-floating-point-11>`_: `Real Number
   Constants <#Real-Number-Constants>`_
-  `constants, integer <#index-constants_002c-integer-7>`_: `Integer
   Constants <#Integer-Constants>`_
-  `constants, real number <#index-constants_002c-real-number-13>`_:
   `Real Number Constants <#Real-Number-Constants>`_
-  ```continue``
   statement <#index-g_t_0040code_007bcontinue_007d-statement-201>`_:
   `The continue Statement <#The-continue-Statement>`_
-  `data types <#index-data-types-19>`_: `Data Types <#Data-Types>`_
-  `data types, array <#index-data-types_002c-array-95>`_:
   `Arrays <#Arrays>`_
-  `data types, complex
   number <#index-data-types_002c-complex-number-48>`_: `Complex Number
   Types <#Complex-Number-Types>`_
-  `data types, enumeration <#index-data-types_002c-enumeration-52>`_:
   `Enumerations <#Enumerations>`_
-  `data types, floating
   point <#index-data-types_002c-floating-point-41>`_: `Real Number
   Types <#Real-Number-Types>`_
-  `data types, integer <#index-data-types_002c-integer-25>`_: `Integer
   Types <#Integer-Types>`_
-  `data types, pointer <#index-data-types_002c-pointer-116>`_:
   `Pointers <#Pointers>`_
-  `data types, primitive <#index-data-types_002c-primitive-22>`_:
   `Primitive Types <#Primitive-Types>`_
-  `data types, real number <#index-data-types_002c-real-number-40>`_:
   `Real Number Types <#Real-Number-Types>`_
-  `data types, structure <#index-data-types_002c-structure-76>`_:
   `Structures <#Structures>`_
-  `data types, union <#index-data-types_002c-union-59>`_:
   `Unions <#Unions>`_
-  `declarations inside
   expressions <#index-declarations-inside-expressions-174>`_:
   `Statements and Declarations in
   Expressions <#Statements-and-Declarations-in-Expressions>`_
-  `declarations, function <#index-declarations_002c-function-206>`_:
   `Function Declarations <#Function-Declarations>`_
-  `declaring arrays <#index-declaring-arrays-96>`_: `Declaring
   Arrays <#Declaring-Arrays>`_
-  `declaring enumerations <#index-declaring-enumerations-55>`_:
   `Declaring Enumerations <#Declaring-Enumerations>`_
-  `declaring pointers <#index-declaring-pointers-117>`_: `Declaring
   Pointers <#Declaring-Pointers>`_
-  `declaring string arrays <#index-declaring-string-arrays-107>`_:
   `Arrays as Strings <#Arrays-as-Strings>`_
-  `declaring structure
   variables <#index-declaring-structure-variables-79>`_: `Declaring
   Structure Variables <#Declaring-Structure-Variables>`_
-  `declaring structure variables after
   definition <#index-declaring-structure-variables-after-definition-83>`_:
   `Declaring Structure Variables After
   Definition <#Declaring-Structure-Variables-After-Definition>`_
-  `declaring structure variables at
   definition <#index-declaring-structure-variables-at-definition-81>`_:
   `Declaring Structure Variables at
   Definition <#Declaring-Structure-Variables-at-Definition>`_
-  `declaring union variables <#index-declaring-union-variables-62>`_:
   `Declaring Union Variables <#Declaring-Union-Variables>`_
-  `declaring union variables after
   definition <#index-declaring-union-variables-after-definition-66>`_:
   `Declaring Union Variables After
   Definition <#Declaring-Union-Variables-After-Definition>`_
-  `declaring union variables at
   definition <#index-declaring-union-variables-at-definition-64>`_:
   `Declaring Union Variables at
   Definition <#Declaring-Union-Variables-at-Definition>`_
-  `decrement operator <#index-decrement-operator-147>`_: `Incrementing
   and Decrementing <#Incrementing-and-Decrementing>`_
-  `defining enumerations <#index-defining-enumerations-53>`_: `Defining
   Enumerations <#Defining-Enumerations>`_
-  `defining structures <#index-defining-structures-77>`_: `Defining
   Structures <#Defining-Structures>`_
-  `defining unions <#index-defining-unions-60>`_: `Defining
   Unions <#Defining-Unions>`_
-  `definitions, function <#index-definitions_002c-function-208>`_:
   `Function Definitions <#Function-Definitions>`_
-  `division, integer <#index-division_002c-integer-250>`_: `Signed
   Integer Division <#Signed-Integer-Division>`_
-  ```do`` statement <#index-g_t_0040code_007bdo_007d-statement-193>`_:
   `The do Statement <#The-do-Statement>`_
-  ```double`` data
   type <#index-g_t_0040code_007bdouble_007d-data-type-45>`_: `Real
   Number Types <#Real-Number-Types>`_
-  ```else``
   statements <#index-g_t_0040code_007belse_007d-statements-190>`_: `The
   if Statement <#The-if-Statement>`_
-  `enumerations <#index-enumerations-50>`_:
   `Enumerations <#Enumerations>`_
-  `enumerations, declaring <#index-enumerations_002c-declaring-56>`_:
   `Declaring Enumerations <#Declaring-Enumerations>`_
-  `enumerations, defining <#index-enumerations_002c-defining-54>`_:
   `Defining Enumerations <#Defining-Enumerations>`_
-  `enumerations,
   incomplete <#index-enumerations_002c-incomplete-128>`_: `Incomplete
   Types <#Incomplete-Types>`_
-  `exit status <#index-exit-status-219>`_: `The main
   Function <#The-main-Function>`_
-  ```EXIT_FAILURE`` <#index-g_t_0040code_007bEXIT_005fFAILURE_007d-220>`_:
   `The main Function <#The-main-Function>`_
-  ```EXIT_SUCCESS`` <#index-g_t_0040code_007bEXIT_005fSUCCESS_007d-221>`_:
   `The main Function <#The-main-Function>`_
-  `expression statements <#index-expression-statements-187>`_:
   `Expression Statements <#Expression-Statements>`_
-  `expressions <#index-expressions-142>`_:
   `Expressions <#Expressions>`_
-  `expressions containing
   statements <#index-expressions-containing-statements-175>`_:
   `Statements and Declarations in
   Expressions <#Statements-and-Declarations-in-Expressions>`_
-  `expressions,
   conditional <#index-expressions_002c-conditional-171>`_: `Conditional
   Expressions <#Conditional-Expressions>`_
-  ```extern`` storage class
   specifier <#index-g_t_0040code_007bextern_007d-storage-class-specifier-137>`_:
   `Storage Class Specifiers <#Storage-Class-Specifiers>`_
-  `fields, bit <#index-fields_002c-bit-90>`_: `Bit
   Fields <#Bit-Fields>`_
-  ```float`` data
   type <#index-g_t_0040code_007bfloat_007d-data-type-44>`_: `Real
   Number Types <#Real-Number-Types>`_
-  `floating point constants <#index-floating-point-constants-10>`_:
   `Real Number Constants <#Real-Number-Constants>`_
-  `floating point types <#index-floating-point-types-39>`_: `Real
   Number Types <#Real-Number-Types>`_
-  ```for``
   statement <#index-g_t_0040code_007bfor_007d-statement-194>`_: `The
   for Statement <#The-for-Statement>`_
-  `function calls, as
   expressions <#index-function-calls_002c-as-expressions-166>`_:
   `Function Calls as Expressions <#Function-Calls-as-Expressions>`_
-  `function declarations <#index-function-declarations-205>`_:
   `Function Declarations <#Function-Declarations>`_
-  `function definitions <#index-function-definitions-207>`_: `Function
   Definitions <#Function-Definitions>`_
-  `function parameter lists, variable
   length <#index-function-parameter-lists_002c-variable-length-215>`_:
   `Variable Length Parameter Lists <#Variable-Length-Parameter-Lists>`_
-  `function parameters <#index-function-parameters-211>`_: `Function
   Parameters <#Function-Parameters>`_
-  `function pointers, calling
   through <#index-function-pointers_002c-calling-through-216>`_:
   `Calling Functions Through Function
   Pointers <#Calling-Functions-Through-Function-Pointers>`_
-  `function, main <#index-function_002c-main-218>`_: `The main
   Function <#The-main-Function>`_
-  `functions <#index-functions-204>`_: `Functions <#Functions>`_
-  `functions, calling <#index-functions_002c-calling-210>`_: `Calling
   Functions <#Calling-Functions>`_
-  `functions, nested <#index-functions_002c-nested-229>`_: `Nested
   Functions <#Nested-Functions>`_
-  `functions, recursive <#index-functions_002c-recursive-224>`_:
   `Recursive Functions <#Recursive-Functions>`_
-  `functions, static <#index-functions_002c-static-226>`_: `Static
   Functions <#Static-Functions>`_
-  ```goto``
   statement <#index-g_t_0040code_007bgoto_007d-statement-199>`_: `The
   goto Statement <#The-goto-Statement>`_
-  `hello program <#index-hello-program-234>`_: `A Sample
   Program <#A-Sample-Program>`_
-  `hello.c <#index-hello_002ec-235>`_: `hello.c <#hello_002ec>`_
-  `identifiers <#index-identifiers-3>`_: `Identifiers <#Identifiers>`_
-  ```if``
   statements <#index-g_t_0040code_007bif_007d-statements-189>`_: `The
   if Statement <#The-if-Statement>`_
-  `incomplete types <#index-incomplete-types-125>`_: `Incomplete
   Types <#Incomplete-Types>`_
-  `increment operator <#index-increment-operator-146>`_: `Incrementing
   and Decrementing <#Incrementing-and-Decrementing>`_
-  `indirect member access
   operator <#index-indirect-member-access-operator-169>`_: `Member
   Access Expressions <#Member-Access-Expressions>`_
-  `initializing arrays <#index-initializing-arrays-98>`_: `Initializing
   Arrays <#Initializing-Arrays>`_
-  `initializing pointers <#index-initializing-pointers-119>`_:
   `Initializing Pointers <#Initializing-Pointers>`_
-  `initializing string
   arrays <#index-initializing-string-arrays-109>`_: `Arrays as
   Strings <#Arrays-as-Strings>`_
-  `initializing structure
   members <#index-initializing-structure-members-85>`_: `Initializing
   Structure Members <#Initializing-Structure-Members>`_
-  `initializing union members <#index-initializing-union-members-68>`_:
   `Initializing Union Members <#Initializing-Union-Members>`_
-  ```int`` data type <#index-g_t_0040code_007bint_007d-data-type-32>`_:
   `Integer Types <#Integer-Types>`_
-  `integer constants <#index-integer-constants-6>`_: `Integer
   Constants <#Integer-Constants>`_
-  `integer overflow <#index-integer-overflow-246>`_: `Signed Overflow
   Advice <#Signed-Overflow-Advice>`_
-  `integer overflow <#index-integer-overflow-241>`_: `Signed Overflow
   Examples <#Signed-Overflow-Examples>`_
-  `integer overflow <#index-integer-overflow-237>`_: `Integer Overflow
   Basics <#Integer-Overflow-Basics>`_
-  `integer types <#index-integer-types-24>`_: `Integer
   Types <#Integer-Types>`_
-  `keywords <#index-keywords-4>`_: `Keywords <#Keywords>`_
-  `labeled statements <#index-labeled-statements-185>`_:
   `Labels <#Labels>`_
-  `labels <#index-labels-184>`_: `Labels <#Labels>`_
-  `lexical elements <#index-lexical-elements-2>`_: `Lexical
   Elements <#Lexical-Elements>`_
-  `logical operators <#index-logical-operators-156>`_: `Logical
   Operators <#Logical-Operators>`_
-  `logical operators,
   bitwise <#index-logical-operators_002c-bitwise-160>`_: `Bitwise
   Logical Operators <#Bitwise-Logical-Operators>`_
-  ```long double`` data
   type <#index-g_t_0040code_007blong-double_007d-data-type-46>`_: `Real
   Number Types <#Real-Number-Types>`_
-  ```long int`` data
   type <#index-g_t_0040code_007blong-int_007d-data-type-34>`_: `Integer
   Types <#Integer-Types>`_
-  ```long long int`` data
   type <#index-g_t_0040code_007blong-long-int_007d-data-type-36>`_:
   `Integer Types <#Integer-Types>`_
-  `loop induction <#index-loop-induction-245>`_: `Optimization and
   Wraparound <#Optimization-and-Wraparound>`_
-  `macros, statements in
   expressions <#index-macros_002c-statements-in-expressions-176>`_:
   `Statements and Declarations in
   Expressions <#Statements-and-Declarations-in-Expressions>`_
-  `main function <#index-main-function-217>`_: `The main
   Function <#The-main-Function>`_
-  `member access expressions <#index-member-access-expressions-168>`_:
   `Member Access Expressions <#Member-Access-Expressions>`_
-  `multidimensional arrays <#index-multidimensional-arrays-102>`_:
   `Multidimensional Arrays <#Multidimensional-Arrays>`_
-  `nested functions <#index-nested-functions-228>`_: `Nested
   Functions <#Nested-Functions>`_
-  `null statement <#index-null-statement-197>`_: `The Null
   Statement <#The-Null-Statement>`_
-  `operator precedence <#index-operator-precedence-178>`_: `Operator
   Precedence <#Operator-Precedence>`_
-  `operator, decrement <#index-operator_002c-decrement-149>`_:
   `Incrementing and Decrementing <#Incrementing-and-Decrementing>`_
-  `operator, increment <#index-operator_002c-increment-148>`_:
   `Incrementing and Decrementing <#Incrementing-and-Decrementing>`_
-  `operators <#index-operators-143>`_: `Expressions <#Expressions>`_
-  `operators as lexical
   elements <#index-operators-as-lexical-elements-16>`_:
   `Operators <#Operators>`_
-  `operators, arithmetic <#index-operators_002c-arithmetic-151>`_:
   `Arithmetic Operators <#Arithmetic-Operators>`_
-  `operators, assignment <#index-operators_002c-assignment-145>`_:
   `Assignment Operators <#Assignment-Operators>`_
-  `operators, comparison <#index-operators_002c-comparison-155>`_:
   `Comparison Operators <#Comparison-Operators>`_
-  `overflow, signed
   integer <#index-overflow_002c-signed-integer-247>`_: `Signed Overflow
   Advice <#Signed-Overflow-Advice>`_
-  `overflow, signed
   integer <#index-overflow_002c-signed-integer-242>`_: `Signed Overflow
   Examples <#Signed-Overflow-Examples>`_
-  `overflow, signed
   integer <#index-overflow_002c-signed-integer-238>`_: `Integer
   Overflow Basics <#Integer-Overflow-Basics>`_
-  `parameters lists, variable
   length <#index-parameters-lists_002c-variable-length-214>`_:
   `Variable Length Parameter Lists <#Variable-Length-Parameter-Lists>`_
-  `parameters, function <#index-parameters_002c-function-212>`_:
   `Function Parameters <#Function-Parameters>`_
-  `pointer operators <#index-pointer-operators-161>`_: `Pointer
   Operators <#Pointer-Operators>`_
-  `pointers <#index-pointers-114>`_: `Pointers <#Pointers>`_
-  `pointers to structures <#index-pointers-to-structures-123>`_:
   `Pointers to Structures <#Pointers-to-Structures>`_
-  `pointers to unions <#index-pointers-to-unions-121>`_: `Pointers to
   Unions <#Pointers-to-Unions>`_
-  `pointers, declaring <#index-pointers_002c-declaring-118>`_:
   `Declaring Pointers <#Declaring-Pointers>`_
-  `pointers, initializing <#index-pointers_002c-initializing-120>`_:
   `Initializing Pointers <#Initializing-Pointers>`_
-  `precedence, operator <#index-precedence_002c-operator-179>`_:
   `Operator Precedence <#Operator-Precedence>`_
-  `preface <#index-preface-1>`_: `Preface <#Preface>`_
-  `primitive data types <#index-primitive-data-types-21>`_: `Primitive
   Types <#Primitive-Types>`_
-  `program structure <#index-program-structure-230>`_: `Program
   Structure <#Program-Structure>`_
-  `qualifiers, type <#index-qualifiers_002c-type-131>`_: `Type
   Qualifiers <#Type-Qualifiers>`_
-  `real number constants <#index-real-number-constants-12>`_: `Real
   Number Constants <#Real-Number-Constants>`_
-  `real number types <#index-real-number-types-38>`_: `Real Number
   Types <#Real-Number-Types>`_
-  `recursive functions <#index-recursive-functions-223>`_: `Recursive
   Functions <#Recursive-Functions>`_
-  ```register`` storage class
   specifier <#index-g_t_0040code_007bregister_007d-storage-class-specifier-138>`_:
   `Storage Class Specifiers <#Storage-Class-Specifiers>`_
-  `renaming types <#index-renaming-types-140>`_: `Renaming
   Types <#Renaming-Types>`_
-  ```return``
   statement <#index-g_t_0040code_007breturn_007d-statement-202>`_: `The
   return Statement <#The-return-Statement>`_
-  `return value of
   ``main`` <#index-return-value-of-_0040code_007bmain_007d-222>`_: `The
   main Function <#The-main-Function>`_
-  `sample program <#index-sample-program-233>`_: `A Sample
   Program <#A-Sample-Program>`_
-  `scope <#index-scope-232>`_: `Scope <#Scope>`_
-  `separators <#index-separators-17>`_: `Separators <#Separators>`_
-  `sequence point <#index-sequence-point-181>`_: `Sequence
   Points <#Sequence-Points>`_
-  `shifting <#index-shifting-158>`_: `Bit Shifting <#Bit-Shifting>`_
-  ```short int`` data
   type <#index-g_t_0040code_007bshort-int_007d-data-type-30>`_:
   `Integer Types <#Integer-Types>`_
-  `side effect <#index-side-effect-180>`_: `Side
   Effects <#Side-Effects>`_
-  `side effects, macro
   argument <#index-side-effects_002c-macro-argument-177>`_: `Statements
   and Declarations in
   Expressions <#Statements-and-Declarations-in-Expressions>`_
-  ```signed char`` data
   type <#index-g_t_0040code_007bsigned-char_007d-data-type-27>`_:
   `Integer Types <#Integer-Types>`_
-  `signed integer overflow <#index-signed-integer-overflow-248>`_:
   `Signed Overflow Advice <#Signed-Overflow-Advice>`_
-  `signed integer overflow <#index-signed-integer-overflow-243>`_:
   `Signed Overflow Examples <#Signed-Overflow-Examples>`_
-  `signed integer overflow <#index-signed-integer-overflow-239>`_:
   `Integer Overflow Basics <#Integer-Overflow-Basics>`_
-  `size of structures <#index-size-of-structures-91>`_: `Size of
   Structures <#Size-of-Structures>`_
-  `size of unions <#index-size-of-unions-72>`_: `Size of
   Unions <#Size-of-Unions>`_
-  `sizeof operator <#index-sizeof-operator-162>`_: `The sizeof
   Operator <#The-sizeof-Operator>`_
-  `specifiers, storage
   class <#index-specifiers_002c-storage-class-135>`_: `Storage Class
   Specifiers <#Storage-Class-Specifiers>`_
-  `statement, null <#index-statement_002c-null-198>`_: `The Null
   Statement <#The-Null-Statement>`_
-  `statements <#index-statements-183>`_: `Statements <#Statements>`_
-  `statements inside
   expressions <#index-statements-inside-expressions-173>`_: `Statements
   and Declarations in
   Expressions <#Statements-and-Declarations-in-Expressions>`_
-  `statements, expression <#index-statements_002c-expression-188>`_:
   `Expression Statements <#Expression-Statements>`_
-  `statements, labeled <#index-statements_002c-labeled-186>`_:
   `Labels <#Labels>`_
-  `static functions <#index-static-functions-225>`_: `Static
   Functions <#Static-Functions>`_
-  `static linkage <#index-static-linkage-227>`_: `Static
   Functions <#Static-Functions>`_
-  ```static`` storage class
   specifier <#index-g_t_0040code_007bstatic_007d-storage-class-specifier-139>`_:
   `Storage Class Specifiers <#Storage-Class-Specifiers>`_
-  `storage class specifiers <#index-storage-class-specifiers-134>`_:
   `Storage Class Specifiers <#Storage-Class-Specifiers>`_
-  `string arrays,
   declaring <#index-string-arrays_002c-declaring-106>`_: `Arrays as
   Strings <#Arrays-as-Strings>`_
-  `string arrays,
   initializing <#index-string-arrays_002c-initializing-108>`_: `Arrays
   as Strings <#Arrays-as-Strings>`_
-  `string constants <#index-string-constants-14>`_: `String
   Constants <#String-Constants>`_
-  `string literals <#index-string-literals-15>`_: `String
   Constants <#String-Constants>`_
-  `strings, arrays as <#index-strings_002c-arrays-as-105>`_: `Arrays as
   Strings <#Arrays-as-Strings>`_
-  `structure members,
   accessing <#index-structure-members_002c-accessing-88>`_: `Accessing
   Structure Members <#Accessing-Structure-Members>`_
-  `structure members,
   initializing <#index-structure-members_002c-initializing-86>`_:
   `Initializing Structure Members <#Initializing-Structure-Members>`_
-  `structure variables,
   declaring <#index-structure-variables_002c-declaring-80>`_:
   `Declaring Structure Variables <#Declaring-Structure-Variables>`_
-  `structure variables, declaring after
   definition <#index-structure-variables_002c-declaring-after-definition-84>`_:
   `Declaring Structure Variables After
   Definition <#Declaring-Structure-Variables-After-Definition>`_
-  `structure variables, declaring at
   definition <#index-structure-variables_002c-declaring-at-definition-82>`_:
   `Declaring Structure Variables at
   Definition <#Declaring-Structure-Variables-at-Definition>`_
-  `structure, program <#index-structure_002c-program-231>`_: `Program
   Structure <#Program-Structure>`_
-  `structures <#index-structures-74>`_: `Structures <#Structures>`_
-  `structures, arrays of <#index-structures_002c-arrays-of-113>`_:
   `Arrays of Structures <#Arrays-of-Structures>`_
-  `structures, defining <#index-structures_002c-defining-78>`_:
   `Defining Structures <#Defining-Structures>`_
-  `structures, incomplete <#index-structures_002c-incomplete-127>`_:
   `Incomplete Types <#Incomplete-Types>`_
-  `structures, pointers to <#index-structures_002c-pointers-to-124>`_:
   `Pointers to Structures <#Pointers-to-Structures>`_
-  `structures, size of <#index-structures_002c-size-of-92>`_: `Size of
   Structures <#Size-of-Structures>`_
-  ```switch``
   statement <#index-g_t_0040code_007bswitch_007d-statement-191>`_: `The
   switch Statement <#The-switch-Statement>`_
-  `system.h <#index-system_002eh-236>`_: `system.h <#system_002eh>`_
-  `ternary operator <#index-ternary-operator-172>`_: `Conditional
   Expressions <#Conditional-Expressions>`_
-  `type casts <#index-type-casts-163>`_: `Type Casts <#Type-Casts>`_
-  `type qualifiers <#index-type-qualifiers-130>`_: `Type
   Qualifiers <#Type-Qualifiers>`_
-  ```typedef``
   statement <#index-g_t_0040code_007btypedef_007d-statement-203>`_:
   `The typedef Statement <#The-typedef-Statement>`_
-  `types <#index-types-20>`_: `Data Types <#Data-Types>`_
-  `types, array <#index-types_002c-array-94>`_: `Arrays <#Arrays>`_
-  `types, complex number <#index-types_002c-complex-number-49>`_:
   `Complex Number Types <#Complex-Number-Types>`_
-  `types, enumeration <#index-types_002c-enumeration-51>`_:
   `Enumerations <#Enumerations>`_
-  `types, floating point <#index-types_002c-floating-point-43>`_: `Real
   Number Types <#Real-Number-Types>`_
-  `types, incomplete <#index-types_002c-incomplete-126>`_: `Incomplete
   Types <#Incomplete-Types>`_
-  `types, integer <#index-types_002c-integer-26>`_: `Integer
   Types <#Integer-Types>`_
-  `types, pointer <#index-types_002c-pointer-115>`_:
   `Pointers <#Pointers>`_
-  `types, primitive <#index-types_002c-primitive-23>`_: `Primitive
   Types <#Primitive-Types>`_
-  `types, real number <#index-types_002c-real-number-42>`_: `Real
   Number Types <#Real-Number-Types>`_
-  `types, renaming <#index-types_002c-renaming-141>`_: `Renaming
   Types <#Renaming-Types>`_
-  `types, structure <#index-types_002c-structure-75>`_:
   `Structures <#Structures>`_
-  `types, union <#index-types_002c-union-58>`_: `Unions <#Unions>`_
-  `union members, accessing <#index-union-members_002c-accessing-71>`_:
   `Accessing Union Members <#Accessing-Union-Members>`_
-  `union members,
   initializing <#index-union-members_002c-initializing-69>`_:
   `Initializing Union Members <#Initializing-Union-Members>`_
-  `union variables,
   declaring <#index-union-variables_002c-declaring-63>`_: `Declaring
   Union Variables <#Declaring-Union-Variables>`_
-  `union variables, declaring after
   definition <#index-union-variables_002c-declaring-after-definition-67>`_:
   `Declaring Union Variables After
   Definition <#Declaring-Union-Variables-After-Definition>`_
-  `union variables, declaring at
   definition <#index-union-variables_002c-declaring-at-definition-65>`_:
   `Declaring Union Variables at
   Definition <#Declaring-Union-Variables-at-Definition>`_
-  `unions <#index-unions-57>`_: `Unions <#Unions>`_
-  `unions, arrays of <#index-unions_002c-arrays-of-111>`_: `Arrays of
   Unions <#Arrays-of-Unions>`_
-  `unions, defining <#index-unions_002c-defining-61>`_: `Defining
   Unions <#Defining-Unions>`_
-  `unions, incomplete <#index-unions_002c-incomplete-129>`_:
   `Incomplete Types <#Incomplete-Types>`_
-  `unions, pointers to <#index-unions_002c-pointers-to-122>`_:
   `Pointers to Unions <#Pointers-to-Unions>`_
-  `unions, size of <#index-unions_002c-size-of-73>`_: `Size of
   Unions <#Size-of-Unions>`_
-  ```unsigned char`` data
   type <#index-g_t_0040code_007bunsigned-char_007d-data-type-28>`_:
   `Integer Types <#Integer-Types>`_
-  ```unsigned int`` data
   type <#index-g_t_0040code_007bunsigned-int_007d-data-type-33>`_:
   `Integer Types <#Integer-Types>`_
-  ```unsigned long int`` data
   type <#index-g_t_0040code_007bunsigned-long-int_007d-data-type-35>`_:
   `Integer Types <#Integer-Types>`_
-  ```unsigned long long int`` data
   type <#index-g_t_0040code_007bunsigned-long-long-int_007d-data-type-37>`_:
   `Integer Types <#Integer-Types>`_
-  ```unsigned short int`` data
   type <#index-g_t_0040code_007bunsigned-short-int_007d-data-type-31>`_:
   `Integer Types <#Integer-Types>`_
-  `unspecified behaviour <#index-unspecified-behaviour-182>`_:
   `Sequence Points Constrain
   Expressions <#Sequence-Points-Constrain-Expressions>`_
-  `variable length parameter
   lists <#index-variable-length-parameter-lists-213>`_: `Variable
   Length Parameter Lists <#Variable-Length-Parameter-Lists>`_
-  ```volatile`` type
   qualifier <#index-g_t_0040code_007bvolatile_007d-type-qualifier-133>`_:
   `Type Qualifiers <#Type-Qualifiers>`_
-  ```while``
   statement <#index-g_t_0040code_007bwhile_007d-statement-192>`_: `The
   while Statement <#The-while-Statement>`_
-  `white space <#index-white-space-18>`_: `White Space <#White-Space>`_
-  `wraparound arithmetic <#index-wraparound-arithmetic-249>`_: `Signed
   Overflow Advice <#Signed-Overflow-Advice>`_
-  `wraparound arithmetic <#index-wraparound-arithmetic-244>`_: `Signed
   Overflow Examples <#Signed-Overflow-Examples>`_
-  `wraparound arithmetic <#index-wraparound-arithmetic-240>`_: `Integer
   Overflow Basics <#Integer-Overflow-Basics>`_

--------------

Footnotes
^^^^^^^^^

[`1 <#fnd-1>`_] C++ also has complex number support, but it is
incompatible with the ISO C99 types

[`2 <#fnd-2>`_] a full declarator is a declaration of a function or an
object which is not part of another object

[`3 <#fnd-3>`_] However if for example ``MAX`` is ``INT_MAX`` and ``x``
is of type ``int``, we clearly have a problem with overflow. See
`Overflow <#Overflow>`_.

[`4 <#fnd-4>`_] Rarely, ``argv[0]`` can be a null pointer (in this case
``argc`` is 0) or ``argv[0][0]`` can be the null character. In any case,
``argv[argc]`` is a null pointer.

--------------

