


lqr
===

LQ compensator (full state)



Calling Sequence
~~~~~~~~~~~~~~~~


::

    [K,X]=lqr(P12)




Arguments
~~~~~~~~~

:P12 `syslin` list (state-space linear system)
: :K,X two real matrices
:



Description
~~~~~~~~~~~

`lqr` computes the linear optimal LQ full-state gain for the plant
`P12=[A,B2,C1,D12]` in continuous or discrete time.

`P12` is a `syslin` list (e.g. `P12=syslin('c',A,B2,C1,D12)`).

The cost function is l2-norm of `z'*z` with `z=C1 x + D12 u` i.e.
`[x,u]' * BigQ * [x;u]` where


::

    [C1' ]               [Q  S]
    BigQ= [    ]  * [C1 D12] = [    ]
    [D12']               [S' R]


The gain `K` is such that `A + B2*K` is stable.

`X` is the stabilizing solution of the Riccati equation.

For a continuous plant:


::

    (A-B2*`inv`_(R)*S')'*X+X*(A-B2*`inv`_(R)*S')-X*B2*`inv`_(R)*B2'*X+Q-S*`inv`_(R)*S'=0



::

    K=-`inv`_(R)*(B2'*X+S)


For a discrete plant:


::

    X=A'*X*A-(A'*X*B2+C1'*D12)*`pinv`_(B2'*X*B2+D12'*D12)*(B2'*X*A+D12'*C1)+C1'*C1;



::

    K=-`pinv`_(B2'*X*B2+D12'*D12)*(B2'*X*A+D12'*C1)


An equivalent form for `X` is


::

    X=Abar'*`inv`_(`inv`_(X)+B2*`inv`_(r)*B2')*Abar+Qbar


with `Abar=A-B2*inv(R)*S'` and `Qbar=Q-S*inv(R)*S'`

The 3-blocks matrix pencils associated with these Riccati equations
are:


::

    discrete                           continuous
    |I   0    0|   | A    0    B2|         |I   0   0|   | A    0    B2|
    z|0   A'   0| - |-Q    I    -S|        s|0   I   0| - |-Q   -A'   -S|
    |0   B2'  0|   | S'   0     R|         |0   0   0|   | S'  -B2'   R|


Caution: It is assumed that matrix R is non singular. In particular,
the plant must be tall (number of outputs >= number of inputs).



Examples
~~~~~~~~


::

    A=`rand`_(2,2);B=`rand`_(2,1);   //two states, one input
    Q=`diag`_([2,5]);R=2;     //Usual notations x'Qx + u'Ru
    Big=`sysdiag`_(Q,R);    //Now we calculate C1 and D12
    [w,wp]=`fullrf`_(Big);C1=wp(:,1:2);D12=wp(:,3:$);   //[C1,D12]'*[C1,D12]=Big
    P=`syslin`_('c',A,B,C1,D12);    //The plant (continuous-time)
    [K,X]=lqr(P)
    `spec`_(A+B*K)    //check stability
    `norm`_(A'*X+X*A-X*B*`inv`_(R)*B'*X+Q,1)  //Riccati check
    P=`syslin`_('d',A,B,C1,D12);    // Discrete time plant
    [K,X]=lqr(P)     
    `spec`_(A+B*K)   //check stability
    `norm`_(A'*X*A-(A'*X*B)*`pinv`_(B'*X*B+R)*(B'*X*A)+Q-X,1) //Riccati check




See Also
~~~~~~~~


+ `lqe`_ linear quadratic estimator (Kalman Filter)
+ `gcare`_ Continuous time control Riccati equation
+ `leqr`_ H-infinity LQ gain (full state)


.. _leqr: leqr.html
.. _gcare: gcare.html
.. _lqe: lqe.html


