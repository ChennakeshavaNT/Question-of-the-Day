## Question:
## What would be the output of executing the following code:
## p = [0, 1, 2, 3, 2, 4]
## q = [4, 3, 2, 1, 1, 3]
## print(set(p) > set(q))
### A: True
### B: False
### C: 1
### D: TypeError
### Answer: A: True 
### Explanation:
In python, a set should have unique elements, so set(p) would be {0, 1, 2, 3, 4} and set q would be {4, 3, 2, 1} and p > q would check whether p is a superset of q and as it is, it prints True
