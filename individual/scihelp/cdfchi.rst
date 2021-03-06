


cdfchi
======

cumulative distribution function chi-square distribution



Calling Sequence
~~~~~~~~~~~~~~~~


::

    [P,Q]=cdfchi("PQ",X,Df)
    [X]=cdfchi("X",Df,P,Q);
    [Df]=cdfchi("Df",P,Q,X)




Arguments
~~~~~~~~~

:P,Q,Xn,Df four real vectors of the same size.
: :P,Q (Q=1-P) The integral from 0 to X of the chi-square
  distribution. Input range: [0, 1].
: :X Upper limit of integration of the non-central chi-square
  distribution. Input range: [0, +infinity). Search range: [0,1E300]
: :Df Degrees of freedom of the chi-square distribution. Input range:
  (0, +infinity). Search range: [ 1E-300, 1E300]
:



Description
~~~~~~~~~~~

Calculates any one parameter of the chi-square distribution given
values for the others.

Formula 26.4.19 of Abramowitz and Stegun, Handbook of Mathematical
Functions (1966) is used to reduce the chi-square distribution to the
incomplete distribution.

Computation of other parameters involve a seach for a value that
produces the desired value of P. The search relies on the monotinicity
of P with the other parameter.

From DCDFLIB: Library of Fortran Routines for Cumulative Distribution
Functions, Inverses, and Other Parameters (February, 1994) Barry W.
Brown, James Lovato and Kathy Russell. The University of Texas.



