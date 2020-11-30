# Food Ordering System

How To Install -
---------

1. Create Database food.
2. Run food.sql script provided in sql folder.
3. Go to login.php and try out our application. Sample user credentials can be found in users & wallet_details table.

Note -
---------
.In table `users` store The username and password of sample users as in sql file.
. Customers with "Verified" status can only place orders using "Cash on Delivery" option.
. A new customer By default gets 2000 coins in Wallet on signing up, and a dummy Credit card details is generated and stored in SQL Table "wallet_details" with corresponding new customer's ID.
. THey can then use that Card Number & CVV while placing an order, else order won't be successful or use "Cash on delivery" option.
. What's lacking? Dynamic payment(real payment system) and error reporting lacks in this project. And also one might wish for showing corresponding food item's photo and all that stuff.
