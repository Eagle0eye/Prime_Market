# Prime_Market
**Prime Market** is a local hypermarket chain with multiple branches. It offers a wide range of products, from fresh local produce to household essentials. Known for its strong community ties and personalized service, Prime Market ensures high-quality goods at competitive prices, making it a preferred shopping destination in the area.

1 - Management System
2 - Branch System
3- Cashier System

# Branch System Requirements:
## Roles:
    - A Manager: the person responsible for the branch.
    - An Assistant: supports the manager and has most of his responsibilities.
    - A Shift: takes care of the client, provides their needs, and handles the stocks.
    - A Staff: helps clients to find products and suggests offers 

## Notes:
    - Everyone in the branch can work as a cashier using his secret key to do operations.
    - there are 2 shifts in the branch.
    - Everyone has his shift.
    - 
## Processes:   
    1- view crew.
    2- A manager determines the crew for the two shifts.
    3- A manager follows up on daily attendance.
    4- A manager can update the price of products.
    5- 
    6-  

### 1- Making Purchase steps:
    1- 


### 2- Refunding Purchase steps:
    1- 

### 3- A View Products:
    1- 


### 4- view the total payments:
    1- 



### 5- Ending the daily total payments:
    1- 

### 6- search for receipts:
    1- 


# Cashier System Requirements:
## Internal Requirements:
    - A user must enter his secret key to do any process.
    - provide payment methods via (visa/master card,  value, or cash).
    - the new day is calculated from the previous end.   

## Processes:   
    1- make purchases.
    2- refund purchases.
    3- view products and offers and their prices.
    4- view the total payments during the day.
    5- the assistant or the manager only can end the daily total payments.
    6- search for receipts by their serial number. 

### 1- Making Purchase steps:
    1- A users select a Purchase.
    2- Select Create.
    3- the system required the user code to complete
    4- the user enters the code.
    5- scan product QR with a QR reader.
    6- select payment method.
    7- (optional step): add promo code to discount the total price.
    8- confirm the payments.
    9- print a receipt.
    10- give the receipt to the client.
    11- return the page of user receipts that have been completed by him per day.
    12- Select Add to another purchase.


### 2- Refunding Purchase steps:
    1- A users select a Purchase.
    2- select refund.
    3- type the serial of the receipt until the date is no longer than 14 days ago if not the system automatically refuses the process.
    4- the system required the user code to complete
    5- the user enters the code.
    6- view the items of receipt.
    7- the user can update or delete items depending on their status.
    8- once any updates happen, the user refunds the money to the client.
    9- print the same serial number on a receipt with its modifications.

### 3- A View Products:
    1- A users select Products and Offers.
    2- view the products and offers.
        - A user can get unit prices using a QR reader.
        - A user can search by: (unit serial number - title).


### 4- view the total payments:
    1- A users select total payments.
    2- The system required the user code to be completed.
    3- check the number of receipts and their prices.
    4- check the amount of the money in the locker that equals the total price.
    5- show the successful purchases, refunded, and canceled.




### 5- Ending the daily total payments:
    1- A users select total payments.
    2- the system required the user code to complete.
    3- review the payments and receipts.
    4- click on Confirm to end the day.
    5- the system required the secret key of his branch manager or assistant only to complete ending of the day.
    6- store the time and the date at the moment that the process is completed.

### 6- search for receipts:
    1- A users select search.
    2- the system required the user code to complete.
    3- type the serial of the receipt to search
    3- A user can search by date (from 00/00/0000 to 00/00/0000)
    4- A user can search by time (from 00:00:00 to 00:00:00)
