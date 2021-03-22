## What would be the output of executing the following code:
## for i in zip([1, 2, 3], ['x', 'y']): print(i, end='')
### (1, 'x')(2, 'y') ---- ans
### (1, 'x')(2, 'y')(3,)
### (1, 'x')(2, 'y')(3, None)
### IndexError
### Explanation:
zip( ) function expects input iterables to be the same size. If you provide arguments of different lengths, then it will trim the output to the shortest argument,
