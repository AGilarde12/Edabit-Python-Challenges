Make a function that encrypts a given input with these steps:

Input: "apple"

Step 1: Reverse the input: "elppa"

Step 2: Replace all vowels using the following chart:

a => 0
e => 1
o => 2
u => 3

# "1lpp0"
Step 3: Add "aca" to the end of the word: "1lpp0aca"

Output: "1lpp0aca"

```python
def encrypt(word):
	step_1 = str(word[::-1])
	step_2_1 = step_1.replace('a','0')
	step_2_2 = step_2_1.replace('e','1')
	step_2_3 = step_2_2.replace('o','2')
	step_2_4 = step_2_3.replace('u','3')
	step_4 = step_2_4 + "aca"
	return(step_4)
```

