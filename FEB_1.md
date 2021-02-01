What would be the output of executing the following code:
a = ['xyz']
b = ['p', 'q', 'r']
print(list(zip(b, a)))
 [('p', 'xyz'), ('q', 'xyz'), ('r', 'xyz')]
 [('pxyz'), ('qxyz'), ('rxyz')]
 [('pqr', 'xyz')]
 [('p', 'xyz')]
Explanation:
The resulting length of the zip function is the shorter of the arguments for the zip. So it is 1 here as a has only one element. zip returns list of tuples by pairing corresponding elements. Since a has only one element, it pairs the first element of b with first element of a and stops there as for the second and third elements of b there are no corresponding elements in a
