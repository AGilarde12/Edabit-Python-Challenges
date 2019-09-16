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


