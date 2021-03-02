# Question
### What would be the output of executing the following code:
## *print((lambda x: 3*x // 3 / x % 3)(17))*
## A: 1
## B: 1.0
## C: 3
## D: SyntaxError
## Answer B: 1.0
## Explanation:
print((lambda x: 3*x // 3 / x % 3)(17))
(lambda x: 3*x // 3 / x % 3)(17)
here x=17

Since precedence value of all operators in equation is same execution starts from left to right
=> 3*17//3/17%3
=>51//3/17%3
=>17/17%3
=>1.0%3
=>1.0

Hint:-
lambda takes an expression and evaluates to provide answer

Refer below links to understand better
https://www.w3schools.com/python/python_lambda.asp
https://www.programiz.com/python-programming/precedence-associativity
