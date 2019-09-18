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
IN PROGRESS
https://edabit.com/challenge/49pyDP8dE3pJ2dYMW
