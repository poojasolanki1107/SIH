# Farm2Fork

This project is mainly aimed to give complete traceability of food from farmers to consumers.
Customers are unaware of the conditions the food has been from seeding to harvesting to transporting until the final destination
i.e the customer.

The project consists of 3 UI's for farmers,middlemen and customers.

# Farmer
The farmer regsiters himself in the web app by either filling out the registration form himself/herself or using the Qrcode scan feature
which scans the Qrcode on Aadhar card (Unique Identity card for each citizen) which fills the form automatically.
Once he/she is dine with it, he/she inputs the crop he/she wants to grow. The app provides the quantity of various required fertilizers,
pesticides which is required by the crop.
After the crop is harvested he makes transaction with the middleman

# Middleman
From here a Qrcode is generated for each box of the food with all the information like anount of fertilizer and pesticides used, the farmer's name
,seeding to harvesting time period etc.

# Customer
The customer can scan the Qrcode present on the box to get all the information related to the product.
Also, the product might turn out to be defective or bad quality, so he can report the same.
After reporting a counter is incremented for all those places the food has been, i.e farmer, middlemen (can be multiple),etc. Like this
after a threshold value is reached we can tell the source of contamination.
