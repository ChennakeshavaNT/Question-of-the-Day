What would be the output of executing the following code:
t = [1,2,3,4]
x = (t.pop() > t.pop()) > (t.pop() < t.pop())
t.append(x)
print(t)
 [True]
 [False]
 1
 2
Explanation:
(t.pop() > t.pop()) > (t.pop() < t.pop()) gives (4 > 3) > (2 < 1) which is True as True > False
