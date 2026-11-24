
DAY 1

## CREATING THE CLASS

Class: Inventory Item

Attributes:
name: item name
quantity: how many units 
category: Produce, Protein, Dair, or Dry Goods
low_stock_threshold: 10 units 

Methods:
__init__: to initialize the attribues 
is_low_stock: checks if quantity is less than 10 


## First Three Lines - Manual Trace

**Starting inventory:** Empty

| Line | Item | Quantity | Valid? | Result |
|---|---|---|---|---|
| 1 | Roma Tomatoes | 48 | Yes | Create item with 48 units |
| 2 | Yellow Onions | 15 | Yes | Create item with 15 units |
| 3 | Chicken Breast | 9 | Yes | Create item with 9 units; flag low stock |

**Conclusion:**
All three ADD transactions are valid.
Each creates a new inventory item.
Chicken Breast is low stock because its quantity is below 10.

