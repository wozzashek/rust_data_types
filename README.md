# Data Types

## Tuple
Tuples like arrays, but each element can be of a different type

Works more like a javascript array. This is fixed length so cannot grow or shrink (those are vectors)

Can be accessed like:
```rust
let tup = (500, 6.4,1); //int, float, int

let big_int = tup.0;
```

## Array
Array of items all of the same data type, again fixed length.

initialized the same was as javascript

**Example**
```rust
let a = [1,2,3,4,5];

//useful tip

let b = [0; 5]; //this will create an array with a length of 5, and each index holding a 0

let first = a[0]; //accessed as most other languages

```