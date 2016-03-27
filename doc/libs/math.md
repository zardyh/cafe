math  
====  
idiomatic bindings to the Lua math libraries  
  
## Symbols  
#### `math/π`  
#### `math/pi`  
3.1415926535...  


  
#### `math/huge`  
The value HUGE_VAL, a value larger than or equal to any other numerical value.  


  
## Functions  
### Trigonometrics  
All trigonometric functions assume the parameters to be in radians.  
#### `sin`, `hsin` and `asin`  
Calculate the sine, hyperbolic sine and arc sine of _x_  


  
#### `cos`, `hcos` and `acos`  
Calculate the cosine, hyperbolic cosine and arc cosine of _x_  


  
#### `tan`, `htan` and `atan`  
Calculate the tangent, hyperbolic tangent and arc tangent of _x_  


  
#### `deg2rad` and `rad2deg`  
Convert degrees to radians and vice-versa  


  
### Algebra  
#### `abs`  
return the absolute value of _x_  


  
#### `exp`  
return the value of e<sup>x</sup>  


  
#### `logn`, `log10` and `log2`  
Take the natural, base-10 and base-2 logarithm of _x_.  


  
#### `max` and `min`  
Find the maximum or minimum value of a set (given as variadic arguments or a list)  


  
#### `modf x`  
Returns two numbers, the integral part of _x_ and the fractional part of _x_ as a cons pair  


  
#### `sqrt x`  
Take the root of _x_ with index 2  


  
#### `rand l u`  
Generate a random number with a lower bound at _l_ and an upper bound at _u_  


  
#### `rand-seed n`  
Seed the random number generator with _n_  


  
#### `percent val tot`  
Take the percentage of _val_ against _tot_  


  
### `mean ...`  
Take the arithmetic mean of a set, given as variadic arguments.  

