## Question
## What would be the output of executing the following code:
## def f1(*num): print (num + num)
## f1(4/2)
### A: 4
### B: 4.0
### C: (2.0), (2.0)
### D: (2.0, 2.0)
### Answer: D: (2.0, 2.0)
### Explanation:
If the input is a tuple, it concatenates the elements of the tuple and as all divisions return float, the result is a tuple with floats.
