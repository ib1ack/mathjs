---
layout: default
---

<h1 id="function-trace">Function trace <a href="#function-trace" title="Permalink">#</a></h1>

Calculate the trace of a matrix: the sum of the elements on the main
diagonal of a square matrix.


<h2 id="syntax">Syntax <a href="#syntax" title="Permalink">#</a></h2>

```js
math.trace(x)
```

<h3 id="parameters">Parameters <a href="#parameters" title="Permalink">#</a></h3>

Parameter | Type | Description
--------- | ---- | -----------
`x` | Array &#124; Matrix | A matrix

<h3 id="returns">Returns <a href="#returns" title="Permalink">#</a></h3>

Type | Description
---- | -----------
Number | The trace of `x`


<h2 id="examples">Examples <a href="#examples" title="Permalink">#</a></h2>

```js
math.trace([[1, 2], [3, 4]]); // returns 5

var A = [
  [1, 2, 3],
  [-1, 2, 3],
  [2, 0, 3]
]
math.trace(A); // returns 6
```


<h2 id="see-also">See also <a href="#see-also" title="Permalink">#</a></h2>

[diag](diag.html)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->