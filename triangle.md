**Visualisations of triangle constructions using Geogebra**

1. The constructions
  + SSS - *triangle-SSS.ggb* - given three sides
  + SAS - *triangle-SAS.ggb* - given two sides and the contained angle
  + ASA - *triangle-ASA.ggb* - given two angles and the contained side
  + AAS - *triangle-AAS.ggb* - given two angles and a side not contained by them
  + ASS or SSA - *triangle-beastOfBurden - given an angle and two sides that don't contain it, or more politely, given two sides and an angle opposite one of them

2. Notes
  + In all five cases, this is plane geometry.  So, if your application is measuring the surface of the earth, you're assuming the earth is flat.  For small areas like city blocks or perhaps even entire cities, this may be a resonable simplifying assumption.  For larger areas, consider using spherical trigonometry (which has analogues of the laws of sines and cosines), but bear in mind that the earth is flatter at the poles than at the equator, so this too is a simplify assumption.  (Maybe I'll do a spherical version of this set...  Time will tell.)
  
  + SSS - As long as the triangle inequality is satisfied, there is a solution and it is unique up to congruence.  A necessary and sufficient condition for a solution is that the maximum length of the sides is less than the semi-perimeter.  When the semi-perimeter inequality fails, there is no solution.

  + SAS - As long as the contained angle is less than a straight angle (*i.e.* between 0 and 180 degrees), there is a solution and it is unique up to congruence.  Since we're talking about interior angles (which are necessarily positive and less than a straight angle, this means that for all practical purposes, a solution exists and that it is unique up to congruence.)

  + ASA and AAS - As long as the measures of the given angles sum to less than a straight angle, there is a solution, and it is unique up to congruence.

  + AAS - Although the actual AAS construction used here solves for the third angle and then follows the ASA construction, I have attempted to illustrate a more interesting construction involving the Law of Sines.  When the angle adjacent to to the given angle is acute, the construction typically has two solutions (_i.e._ two points of intersection), one of which is extraneous (_i.e._ incorrect) and must be thrown out.  As the angle opposite the given side passes from acute to obtuse, the true solution passes from the second point of intersection to the first.
  
  + ASS/SSA - this is the most interest of the construction in that there are sometimes two solutions up to congruence.

3. Other resources
  + There are proof-of-concept demonstration programs in my COBOL and Fortran repositories that solve these constructions in a purely algebraic manner.

  + *Warning:* It has been a long time since I've used Fortran, and I've never used Fortran extensively.  I did write COBOL extensively back in the 1970s and 1980s (for business programming), but it's the first time I have ever used the CODASYL intrinsic functions extension in COBOL programming.
