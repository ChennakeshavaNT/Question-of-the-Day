## Question:-
## Given two lists, a = [1, 2, 3]; b = [2, 3, 4], which of the following code snippets will NOT find the difference between the two lists (elements that are unique ie. elements that are present in one list, but not in the other)?

### A. set(a) ^ set(b)
### B. set(a).symmetric_difference(set(b))
### C. set(set(a) - set(b)).union(set(b) - set(a))
### D. set(set(b).union(a).intersection(set(a).union(b)))

### Answer:- D. set(set(b).union(a).intersection(set(a).union(b)))

### Explanation:-
set(set(b).union(a).intersection(set(a).union(b))) gives the union or universal set, while the others give the difference as desired
