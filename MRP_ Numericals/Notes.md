🔹 Purpose
This page helps bridge the aggregate production plan (total for all products) with a detailed master schedule (per product).

📊 TABLE: Aggregate Plan

| Week                    | 1   | 2   | 3   | 4   | 5   | 6   |
| ----------------------- | --- | --- | --- | --- | --- | --- |
| **Aggregate Forecast**  | 160 | 160 | 160 | 160 | 215 | 250 |
| **Production Plan**     | 205 | 205 | 205 | 205 | 205 | 205 |
| **Aggregate Inventory** | 545 | 590 | 635 | 680 | 670 | 625 |

✅ What it shows:

Forecast is the expected demand for the family of products (A + B + C).
Production Plan is fixed at 205 units/week.
Inventory grows slowly over time since production (205) > demand (~160).


🧮 Opening Inventories (per product):

Product A: 350
Product B: 100
Product C: 50

Total: 500
These are the initial stocks for the master schedule calculation.

🔮 Individual Product Forecasts (Demand)

| Week          | 1   | 2   | 3   | 4   | 5   | 6   |
| ------------- | --- | --- | --- | --- | --- | --- |
| **Product A** | 70  | 70  | 70  | 70  | 70  | 80  |
| **Product B** | 40  | 40  | 40  | 40  | 95  | 120 |
| **Product C** | 50  | 50  | 50  | 100 | 50  | 50  |
| **Total**     | 160 | 160 | 160 | 210 | 215 | 250 |

This tells how many units are needed per product, per week.

🧩 MASTER SCHEDULE EXAMPLE (Proposed Plan)

| Week              | 1   | 2   | 3   | 4   | 5   | 6   |
| ----------------- | --- | --- | --- | --- | --- | --- |
| **Product A**     | 205 | 205 | 205 |     |     |     |
| **Product B**     |     |     |     | 205 | 205 |     |
| **Product C**     |     |     |     |     |     | 205 |
| **Total Planned** | 205 | 205 | 205 | 205 | 205 | 205 |

📌 Interpretation:

First 3 weeks: Focus is on Product A.
Weeks 4 & 5: Switch to Product B.
Week 6: All 205 units used for Product C.
This respects the weekly cap of 205 units.

This is just one way to schedule production — many alternatives are possible depending on constraints.


📙: Master Scheduling ++++++++++++++++++++++++++++++++++==IMP

📊 Inventory Table

| Week              | 1   | 2   | 3    | 4   | 5   | 6   |
| ----------------- | --- | --- | ---- | --- | --- | --- |
| **Product A**     | 280 | 210 | 140  | 70  | 0   | 125 |
| **Product B**     | 265 | 430 | 595  | 555 | 460 | 340 |
| **Product C**     | 0   | -50 | -100 | 55  | 210 | 160 |
| **Total Planned** | 545 | 640 | 735  | 680 | 670 | 625 |


This shows the inventory at the end of each week for each product, calculated as:

Inventory = Previous Inventory + Production - Forecast



⚖️ Evaluation of This Schedule

✅ Satisfactory:

Helps decide when to produce each product.
Meets weekly production capacity (total under control: ~625–735).

❌ Unsatisfactory:

Poor balance in inventory:
Product B is overstocked (stays high throughout).
Product C is understocked, with negative inventory in weeks 2 and 3 (meaning stockout or unmet demand).

This creates inefficiencies and potential customer dissatisfaction.


📦 Final Concept: Master Production Schedule (MPS)

MPS = Weekly schedule of which product is produced and how much.
The bottom line in the inventory table ("Total Planned") shows MPS totals.

The goal is to balance:

Inventory cost
Demand satisfaction
Production constraints (max capacity per week)

---------------------------------------------------------------------------------------------------------------------------------
PROBLEM 1: 

Great! Let's walk through the Example Problem from these images in detail. This problem is a practical illustration of how to create a Master Production Schedule (MPS) for two models—Model H and Model I—within given constraints.

🧩 Problem Statement Summary

Company: Hotshot Lightning Rod Company
Products: 2 models – H and I
Time Frame: 4 weeks

Total Monthly Forecasted Demand:
Model H = 700 units
Model I = 500 units
Total = 1200 units

📌 Constraints

| Item                        | Value                 |
| --------------------------- | --------------------- |
| Opening inventory (total)   | 500 units             |
| Ending inventory target     | 300 units             |
| Monthly Production Capacity | 1000 units            |
| Weekly Production Capacity  | 250 units             |
| Forecasts provided          | Weekly for both items |


