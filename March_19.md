## Question
### Which of the following code snippets, when executed would NOT give the following output:
### [1, 2, 3, []]
### A: w = [1,2,3]; w.add(len(w), []); print(w)
### B: w = [1,2,3]; w.insert(len(w), []); print(w)
### C: w = [1,2,3]; w.append([]); print(w)
### D: w = [1,2,3]; w.extend([[]]); print(w)
## Answer: 
### A: w = [1,2,3]; w.add(len(w), []); print(w)
## Explanation:
In python, list does not have add method
