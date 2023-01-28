SHIP-EZ DOCUMENTATION


PROBLEM STATEMENT

In any shipment system, there are multiple parties involved: the producer, the consumer, and the mediator. Goods are stored in the warehouses of these three parties. An efficient warehousing system helps to maximise and optimise all the space, lean inventory, optimise labour efficiency and organise workstations by adopting modern technology and automation.




DEV CYCLE and TECH FLOW

Let us divide our dev cycle into 3 different parts.
1. The Frontend
2. Machine Learning model training and implementation 
3. The Backend
We started our project journey with training our ML model with linear regression which estimates the cost freight based on various structures like quantity, volume, category and distance

With that we parallelly worked on the front and the backend,

The frontend is a unique eye-catching yet completely responsive interface which starts with an informative - what-do-we-do home page which also directs you to our Login and Create Account Page which is completely secured by our firebase authentication.
Upon successful Login and registration you are directed to our well designed dashboard page which allows you to enter data (as a logged in business) to the number of warehouses you have and their locations, and also allows you to enter the data of the items with their quantity present within those warehouses. Upon complete addition of data to the database you are led on to the “Shipping page” where you get an input illustrative form which allows you to enter the warehouse from where you want to send the item, the item information and to which business you are sending to.
After receiving all the information we use OUR ML MODEL TO PROVIDE YOU THE ESTIMATE SHIPPING COST it will take you to send the item from desired input and output locations.

The backend manages all the required databases and provides the front end with all the useful APIs for the integration of the complete project.
The DB’s managed by the backend are - Login/Warehouse/Item/Business/Distance and provides us with the following APIs
1. GET warehouses
2. POST warehouses
3. GET Items
4. POST Items
5. POST Distance 
6. POST Login 
7. POST Cost Estimation API for ML model. 

