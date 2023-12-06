
# Menu-Ordering App

## Description

This is a basic program allowing a user to order
from one of 4 categories:
- Snacks
- Meals
- Drinks
- Dessert

Each category has multiple sub-options for a
 user to order, and includes price. 
 
The user will then be prompted to input a
 quantity for the ordered item.
 
 Finally, the user will be asked if they want
  to continue ordering more items or end the 
  order.
  
After an order is completed, the user will be 
  shown their complete order, including the
  price of each item, the quantity of each 
  item, and the total cost for the order. 
  
## Step-by-step

After starting the program, follow the on-screen prompts:
1. Choose a menu category by entering the corresponding number.
2. Select a menu item by entering the item number.
3. Specify the quantity of the selected item.
4. Continue ordering or complete your order.
5. Review your total order summary.  

### Outside Code Used:
Line 145:
    "Form a unique key for each item to avoid collisions"
    item_key = f"{menu_category_name} - {customers_choice['Item name']}"
    
The above code was sourced from ChatGPT to solve an issue where ordering the same menu *item* from a different *category* caused
an issue where the quantity of the second item was added to the first item, and the second item was never added to the 
"order_list" dictionary.

## Customization
The menu items and prices can be customized by editing the "menu" dictionary in the program file. Each key-value pair represents a
category and its items.


## Dependencies
- Python 3.x

## Author
Jake Lee
