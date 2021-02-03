What would be the output of executing the following code:
w = [1, 2, 3, 4]
w[2::-2] = [7, 8]
print(w[0])
 7
 8
 1
 2
Explanation:
w[2: :-2] tells us to start at index 2 and step 2 in right to left. so 3 and 1 are replaced by 7 and 8, So, the new list is [8, 2, 7, 4] and 8 is at index 0.
