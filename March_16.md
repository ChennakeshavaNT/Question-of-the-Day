## Question:
## What would be the output of executing the following code:
## x,y = (False, False)
## if (y,) and [y,]: x+=1
## print(x)
### A: 0
### B: 1
### C: False
### D: SyntaxError
### Answer: B: 1
### Explanation:
All non-empty iterables (tuple and list in this example) will evaluate to True and True and True is True and hence x will become 1 and it will be printed
