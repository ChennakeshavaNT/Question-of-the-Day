## What would be the output of executing the following code:
## s = 'Ape deer elk cow yak fox ape'
## w = s.lower().split()
## print(max(dict(list(zip(w,[w.count(p) for p in w])))))
### A: 2
### B: ape
### C: deer
### D: yak
### Answer: D: yak
### Explanation:
[w.count(p) for p in w] gives [2, 1, 1, 1, 1, 1, 2] and list(zip(w,[w.count(p) for p in w])) gives [('ape', 2), ('deer', 1), ('elk', 1), ('cow', 1), ('yak', 1), ('fox', 1), ('ape', 2)] and dict(list(zip(w,[w.count(p) for p in w]))) gives {'ape': 2, 'deer': 1, 'elk': 1, 'cow': 1, 'yak': 1, 'fox': 1} and max(dict(list(zip(w,[w.count(p) for p in w])))) gives the last word alphabetically, yak as it is the max key
