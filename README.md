# Broker
Programmatic buy and sell company


Farmer :
	1. Register in system
	2. Select category which he want to sell
	3. If prime-subscriber then can see price offerred by all buyer
	4. Upload details - quantity / min-price / images/videos delivery-time
	5. Provide time for the quality-check team 
	6. View price offerred by buyers and decides whom to send.
	7. Helps delivery team to pick-up and measure weights
	8. Gets the payment
	
	/register 
		- unique-id 
		- mobile , address, email
		- ID proof - Aadhar-ID 
	
	/login
		- InProgress items.
		- History 
	/view-category
	/upload 
		- Approx weight , Min-price , images , videos 
		- date & time for quality check 
	/edit 
		- edit the item details = weight/images/videos/min-price 
	/delete 
		- delete if dont want to sell items 
	/view-price 
		- view price offered by multiple buyer 
	/choose
		- choose buyer 
		
		

Buyer :
	1. Register 
	2. select category to buy 
	3. Views all available sellers and their items
	4. select seller and shares the price { assume = all quantity should be bought }
	5. Makes payment 
	6. Wait for delivery team to deliver 
	
Delivery-Team 
	1. Register - share vehicle details & identity
	2. View available sellers location and  item + quantity 
	3. Measure weight of items and loads the vehicle 
	4. Update in system
	5. Delivers to buyer 

Quality-Check-Team :
	1. Register 
	2. Go-to Farmer location and confirms the quality & provide expert opinion
	3. Set the details/rating in system
