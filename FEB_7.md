What would be the output of executing the following code:
t = [10, 13, 16]
print(max(t, key=lambda x: x%5))
 10
 13
 16
 SyntaxError
Explanation:
The built-in function max() takes an optional argument key that expects a function. This key function computes a value for each element in the input list. The function max () operates on the values computed by the key function and returns the maximum depending on those values. Here the modulo 5 value for each element in the list is computed and the maximum key value was found to be for 13
