# Easy Challenges from Edabit.com

## Challenges get incramentally harder

Create a function that takes a number as an argument. Add up all the numbers from 1 to the number you passed to the function. 
For example, if the input is 4 then your function should return 10 because 1 + 2 + 3 + 4 = 10.

```python
def addUp(num):
	add = (num*(num+1))/2
	return(add)
```

A museum wants to get rid of some exhibitions. Vanya, the interior architect, comes up with a plan to remove the most boring exhibitions. She gives them a rating, and removes the one with the lowest rating. Just as she finishes rating the exhibitions, she's called off to an important meeting. She asks you to write a program that tells her the ratings of the items after the lowest one is removed.
```python
def remove_smallest(lst):
  if lst:
  	lst.remove(min(lst))
  return lst
```
