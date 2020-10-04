# rc-tricks
Some snippets of code written in Plan 9's rc shell.

### Arithmetic
![Arithmetic demonstration](img/arithmetic.png)

### Functional Programming
`dedup` removes all duplication elements from an array.

`r` outputs the return value of a function.

![Deduplication demonstration](img/funcs-dedup.png)
`match` compares two strings and returns `true` if they're the same.

`filter` runs a function on every element in an array, and returns the element if it returns true.
![Filter demonstration](img/funcs-filter.png)
`fold` combines an array into a single element via a function.
![Fold demonstration](img/funcs-fold.png)
`list` declares an array.

`invert` reverses an array.
![Invert demonstration](img/funcs-invert.png)

`map` runs a function on every element in an array, and returns the result.
![Map demonstration](img/funcs-map.png)
