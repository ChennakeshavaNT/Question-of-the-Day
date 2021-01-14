## Question :-
## What would be the output of executing the following code:
## a = [1, 2, 3, 4, 5, 6, 7, 8]
## print(a[-4:--1:-1])
### A: [5, 4, 3, 2]
### B: [5, 4]
### C: [5, 4, 3]
### D: IndexError
### Answer:- C: [5, 4, 3]
### Explanation:
a[-4:--1:-1] is the same as a[-4:1:-1] and -1 makes it the reverse order. starting at -4 means starting with element 5 till element 2 ie [5, 4, 3]
