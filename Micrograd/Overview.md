Micrograd library's functions:
- value object : We can do all the math with value object, it is essentially like declaring a value to a variable.
  ```python
  a = value(-6,0)
  b = value(8,0)
  ```
- Builds expression tree using the mathematical expressions done using the value objects and it's child nodes
- .data function gives the value of the variable after mathematical expression
- .grad function gives the gradient of the final variable with respect to the value object. 
