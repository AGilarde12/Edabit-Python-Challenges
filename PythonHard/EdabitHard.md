Make a function that encrypts a given input with these steps:

Input: "apple"

Step 1: Reverse the input: "elppa"

Step 2: Replace all vowels using the following chart:

a => 0
e => 1
o => 2
u => 3

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


In the image below, squares are either empty or filled with a circle.

![Challenge photo](https://edabit-challenges.s3.amazonaws.com/empty_square_sequence.png)

Create a function that takes a number step (which equals HALF the width of a square) and returns the amount of empty squares. The image shows the squares with step 1, 2 and 3. The return value is the number of cells not on a diagonal, which is 0 for the first square, 8 for the second, and 24 for the third.
```python
def empty_sq(step):
	return 8*sum([i for i in range(1,step)])
```

A quadratic equation a x² + b x + c = 0 has either 0, 1, or 2 distinct solutions for x. Given a, b and c, you should return the number of solutions to the equation.

```python
def solutions(a, b, c):
    if ((b * b) - (4 * a * c)) > 0:
        return 2
    elif ((b * b) - (4 * a * c)) == 0:
        return 1
    else:
        return 0
	
```



