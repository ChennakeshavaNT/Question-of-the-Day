## import re
## s = '@Raju will meets him @11 am or reply to hr@datai.co'
## print(re.findall('\S+@\S+[.]\w{2,3}', s))
### A. ['Raju']
### B. ['Raju', '11', 'datai']
### C. ['hr@datai.co']
### D. [ ]

## Answer:- C. ['hr@datai.co']

## Explanation:
The regular expression '\S+@\S+[.]\w{2,3}' will get any string with @ followed by some string followed by . followed by two or three letter extension. So it gets all the emails from the string