🔢 Step-by-Step Breakdown

🧾 1. Total Production Planning

📊 Production Plan (Top Table)

| Week | Forecast | Projected Available | Production |
| ---- | -------- | ------------------- | ---------- |
| ---- | -------- | 500   --------------| ---------- |
| 1    | 300      | 450                 | 250        |
| 2    | 350      | 350                 | 250        |
| 3    | 300      | 300                 | 250        |
| 4    | 250      | 300                 | 250        |


✅ Now, let’s go to MPS of Model H:

| Week | Forecast | Projected Available | MPS |
| ---- | -------- | ------------------- | --- |
| ---- | -------- | 200 --------------- | --- |
| 1    | 200      | 250                 | 250 |
| 2    | 300      | 200                 | 250 |
| 3    | 100      | 350                 | 250 |
| 4    | 100      | 500                 | 250 |
|Total | 700



=================================================================================================================================

You're now studying the core process of developing a Master Production Schedule (MPS) — which balances demand forecasts, inventory levels, and production lot sizes. Let me explain both parts step by step.

“DEVELOPING A MASTER PRODUCTION SCHEDULE”

✅ Objective of MPS
MPS helps to:

Maintain customer service levels.
Minimize inventory investment.
Utilize resources effectively (labour, material, capacity).



🔧 PART 1: Preliminary Master Production Schedule

🧠 Example Given
Let’s understand this lot-based MPS example (Figure 3.1):

Given:

Forecast per period = 60 units
Lot size = 100 units
Opening inventory = 80 units

| Period                 |   | 1  | 2   | 3  | 4   | 5  | 6  |
| -----------------------|   | -- | --- | -- | --- | -- | -- |
| **Forecast**           |   | 60 | 60  | 60 | 60  | 60 | 60 |
| **Projected Available**|80 | 20 | 60  | 0  | 40  | 40 | 20 |
| **MPS**                |   |    | 100 |    | 100 | 100| 100|




Problem 4							
The Acme Tweezers Company makes tweezers in two models, medium and fine. The bottleneck operation is in work center 20. Following is the resource bill (in hours per dozen) for work center 20			Hours per Dozen				
		
        work centre	Medium	Fine			
		20	         0.5	1.2			
							
		MPS for 4 weeks					
		Week	1	2	3	4	Total
		Medium	40	25	40	15	120
		Fine	20	10	30	20	80
							
							
		Week	    1	2	     3	  4	      Total
		Medium	    20	12.5	20	 7.5	    60
		Fine	    24	12	    36	 24	        96
		Total hours	44	24.5	56	 31.5	    156


Problem 3.6								
The Acme Widget Company makes widgets in two models, and the bottleneck operation is in work center 10. Following is the resource bill (in hours per part).			Hours per Part					
		work centre	model A	Model B				
		10	2.5	3.3				
								
		Week	1	2	3	4	5	
		Model A	70	50	50	60	45	
		Model B	20	40	55	30	45	
								

(a)Using the resource bill and the master production schedule, calculate the number of hours required in work center 10 for each of the 5 weeks. Use the following table to record the required capacity on the work center		

        Week	       1	2	 3	    4	 5	
		Model A	     175	125	 125	150	 112.5	
		Model B	      66	132	 181.5	99	 148.5	
		Total hours	 241	257	 306.5	249	 261	
								
(b)  If the available capacity at work station 10 is 260 hours per week, suggest possible ways of meeting the demand in week 3								

=================================================================================================================================

🎯 What is Available to Promise (ATP)?
ATP = Inventory units available to promise to new customers without affecting existing commitments (customer orders).
It's used to determine whether new customer orders can be accepted in a given period.

🧮 ATP Formula
There are two main scenarios when calculating ATP:

🔹 Case 1: ATP in a week with MPS
If there is an MPS in a week, ATP is calculated as:

ATP
=
MPS in current week
−
∑
Customer Orders until next MPS
ATP=MPS in current week−∑Customer Orders until next MPS
Only include customer orders until the next MPS week.

🔹 Case 2: ATP in a week without MPS
ATP
=
0
ATP=0
No new production = nothing to promise.

✅ Step-by-Step Example
📊 Given:
Week	        1	2	 3	 4	 5
Customer Order	50	20	 30	 30	 15
MPS	            100		 100		

🔹 ATP Calculation:
Week 1:
MPS = 100

Next MPS is in Week 3

