About RIDC
==========

Revisionist Integral Deferred Correction methods -- a family of high-order, parallel time-integrators.

Revisionist integral deferred correction (RIDC) methods are a
family of parallel--in--time methods to solve systems of initial
values problems.  The approach is able to bootstrap lower order time
integrators to provide high order approximations in approximately the
same wall clock time, hence providing a multiplicative increase in the
number of compute cores utilized.  Here we provide a C++ framework
which automatically produces a parallel--in--time solution of a system
of initial value problems given user supplied code for the right hand
side of the system and a sequential code for a first-order time
step.  The user supplied time step routine may be explicit or implicit
and may make use of any auxiliary libraries which take care of the
solution of any nonlinear algebraic systems which may arise or the
numerical linear algebra required.  The code contains six examples of
increasing complexity which also serve as templates to solve user defined
problems.
