


ric_desc
========

Riccati equation



Calling Sequence
~~~~~~~~~~~~~~~~


::

    X=ric_desc(H [,E))
    [X1,X2,zero]=ric_desc(H [,E])




Arguments
~~~~~~~~~

:H,E real square matrices
: :X1,X2 real square matrices
: :zero real number
:



Description
~~~~~~~~~~~

Riccati solver with hamiltonian matrices as inputs.

In the continuous time case calling sequence is `ric_descr(H)` (one
input):

Riccati equation is:


::

    (Ec)   A'*X + X*A + X*R*X -Q = 0.


Defining the hamiltonian matrix `H` by:


::

    H = [A  R;
         Q -A']


with the calling sequence `[X1,X2,zero]=ric_descr(H)`, the solution
`X` is given by `X=X1/X2`.

`zero` = L1 norm of rhs of ( `Ec`)

The solution `X` is also given by `X=riccati(A,Q,R,'c'))`

In the discrete-time case calling sequence is `ric_descr(H,E)` (two
inputs):

The Riccati equation is:


::

    (Ed)  A'*X*A-(A'*X*B*(R+B'*X*B)^-1)*(B'*X*A)+C-X = 0.


Defining `G=B/R*B'` and the hamiltonian pencil `(E,H)` by:


::

    E=[`eye`_(n,n),G;               H=[A, 0*`ones`_(n,n);
       0*`ones`_(n,n),A']             -C, `eye`_(n,n)];


with the calling sequence `[X1,X2,err]=ric_descr(H,E)`, the solution
`X` is given by `X=X1/X2`.

`zero`= L1 norm of rhs of ( `Ed`)

The solution `X` is also given by `X=riccati(A,G,C,'d')` with
`G=B/R*B'`



See Also
~~~~~~~~


+ `riccati`_ Riccati equation


.. _riccati: riccati.html


