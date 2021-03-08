### What would be the output of executing the following code:
## a = [1.0, 2, 1, 2, 1.0, 2.5]
## print(a.index(1.0, 1))
## A. 2
## B. 4
## C. 5
## D. TypeError
### Answer:- A. 2
### Explanation:
The index() method returns the index of the specified element in the list. On my hardware, the signature is a.index(value, start=0, stop=9223372036854775807, /) It takes 1/2/3 parameters - value - the element to be searched, start (optional) - start searching from this index and stop (optional) - search the element up to this index. Start, if not given is at 0 (beginning), stop if not given will the maximum possible. Here the trick is to understand that it treats 1.0 and 1 the same.
