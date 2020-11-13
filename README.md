# InventorySimulation
Simulation of a continuous review inventory system

This is a model where the stock is reviewed continuously and an order of size y is placed every time the stock level reaches a certain reorder point R.
In this Python script it is possible to manually set the values for order quantity and reorder point.  

Demand is variable and is shown in the following table:

Demand	Probability
0	          .10
1	          .25
2	          .35
3	          .21
4	          .09

Lead time (the number of full days between the placement of the order and the receipt of the order) is variable and is shown in the following table:

Lead Time 	Probability
1	day           60%
2	days          30%
3	days          10%

Each replication will be run for 25 days. 
Shortages must be made up as soon as a new order comes in.

We are interested in analyzing

	1. the average ending inventory

	2. the average shortage amount 

	3. the maximum shortage inventory
