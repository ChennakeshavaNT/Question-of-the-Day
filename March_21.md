## What would be the output of executing the following code:
## t = [1,2,3,4]
## x = (t.pop() > t.pop()) > (t.pop() < t.pop())
## t.append(x)
## print(t)
### A: [True]
### B: [False]
### C: 1
### D: 2
### Explanation:
(t.pop() > t.pop()) > (t.pop() < t.pop()) gives (4 > 3) > (2 < 1) which is True as True > False
