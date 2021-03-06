


scanf_conversion
================

scanf, sscanf, fscanf conversion specifications



Description
~~~~~~~~~~~

Each conversion specification in the format parameter contains the
following elements:

:+ The character % (percent sign)
: :+ The optional assignment suppression character *
: :+ An optional numeric maximum field width
: :+ A conversion code
:

The conversion specification has the following syntax:

`[*][width][size]convcode`.

The results from the conversion are placed in v_i arguments unless you
specify assignment suppression with * (asterisk). Assignment
suppression provides a way to describe an input field that is to be
skipped. The input field is a string of nonwhite-space characters. It
extends to the next inappropriate character or until the field width,
if specified, is exhausted.

The conversion code indicates how to interpret the input field. You
should not specify the v_i parameter for a suppressed field. You can
use the following conversion codes:

:% Accepts a single % (percent sign) input at this point; no
  assignment is done.
: :d, i Accepts a decimal integer;
: :u Accepts an unsigned decimal integer;
: :o Accepts an octal integer;
: :x Accepts a hexadecimal integer;
: :e,f,g Accepts a floating-point number. The next field is converted
  accordingly and stored through the corresponding parameter, which
  should be a pointer to a float. The input format for floating-point
  numbers is a string of digits, with the following optional
  characteristics:
: :+ It can be a signed value.
: :+ It can be an exponential value, containing a decimal point
  followed by an exponent field, which consists of an E or an e followed
  by an (optionally signed) integer.
: :+ It can be one of the special values INF, NaN,
: :s Accepts a string of characters.
: :c character value is expected. The normal skip over white space is
  suppressed.
: :%lg get value as a double.
:



See Also
~~~~~~~~


+ `scanf`_ Converts formatted input on standard input
+ `scanf`_ Converts formatted input on standard input
+ `fscanf`_ Converts formatted input read on a file


.. _fscanf: fscanf.html
.. _scanf: scanf.html


