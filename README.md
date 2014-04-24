javascript-the-bad-parts
========================

examples of terrible behavior in javascript

js> [1,2,3] + [4,5,6]
"1,2,34,5,6"

js> ["1","2","3","4"].map(parseInt)
[1, NaN, NaN, NaN]
