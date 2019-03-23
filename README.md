# identical


## Requirements
* a single function that matches this declaration:
```C
  int identical( int a[], int b[], unsigned int len );
```
* Arrays `a` and `b` are both of length `len`, and contain arbitrary integer values.
* The function `identical()` should return 1 if and only if arrays `a`and `b` contain the same values in the same order, or 0 otherwise.
* `len` can have any unsigned integer value, including 0.
* If `len` is 0 then `identical()` should return 1 (since the arrays have the empty contents).
* You must not change the contents of the arrays.

## Example

return 1:
* a = {10,15,20}, b = {10,15,20}
* a = {100}, b = {100}
* a = {5,2,2,3,4,5,5}, b = {5,2,2,3,4,5,5} 
* a = {}, b = {} (i.e. len = 0)

return 0:
* a = {1,1}, b = {1,2}
* a = {10,15,20}, b = {10,15,21} 
* a = {1,2,3,4,5}, b = {5,3,4,2,2}

