# geogebra
Saved Geogebra scripts (Geogebra is available from https://www.geogebra.org/)

This is a place for saving my Geogebra ggb scripts...

1) SIR_model.ggb - Susceptible-Infected-Recovered model using ordinary differential equations<br/>
2) SIR_modified.ggb - Same as above except some recovered individuals lose immunity<br/>
3) JacobiEllipticFunc.ggb - The Jacobian elliptic functions (sn, cn and dn) implemented as a system of ODE's
    a) these are functions of argument *u* and modulus *k* (some authors prefer to use *m=k<sup>2</sup>*)
    b) trigonometric functions: taking *k*=0 gives sn(*u*,0)=sin(*u*), cn(*u*,0)=cos(*u*) and dn(*u*,0)=1
    c) hyperbolic functions: (with *k*=1 or -1) sn(*u*,1)=tanh(*u*), cn(*u*,1)=dn(*u*,1)=sech(*u*)
    d) values of *k* between 0 and 1 (and complex values other than 0, 1 or -1) give non-elementary functions of argument *u*
4) natural exponential growth.ggb - an simple illustration of Euler's limit definition of the constant *e*.  (The accompanying png file shows the annual and monthly compounding along with the natural exponential.)
5) Fibonacci.ggb - graphically demonstrate use of the Binet Formula for the Fibonacci numbers (defined using the relations F(0)=0, F(1)=1 and F(n+2)=F(n+1)+F(n)).  *Note:* The analytic continuation is not a function in the sense of one output for each input - the principal branch is used here to make the output unique.  The math is tricky, but the pictures are beautiful.
    a) The JFIF/JPEG image (Fibonacci.jpg) shows the the result if the inputs are the real numbers from -5 to 5.  The geogebra file (Fibonacci.ggb) uses these parameters.
    b) To play with the simulation, the four parameters you can play with are a, b, f and g.  The real numbers a and b control the range of the hidden parameter t: t ranges over the interval \[a,b\].  The parameters f and g yield the input curve (x,y)=(f(t),g(t)).  Treat this as a complex variable z=x+yi, plotted in red.  The best way to work this is to create functions fn and gn of t and then set f=fn and g=gn.  I've provided (f1,g1) from the x-axis and (f2,g2) the unit circle.
    c) The output in blue is the curve (u,v)=binet(z) where u is the real part, v is the imaginary part and binet(z) are complex outputs of the binet function (i.e. the principal branch...)
6) All five of the classic triangle construction problems in plane geometry:
   a) triangle-SSS.ggb
   b) triangle-SAS.ggb
   c) triangle-AAS.ggb
   d) triangle-ASA.ggb
   e) triangle-beastOfBurden.ggb - (angle-side-side) sometimes having two noncongruent solutions
7) triangle-SAS-tan.ggb -  Revisiting SAS using the Law of Tangents to get the angles (instead of using the unknown side with the Law of Cosines). This demo is tricky because of the ways Geogebra handles angles. Note that instead of entering sides b and c, you enter b and the difference c-b to insure c is larger than b.  The Law of Tangents approach was more common in the days before scientific calculators...
8) lawOfSines.ggb - the common textbook argument for the Law of Sines.  This involves writing an altitude in two ways.  (This argument does not make the beautiful and important connection with the circumcircle.)

Enjoy!
