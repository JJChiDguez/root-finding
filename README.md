# Root-finding algorithm

------------------------------------------------------------------------
This project was done by

     Jesús-Javier Chi Domínguez <jjchi@computacion.cs.civnestav.mx>, and
     Francisco Rodríguez-Henríquez <francisco@cs.cinvestav.mx>.
     
------------------------------------------------------------------------
# Requirements

[To run in a personal machine]
To have install any version of the Magma Computational Algebra System.

[To run using the online calculator]
To paste the Magma code implementation in the calculator, which can be
found it at http://magma.maths.usyd.edu.au/calc/

------------------------------------------------------------------------
# Description
Let F_q be a finite field with q = p^n elements and h(x) = h_0 + h_1*x + ... + h_d*x^d
be a polynomial with coefficients in F_q. Then, the proposed algorithm finds all the 
roots of the polynomial h^\sigma(x) = h_0*x + h_1*x^q + ... + h_d*x^{q^d} that belongs 
to F_{q^l} where 

       l = p^d - 1 if h_0, ..., h_d live in F_p, or
       l = q^d - 1 otherwise.
