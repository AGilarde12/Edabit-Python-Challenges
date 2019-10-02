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
Given a list of integers, return the difference between the largest and smallest integers in the list.
```python
def difference(nums):
	return(max(nums)-min(nums))
```

Create a function that takes two strings as arguments and return either True or False depending on whether the total number of characters in the first string is equal to the total number of characters in the second string.
```python
def comp(txt1, txt2):
	if len(txt1) == len(txt2):
		return(True)
	else:
		return(False)
```

Write a function to check if a list contains a particular number.
```python
def check(lst, el):
	if el in lst:
		return(True)
	else:
		return(False)
```
Create a function that takes a single string as argument and returns an ordered list containing the indexes of all capital letters in the string.
```python
def index_of_caps(word):
 return [index for index, letter in enumerate(word) if letter.isupper()]
```

Create a function to concatenate two integer lists.
```python
def concat(lst1, lst2):
	return(lst1 + lst2)
```
Create a function that returns True if a string is empty and False otherwise.
```python
def is_empty(s):
	if len(s) == 0:
		return(True)
	else:
		return(False)
```

Write a function to check if a list contains a particular number.
```python
def check(lst, el):
	if el in lst:
		return(True)
	else:
		return(False)
```

Create a function that accepts a list and returns the last item in the list. The list can be either homogeneous or heterogeneous.
```python
def get_last_item(lst):
	return(lst[-1])
```

ATM machines allow 4 or 6 digit PIN codes and PIN codes cannot contain anything but exactly 4 digits or exactly 6 digits. Your task is to create a function that takes a string and returns True if the PIN is valid and False if it's not.
```python
def is_valid_PIN(pin):
	return (len(pin) == 4 or len(pin) == 6) and pin.isdigit()
```