Customer Orders in Week 1 & 2 = 50 + 20 = 70
→ ATP = 100 - 70 = 30

Week 2:
No MPS → ATP = 0

Week 3:
MPS = 100

Next MPS = no further MPS in horizon

Customer Orders in Week 3, 4, 5 = 30 + 30 + 15 = 75
→ ATP = 100 - 75 = 25

Week 4 & 5:
No MPS → ATP = 0

✅ Final ATP Table (Original Case):
Week	           1	2	3	4	5
Customer Order	  50	20	30	30	15
MPS	              100		100		
ATP	              30		25		

🔁 Second Case: New Order for 30 units in Week 5
So now:

Week	           1	2	3	4	5
Customer Order	  50	20	30	30	45 ⬅️
MPS	             100		100		

🔁 Re-calculate ATP:
Week 1:
MPS = 100

Orders in Week 1 & 2 = 50 + 20 = 70
→ ATP = 100 - 70 = 30

Week 3:
MPS = 100

Orders in Week 3, 4, 5 = 30 + 30 + 45 = 105
→ ATP = 100 - 105 = −5, but we can't promise negative units
→ ATP = 0

Week 1 ATP: 30
→ We try to accept a new order of 30 units in Week 5
→ If accepted, Week 5 order becomes 15 + 30 = 45
→ Already seen, ATP from Week 3 becomes 0

✅ Final ATP Table (Updated):
Week	           1	2	3	4	5
Customer Order	  50	20	30	30	45
MPS	              100		100		
ATP	              25		0		

🟢 ATP is still non-negative → Yes, we can accept the new order
🔄 ATP in Week 1 is now:
→ ATP = 100 − (50 + 20 + 5) = 25

✅ Final Answer
Q: Can an order for 30 units in Week 5 be accepted?
✔️ Yes, it can be accepted.

New ATP Table (after order is accepted):

Week	1	2	3	4	5
ATP	   25		0		

✅ Summary of ATP Rules
Condition	Rule
MPS week	MPS − (Customer orders up to next MPS)
Non-MPS week	ATP = 0
Extra order	Subtract extra quantity from ATP
Negative ATP	Not acceptable (means over-promise)

=================================================================================================================================

Great! You're now working on Projected Available Balance (PAB) and Available to Promise (ATP) calculations — two critical components of Master Production Scheduling (MPS).

Let's break it down step-by-step with formulas, logic, and application for both parts of your problem

✅ PAB (Projected Available Balance)

🧠 Key Concepts

🔹 Demand Time Fence (DTF):
The number of weeks into the future where demand is considered firm (based on actual customer orders).

In your problem: DTF = end of Week 3

🔧 PAB Formulas:
Before DTF (Weeks 1 to 3)

PAB= Prior PAB (or On-Hand) + MPS − Customer Orders

After DTF (Weeks 4 onward)

PAB = Prior PAB + MPSM −max (Customer Orders, Forecast)


PROBLEM : 

Given the following data, calculate the projected available balance. The demand time fence is the end of week 3, the order quantity is 100, 40 are available at the beginning of the period.

prior PAB=40
MPS=100

PAB=Prior Period PAB or On-Hand Balance +MPS−Customer Orders(before Demand Fence)​
PAB=Prior Period PAB+MPS−max(Customer Orders, Forecast)(after demand Time fence)​
 
Week		                        1	   2	   3	  4	     5
Forecast		                    40	   40	   40	  40	40
Customer Order		                39	   42	   39	  33	23
Projected Available Balance	   40	1	   59	   20	  80	40
MPS		                            0	   100	          100	




Week		                              1	    2	   3	4	   5	6
Forecast		                          75	50	  30	40	   70	20
Customer Order		                      80	45	  40	50	   50	5
Projected Available Balance[50]           70	25	  85	35	   85	
ATP				                                      10		   45	
MPS		                                  100		  100		   100	


Step-by-Step ATP:
Week 1: MPS = 100
Customer Orders (Week 1 + 2) = 80 + 45 = 125
→ ATP = 100 − 125 = −25 ❌ Not feasible → likely a mistake in the table (must revise MPS or reject some orders)

But table shows ATP = 10 (assuming modified values):

Let’s assume:

Week 1 ATP = 10 (i.e. 100 – (80 + 10) → only 10 units left to promise)

Week 3: MPS = 100
Orders Week 3 to 4 = 40 + 50 = 90
→ ATP = 100 − 90 = 10

Table says ATP = 45 (maybe Week 3-6 cumulative order = 55 → 100 – 55)

