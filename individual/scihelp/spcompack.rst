


spcompack
=========

converts a compressed adjacency representation



Arguments
~~~~~~~~~

:xadj integer vector of length (n+1).
: :xlindx integer vector of length n+1 (pointers).
: :lindx integer vector
: :adjncy integer vector
:



Description
~~~~~~~~~~~


::

    Utility fonction spcompak is used to convert a compressed adjacency
    representation into standard adjacency representation.




Examples
~~~~~~~~


::

    // A is the sparse matrix:
    A=[1,0,0,0,0,0,0;
       0,1,0,0,0,0,0;
       0,0,1,0,0,0,0;
       0,0,1,1,0,0,0;
       0,0,1,1,1,0,0;
       0,0,1,1,0,1,0;
       0,0,1,1,0,1,1];
    A=`sparse`_(A);
    //For this matrix, the standard adjacency representation is given by:
    xadj=[1,2,3,8,12,13,15,16];
    adjncy=[1, 2, 3,4,5,6,7, 4,5,6,7, 5, 6,7, 7];
    //(see sp2adj).
    // increments in vector xadj give the number of non zero entries in each column
    // ie there is 2-1=1 entry in the column 1
    //    there is 3-2=1 entry in the column 2
    //    there are 8-3=5 entries in the column 3
    //              12-8=4                      4
    //etc
    //The row index of these entries is given by the adjncy vector
    // for instance, 
    // adjncy (3:7)=adjncy(xadj(3):xadj(4)-1)=[3,4,5,6,7] 
    // says that the 5=xadj(4)-xadj(3) entries in column 3 have row
    // indices 3,4,5,6,7.
    //In the compact representation, the repeated sequences in adjncy
    //are eliminated.
    //Here in adjncy the sequences 4,5,6,7  and 7 are eliminated.
    //The standard structure (xadj,adjncy) takes the compressed form (lindx,xlindx)
    lindx=[1, 2, 3,4,5,6,7, 5, 6,7];
    xlindx=[1,2,3,8,9,11];
    //(Columns 4 and 7 of A are eliminated).
    //A can be reconstructed from (xadj,xlindx,lindx).
    [xadj,adjncy,anz]= `sp2adj`_(A);
    adjncy-spcompack(xadj,xlindx,lindx)




See Also
~~~~~~~~


+ `sp2adj`_ converts sparse matrix into adjacency form
+ `adj2sp`_ converts adjacency form into sparse matrix.
+ `spget`_ retrieves entries of sparse matrix


.. _adj2sp: adj2sp.html
.. _spget: spget.html
.. _sp2adj: sp2adj.html


