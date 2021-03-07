## In python 3.8 two dictionaries, d1 and d2, were created - d1 = {'p': 1, 'q': 2}; d2 = {'q': 3, 'r': 4}. Which of the following code snippet would NOT merge these two dictionaries into a dictionary called d3 that will have {'q': 2, 'r': 4, 'p': 1} as its data.
 
 #### A: d3 = d2 | d1
 
 #### B: d3 = {**d2, **d1}
 
 #### C: d3 = d2.copy(); d3.update(d1)
 
 #### D: d3 = dict(list(d2.items()) + list(d1.items()))
 
 ### Answer:- A: d3 = d2 | d1

### Explanation:
The code snippet, d3 = d2 | d1 works in version 3.9 or later versions only
