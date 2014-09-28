References
==========

| Name               | Notation  | Meaning                                                  | Unicode Codepoint|
|--------------------|:---------:|----------------------------------------------------------|------------------|
| Roll	             | &#x003F;B | One integer selected randomly from the first B integers	| U+003F           |
| Ceiling	           | &#x2308;B | Least integer greater than or equal to B	                | U+2308           |
| Floor	             | &#x230A;B | Greatest integer less than or equal to B	                | U+230A           |
| Shape	             | &#x2374;B | Number of components in each dimension of B	            | U+2374           |
| Not	               | &#x223C;B | Logical: &#x223C;1 is 0, &#x223C;0 is 1	                | U+223C           |
| Absolute value	   | &#x2223;B | Magnitude of B	                                          | U+2223           |
| Index generator	   | &#x2373;B | Vector of the first B integers	                          | U+2373           |
| Exponential	       | &#x22C6;B | e to the B power	                                        | U+22C6           |
| Negation	         | &#x2212;B | Changes sign of B	                                      | U+2212           |
| Identity	         | &#x002B;B | No change to B	                                          | U+002B           |
| Signum	           | &#x00D7;B | &#x00AF;1 if B<0; 0 if B=0; 1 if B>0	                    | U+00D7           |
| Reciprocal	       | &#x00F7;B | 1 divided by B	                                          | U+00F7           |
| Ravel	             | &#x002C;B | Reshapes B into a vector	                                | U+002C           |
| Matrix inverse	   | &#x2339;B | Inverse of matrix B	                                    | U+2339           |
| Pi times	         | &#x25CB;B | Multiply by π	                                          | U+25CB           |
| Logarithm	         | &#x235F;B | Natural logarithm of B	                                  | U+235F           |
| Reversal	         | &#x233D;B | Reverse elements of B along last axis	                  | U+233D           |
| Reversal	         | &#x2296;B | Reverse elements of B along first axis	                  | U+2296           |
| Grade up	         | &#x234B;B | Indices of B which will arrange B in ascending order	    | U+234B           |
| Grade down	       | &#x2352;B | Indices of B which will arrange B in descending order	  | U+2352           |
| Execute	           | &#x234E;B | Execute an APL expression	                              | U+234E           |
| Monadic format	   | &#x2355;B | A character representation of B	                        | U+2355           |
| Monadic transpose  | &#x2349;B | Reverse the axes of B	                                  | U+2349           |
| Factorial	         | &#x0021;B | Product of integers 1 to B	                              | U+0021           |

|Name                     |  Notation  |Meaning                                                                 |Codepoint|
|-------------------------|:----------:|------------------------------------------------------------------------|---------|
| Add                     | A&#x002B;B | Sum of A and B	                                                        |U+002B   |
| Subtract                | A&#x2212;B | A minus B	                                                            |U+2212   |
| Multiply                | A&#x00D7;B | A multiplied by B	                                                    |U+00D7   |
| Divide                  | A&#x00F7;B | A divided by B	                                                        |U+00F7   |
| Exponentiation          | A&#x22C6;B | A raised to the B power	                                              |U+22C6   |
| Circle                  | A&#x25CB;B | Trigonometric functions of B selected by A<br>A=1: sin(B) A=2: cos(B) A=3: tan(B)|U+25CB|
| Deal                    | A&#x003F;B | A distinct integers selected randomly from the first B integers	      |U+003F   |
| Membership              | A&#x2208;B | 1 for elements of A present in B; 0 where not.	                        |U+2208   |
| Maximum                 | A&#x2308;B | The greater value of A or B	                                          |U+2308   |
| Minimum                 | A&#x230A;B | The smaller value of A or B	                                          |U+230A   |
| Reshape                 | A&#x2374;B | Array of shape A with data B	                                          |U+2374   |
| Take                    | A&#x2191;B | Select the first (or last) A elements of B according to ×A	            |U+2191   |
| Drop                    | A&#x2193;B | Remove the first (or last) A elements of B according to ×A	            |U+2193   |
| Decode                  | A&#x22A5;B | Value of a polynomial whose coefficients are B at A	                  |U+22A5   |
| Encode                  | A&#x22A4;B | Base-A representation of the value of B	                              |U+22A4   |
| Residue                 | A&#x2223;B | B modulo A	                                                            |U+2223   |
| Catenation              | A&#x002C;B | Elements of B appended to the elements of A	                          |U+002C   |
| Expansion               | A&#x005C;B | Insert zeros (or blanks) in B corresponding to zeros in A	            |U+005C   |
| Compression             | A&#x002F;B | Select elements in B corresponding to ones in A	                      |U+002F   |
| Index of                | A&#x2373;B | The location (index) of B in A; 1+⌈/⍳⍴A if not found	                   |U+2373   |
| Matrix divide           | A&#x2339;B | Solution to system of linear equations Ax = B	                        |U+2339   |
| Rotation                | A&#x233D;B | The elements of B are rotated A positions	                            |U+233D   |
| Rotation                | A&#x2296;B | The elements of B are rotated A positions along the first axis	        |U+2296   |
| Logarithm               | A&#x235F;B | Logarithm of B to base A	                                              |U+235F   |
| Dyadic format           | A&#x2355;B | Format B into a character matrix according to A	                      |U+2355   |
| General transpose       | A&#x2349;B | The axes of B are ordered by A	                                        |U+2349   |
| Combinations            | A&#x0021;B | Number of combinations of B taken A at a time	                        |U+0021   |
| Less than               | A&#x003C;B | Comparison: 1 if true, 0 if false	                                    |U+003C   |
| Less than or equal      | A&#x2264;B | Comparison: 1 if true, 0 if false	                                    |U+2264   |
| Equal                   | A&#x003D;B | Comparison: 1 if true, 0 if false	                                    |U+003D   |
| Greater than or equal   | A&#x2265;B | Comparison: 1 if true, 0 if false	                                    |U+2265   |
| Greater than            | A&#x003E;B | Comparison: 1 if true, 0 if false	                                    |U+003E   |
| Not equal               | A&#x2260;B | Comparison: 1 if true, 0 if false	                                    |U+2260   |
| Or                      | A&#x2228;B | Logic: 0 if A and B are 0; 1 otherwise	                                |U+2228   |
| And                     | A&#x2227;B | Logic: 1 if A and B are 1; 0 otherwise	                                |U+2227   |
| Nor                     | A&#x2371;B | Logic: 1 if both A and B are 0; otherwise 0	                          |U+2371   |
| Nand                    | A&#x2372;B | Logic: 0 if both A and B are 1; otherwise 1	                          |U+2372   |

from [wikipedia](http://en.wikipedia.org/wiki/APL_syntax_and_symbols)
