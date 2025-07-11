Given:

Starting Inventory (Week 1 Projected Available): 75 units
Gross Requirements:
Week 2: 50 units
Week 3: 45 units
Week 4: 20 units
Lead Time: 2 weeks
Lot Size: 100 units
Weeks: 1 to 4
 
Field	                             Week 1	     Week 2	     Week 3	   Week 4
Gross Requirements	                    0	      50	       45	     20
Projected Available	            75	              25	       55	     35
Net Requirements	                    0	      0	           0	      0
Planned Order Receipt	                0	      0	           0	      0
Planned Order Release	                0	      0	           0	      0


Field	                             Week 1	     Week 2	     Week 3	   Week 4
Gross Requirements	                    0	      50	       45	     20
Projected Available	            75	   75         25	       80	     60
Net Requirements	                    0	      	           20	      
Planned Order Receipt	                0	      0	           100	      0
Planned Order Release	               100	      0	           0	      0


Explanation:
Week 1: No gross requirement, so projected available remains 75.
Week 2: 50 units required → 75 - 50 = 25 units left.
Week 3: 45 units required → 25 - 45 = -20 → shortage of 20 units → Net Requirement = 20 → Order 100 units (lot size) → Receipt in Week 3 → Release in Week 1 (due to 2-week lead time).
Week 4: 20 units required → 100 (received in Week 3) - 20 = 80 units left.


=================================================================================================================================

Given:

Lead Time: 2 weeks
Order Quantity (Lot Size): 200 units
Gross Requirements:
Week 1: 50
Week 2: 250
Week 3: 100
Week 4: 50
Scheduled Receipt: 200 units in Week 2
Starting Inventory (Week 1 Projected Available): 150 units


| Field                   | Week 1 | Week 2 | Week 3 | Week 4 |
|------------------------|--------|--------|--------|--------|
| Gross Requirements     | 50     | 250    | 100    | 50     |
| Scheduled Receipts     |        | 200    |        |        |
| Projected Available    |        | 150    |        |        |
| Net Requirements       |        |        |        |        |
| Planned Order Receipt  |        |        |        |        |
| Planned Order Release  |        |        |        |        |


SOLUTION

Explanation:
Week 1:

Gross Requirement = 50
Projected Available = 150 - 50 = 100
No Net Requirement
Week 2:

Scheduled Receipt = 200
Gross Requirement = 250
Projected Available = 100 + 200 - 250 = 50
No Net Requirement
Week 3:

Gross Requirement = 100
Projected Available = 50 - 100 = -50 → shortage
Net Requirement = 50 → Order 200 units
Planned Order Receipt = Week 3
Planned Order Release = Week 1 (due to 2-week lead time)
Week 4:

Gross Requirement = 50
Projected Available = 150 (from Week 3 receipt) - 50 = 100
No Net Requirement


SOLVED
| Field                  | Week 1 | Week 2 | Week 3 | Week 4 |
|------------------------|--------|--------|--------|--------|
| Gross Requirements     | 50     | 250    | 100    | 50     |
| Scheduled Receipts     |        | 200    |        |        |
| Projected Available[150] 100    | 50     | 150    | 100    |        
| Net Requirements       |        |        | 50     |        |
| Planned Order Receipt  |        |        | 200    |        |
| Planned Order Release  | 200    |        |        |        |

=================================================================================================================================