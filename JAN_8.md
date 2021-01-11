k = 2

s1 = 'a' * k

s2 = "a" * k

s3 = 'a' * 2

s4 = "a" * 2

After executing the code above, which of the following would print True

A.print(s1 is s2)
 
B.print(s1 is s3)
 
C.print(s2 is s4)
 
D.print(s3 is s4)
 
 Answer:- Option D
 
 Explanation:- 
 
 In Python, single and double quotes are the same, but allocator is not able to determine that the content is the same, even if the size is the same, if we multiply string with a constant
