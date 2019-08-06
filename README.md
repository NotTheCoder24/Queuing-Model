# Inventory-Model
Simulated an inventory model for a given lead time, holding cost and per item cost.

Assumptions Made 
●	No back-orders are permitted.
●	The Production Cost (C0) and Opening Inventory is taken as input from the user.
●	Reordering is done at the end of the month and received at the beginning of a month.
●	Reordering is not permitted if previous order hasn’t been received.
●	Random numbers follow a uniform distribution.
●	The code has been done in matlab
 
Variables 
•	average_stock_level: contains the average stock.
•	expected_total_cost: contains the expected total cost.
•	end_invent: array containing the ending inventory at the end of each month.
•	order_received: array monitoring the order received at the beginning of each month.
•	open_invent: array containing the inventory at the beginning of each month.
•	demand: array containing the demand generated in each month.
•	c0: array containing the production/ordering cost of each month.
•	ch: array containing the holding cost incurred for each month.
•	cs: array containing the shortage cost incurred in each month.
•	lead_time: array containing the lead time for each month (if valid).
•	reorder: array containing the quantity ordered in each month.
•	flag: a variable to check whether an order is in progress or not.
•	u: array containing the random number generated.
•	time: array containing the month number being simulated.
