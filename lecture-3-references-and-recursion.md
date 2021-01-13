# Lecture 3: References and Recursion

## Primitive Types vs Reference Types

### Primitive

primitives are stored directly in memory

variable declaration: set aside enough memory for primitive, int 32 bits, double 64bits roughly.

What happened when you declare a variable?

What does equal sign do? GRoE

y = x copies all the bits from x into y

### Reference

variable instantiation: allocate

think of new keyword as returning the address for newly created object

declaration: java allocates 64 bits for address, no matter type of object, these bit can be set to address of the object or null\(all 0s\)

box and pointer annotation to think about object

= sign still work under Golden Rule of Equal

#### declaration and instantiation of array

declaration: int\[\]

instantiation: new or {}



### Parameter passing

it obey the same GRoE\(copy bit from right side of = into left side of =\) 

this behavior is called by pass by value



## IntList



