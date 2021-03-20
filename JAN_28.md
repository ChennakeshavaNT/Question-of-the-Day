## Which line of code should replace '# Replace this line' in the following code snippet to get the result: P-y-t-h-o-n!
## w = 'Python'
## d = {'sep':'-', 'end':'!'}
# Replace this line
### A. print(w, d)
### B. print(*w, *d)
### C. print(*w, **d)
### D. print(**w, **d)
Explanation:
In python, asterisk operator (*) is also used for unpacking. When used with a string, each character in the string becomes a separate object. With the double-asterisk operator (**), you unpack the dicttionary. Here we are passing the contents of the dictionary as arguments for the print function.
