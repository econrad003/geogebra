**Visualisations of triangle constructions using Geogebra**

1. The constructions
  + SSS - *triangle-SSS.ggb* - given three sides
  + SAS - *triangle-SAS.ggb* - given two sides and the contained angle
  + ASA - *triangle-ASA.ggb* - given two angles and the contained side
  + AAS - *triangle-AAS.ggb* - given two angles and a side not contained by them

2. Notes
  + AAS - Although the actual AAS construction used here solves for the third angle and then follows the ASA construction, I have attempted to illustrate a more interesting construction involving the Law of Sines.  When the angle adjacent to to the given angle is acute, the construction typically has two solutions (_i.e._ two points of intersection), one of which is extraneous (_i.e._ incorrect) and must be thrown out.  As the angle opposite the given side passes from acute to obtuse, the true solution passes from the second point of intersection to the first.

3. Other resources
  + There are proof-of-concept demonstration programs in my COBOL and Fortran repositories that solve these constructions in a purely algebraic manner.

  + *Warning:* It has been a long time since I've used Fortran, and I've never used Fortran extensively.  I did write COBOL extensively back in the 1970s and 1980s, but it's the first time I have ever used the CODASYL intrinsic functions extension in COBOL programming.
