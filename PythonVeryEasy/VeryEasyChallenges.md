# Very Easy Challenges fround on Edabit.com

## Each challenge gets steadily harder

Create a function that takes a number as an argument, increments the number by +1 and returns the result.
```python
def addition(num):
	return (num + 1)
```

Write a function that takes an integer minutes and converts it to seconds.
```python
def convert(minutes):
	return(minutes*60)
```

Write a function that converts hours into seconds.
```python
def how_many_seconds(hour):
	minutes = hour * 60
	seconds = minutes * 60
	return (seconds)
```

You've got chickens (2 legs), cows (4 legs) and pigs (4 legs) on your farm. Return the total number of legs on your farm.
```python
def animals(chicken,cow,pig):
  return chicken * 2 + (cow + pig) * 4
```

Create a function that takes two numbers as arguments and return their sum.
```python
def addition(a,b):
	total = (a + b)
	return(total)
```

Create a function that takes a base number and an exponent number and returns the calculation.
```python
def calculate_exponent(num, exp):
	calc = (num**exp)
	return(calc)
```

Write a function that takes two integers (hours, minutes) and converts them to seconds.
```python
def convert(hours, minutes):
	h_sec = hours * 3600
	m_sec = minutes*60
	sec = h_sec + m_sec
	return(sec)
```

Create a function that takes in three arguments (prob, prize, pay) and returns true if prob * prize > pay; otherwise return false.
```python
def profitable_gamble(prob, prize, pay):
	gamble = ((prob*prize)-pay)
	if gamble >0:
		return(True)
	elif gamble < 0:
		return(False)
	else:
		return(False)

# profitable_gamble(0.2, 50, 9) should yield true, since the net profit is 1 (0.2 * 50 - 9), and 1 > 0.
# probability_of_winning * prize - cost_of_playing.
```

Create a function that takes a list and returns the first element.
```python
def get_first_value(number_list):
	first = number_list[0]
	return(first)
```

Create a function that returns True when less or equal to zero and False when greater than 0
```python
def less_than_or_equal_to_zero(num):
	if num <= 0:
		return(True)
	elif num > 0:
		return(False)
```

Write two functions:

to_int() : A function to convert a string to an integer.
to_str() : A function to convert an integer to a string
```python
def to_int(txt):
	convert_int = int(txt)
	return(convert_int)

def to_str(num):
	convert_str = str(num)
	return(convert_str)
```

Create a function that takes a list of numbers and returns the smallest number in the list.
```python
def find_smallest_num(lst):
	smallest_num = min(lst)
	return(smallest_num)
```

Create a function that takes an integer and returns True if it's divisible by 100, otherwise return False.
```python
def divisible(num):
	div = (num/100)
	if div.is_integer():
		return True
	else:
		return False
```

```python
Create a function that finds the maximum range of a triangles third edge.
#(side1 + side2) - 1 = maximum range of third edge.
def next_edge(side1, side2):
	tri = (side1 + side2)-1
	return(tri)
```

Create a function that takes a name and returns a greeting.
```python
def hello_name(name):
	return("Hello " + name + "!")
```

Create a function that takes a list and returns the difference between the smallest and biggest numbers.
```python
def difference_max_min(lst):
	diff = (max(lst) - min(lst))
	return(diff)
```

Write a function that returns True if k^k == n for input (n, k).
```python
def k_to_k(n, k):
	ex = k**k
	if ex == n:
		return(True)
	else:
		return(False)
```



