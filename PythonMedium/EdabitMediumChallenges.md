You work for a manufacturer, and have been asked to calculate the total profit made on the sales of a product. You are given a dictionary containing the cost price per unit (in dollars), sell price per unit (in dollars), and the starting inventory. Return the total profit made, rounded to the nearest dollar. Assume all of the inventory has been sold.
```python
def profit(info):
	#Profit = Total Sales - Total Cost
	if info["cost_price"] > 0 and info["sell_price"] > 0:
		return(round(info["sell_price"]*info["inventory"]-(info["cost_price"]*
		info["inventory"])))
```

You hired three programmers and you (hopefully) pay them. Create a function that takes three numbers (the hourly wage of each programmer) and returns the difference between the highest-paid programmer and the lowest-paid.
```python
def programmers(one, two, three):
	lst = one,two,three
	return(max(lst)-min(lst))
```

Create a function that returns True if an integer is divisible by 5, and false otherwise.
```python
def divisible_by_five(n):
	if n % 5 == 0:
		return(True)
	else:
		return(False)
```

Write a function that validates whether two strings are identical. Make it case insensitive.
```python
#("hello", "hELLo") ➞ True
def match(s1, s2):
	if s1.lower() == s2.lower():
		return(True)
	else:
		return(False)
```
Create a function that takes in a list and returns a list of the accumulating sum.
```python
#accumulating_list([1, 5, 7]) ➞ [1, 6, 13]
def accumulating_list(list):
 return [sum(list[:i+1]) for i in range(len(list))]
```

Create a function that takes an integer and outputs an n x n square solely consisting of the integer n.
```python
#Ex - square_patch(3) ➞ [
  [3, 3, 3],
  [3, 3, 3],
  [3, 3, 3]
]

#####in progress####
def square_patch(n):
	if n >= 0:
		for i in range(n):    
   	n.append(i)
	if n < 0:
		return()
```


You have a list of item codes with the following format: "[letters][digits]"
Create a function that splits these strings into their alphabetic and numeric parts.

```python
def split_code(item):
 head = item.rstrip('0123456789')
 tail = item[len(head):]
 return[head, int(tail)]
```

Create a function that takes a number (from 1 - 60) and returns a corresponding string of hyphens.
```python
def num_to_dashes(num):
	return(num * "-")
```

Given two strings, first_name and last_name, return a single string in the format "last, first".
```python
def concat_name(first_name, last_name):
	return(last_name + ", " + first_name)
```

Create a function that returns the ASCII value of the passed in character.
```python
def ctoa(char):
	return(ord(char))
```

