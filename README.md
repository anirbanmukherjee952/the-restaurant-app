# the-restaurant-app
An online restaurant management system application, where anyone wishes to order foods, first needs to sign in to the system. If the user doesn't have an account then he/she needs to sign up with the system. After signing in to the system the user can choose one or more items from the displayed menu, then he/she have to confirm his/her order and complete payment. On the other hand, the service provider restaurant on receiving the order will prepare the order and deliver to the user's home. This is basic overview of this app. Futher details are listed below.
# User classes
- **Customer:** Any person wishes to use our system to order foods online.
- **Delivery Boy:** An employee of the restaurant who will deliver food to customer.
- **Admin:** To keep everything simple the service provider restaurant is treated as single entity. There may exist several potential users like manager, cashier etc. but to avoid complications these users are treated as single user administrator. Admin is the entity who manages the entire system from receving customer's order to deliver them to customer's home.
# App features for customer:
- **Customer registration and authenticaton:** To use the system a customer needs to register with our system by providing his/her full name, present address, email address and password. All the entries need to be validated and proper message should be generated if some/all of the entries are invalid. After a successfull sign up customer can sign in to the system by providing email address and password.
- **Food-order placement:** After sign in a customer can choose one or more item(s) from menu and add it to the cart. The customer can delete/add item(s) from cart before confirming the order. Then customer has to make the payment. There should be one or more payment methods like cash, credit-card, debit-card, UPI.
- **Food-order cancellation:** Customer can cancel order anytime after he/she had placed an food-order. The money refund will depend on order status for an example if delivery boy is out for delivery and customer cancels order.
- **History navigation:** Customer can navigate thorough all the previous food orders he/she has made but can't delete it.
- **Status notification:** Customer should be notified about the status of the food-order processing e.g. order is accepted or order is out for delivery by messages and emails.
- **Feedback submission:** Customer can submit his/her feedback for each food-order he/she placed.
# App features for administrator:
- **Food-order management:** Admin can accept, reject incoming food orders and can assign delivery boy to deliver food-order.
- **Menu Management:** Admin can add, update, remove any of the food-items.
- **Delivery Boy Management:** Admin can add, update, remove any of the delivery boy profiles.
- **Discount Coupon Management:** Admin can add, update, remove discount coupons. An automated suggestions can be made from customers' purchase history about coupon offerings to the customer but it is offered to customer only if admin approves.
- **Sales report:** Automated sales reports are generated and displayed on admin's dashboard. These reports will help admin to gain insights about the business. List of these reports are mentioned below.
  1. Monthly, daily sales report.
  2. Popular food items.
  3. Customer feedback report.
# App features for delivery-boy:
- Delivery boy can sign in to the system and see what are the orders to deliver. 
- Delivery boy can see customer's location on virtual map after clicking on the order.  
