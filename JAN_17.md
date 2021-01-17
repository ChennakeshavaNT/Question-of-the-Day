## Question:-
## What would be the output of executing the following code:
## import numpy as np
## s=j=k=0
## for e in np.eye(4)*5:s+=e[j];e+=1;j+=1
## print(s)
### A: 4
### B: 5.0
### C: 20.0
### D: SyntaxError
### ANSWER: C: 20.0
### Explanation:
It's the sum of the elements in an identity matrix
