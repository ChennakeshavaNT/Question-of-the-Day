## Question
## What would be the output of executing the following code:
## t = 'Hello Python'
## for i in range(5): t = tuple(t)
## print(len(t))
### A: 1
### B: 11
### C: 12
### D: 60
### Answer: C: 12
### Explanation:
The tuple constructor uses the characters of the string to create the tuple. The same tuple will be created in the loop for each iteration. So the tuple in each iteration would be ('H', 'e', 'l', 'l', 'o', ' ', 'P', 'y', 't', 'h', 'o', 'n')
