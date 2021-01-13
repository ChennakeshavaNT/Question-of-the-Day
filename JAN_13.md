## Question:-
## What would be the output of executing the following code:
## print(2**3**2**0*2)
### A: 0
### B: 1
### C: 2
### D: 16
### Answer :- 
## Explanation: D: 16
Unlike all other operators, exponents in python has right to left associativity. In evaluating (2**3**2**0*2), ** has higher precedence than *, so 2**0 is 1, 3**1 is 3 and 2**3 is 8 and then 8*2 = 16
For more info, please visit: Python operators and their precedence
