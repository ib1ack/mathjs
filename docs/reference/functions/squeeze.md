# Function squeeze

Squeeze a matrix, remove outer singleton dimensions from a matrix.


## Syntax

```js
math.squeeze(x)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | Matrix &#124; Array | Matrix to be squeezed

### Returns

Type | Description
---- | -----------
Matrix &#124; Array | Squeezed matrix


## Examples

```js
var math = mathjs();

math.squeeze([3]);           // returns 3
math.squeeze([[3]]);         // returns 3

var A = math.zeros(1, 3, 2); // returns [[[0, 0], [0, 0], [0, 0]]] (size 1x3x2)
math.squeeze(A);             // returns [[0, 0], [0, 0], [0, 0]] (size 3x2)

// only outer dimensions will be squeezed, so the following B will be left as as
var B = math.zeros(3, 1, 1); // returns [[[0]], [[0]], [[0]]] (size 3x1x1)
math.squeeze(B);             // returns [[[0]], [[0]], [[0]]] (size 3x1x1)
```


## See also

[subset](subset.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->