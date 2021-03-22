## What would be the output of executing the following code:
## for i in zip([1, 2, 3], ['x', 'y']): print(i, end='')
### A: (1, 'x')(2, 'y')
### B: (1, 'x')(2, 'y')(3,)
### C: (1, 'x')(2, 'y')(3, None)
### D: IndexError
### Answer:- A: (1, 'x')(2, 'y')
### Explanation:
zip( ) function expects input iterables to be the same size. If you provide arguments of different lengths, then it will trim the output to the shortest argument,
