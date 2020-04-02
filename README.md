# geogebra
Saved Geogebra scripts

A place for saving Geogebra ggb scripts...

1) SIR_model.ggb - Susceptible-Infected-Recovered model using ordinary differential equations
2) SIR_modified.ggb - Same as above except some recovered individuals lose immunity
3) JacobiEllipticFunc.ggb - The Jacobian elliptic functions (sn, cn and dn) implemented as a system of ODE's
   a) these are functions of argument *u* and modulus *k* (some authors prefer to use *m=k<sup>2</sup>*)
   b) trigonometric functions: taking *k*=0 gives sn(*u*,0)=sin(*u*), cn(*u*,0)=cos(*u*) and dn(*u*,0)=1
   c) hyperbolic functions: (with *k*=1 or -1) sn(*u*,1)=tanh(*u*), cn(*u*,1)=dn(*u*,1)=sech(*u*)
   d) values of *k* between 0 and 1 (and complex values other than 0, 1 or -1) give non-elementary functions of argument *u*
   
