# Wish.com 
## Define the problem
* The dataset is the wish.com product dataset
* the dataset has alot of noise and missing values and a lot of things need to data preprocessing
* **the problem is** i have some features for the product and i need to predict the product rating to help Wish.com to know if this priduct will be good for people or not to publish the product on the website or not 

---
# goal
* The goal is to predict product ratings based on other information available about a product on Wish.com. The rating range from 1 to 5. The higher the rating for a product, the more satisfied for the customers. When you have a new product to list on wish.com, you may use this model to predict how probable people will like it before actually listing it. Also , by doing so, we may better determine under what circumstances a product will be highly rated, as well as the wish.com consumer base.
# what is the input 
the input is the features of the product to predict the rating value but the model will select this features from the data input
* `Price`: The amount of money charged for a product on the Wish platform.

* `Retail Price`: The standard or suggested retail price for the product, often used for comparison with the discounted price on Wish.

* `Units Sold`: The number of units of the product that have been sold on the Wish platform.

* `Uses Ad Boosts`: Indicates whether the product listing utilizes advertising boosts to increase its visibility on the Wish platform.

* `Rating`: The average rating given to the product by customers who have purchased and reviewed it.

*` Rating Count`: The total number of ratings and reviews received for the product.

*` Badges Count`: The number of badges or certifications associated with the product, indicating certain attributes like quality or fast shipping.

* `Badge Product Quality`: A badge indicating the perceived quality of the product.

*` Badge Fast Shipping`: A badge indicating that the product comes with fast shipping options.

* `Product Color`: The color or colors available for the product.

*` Product Variation Size ID`: An identifier for different sizes or variations of the product.

*` Product Variation Inventory`: The quantity of each size or variation available in stock.

* `Shipping Option Price`: The cost of shipping the product to the buyer.

* `Has Urgency Banner`: Indicates whether the product listing includes an urgency banner, often used to create a sense of urgency for potential buyers.

* `Origin Country`: The country where the product is manufactured or sourced from.

* `Merchant Rating Count`: The total number of ratings and reviews received by the merchant selling the product.

* `Merchant Rating`: The average rating of the merchant selling the product.

* `Merchant Has Profile Picture`: Indicates whether the merchant selling the product has a profile picture on the platform.


## What is the output?
the out put is the prediction `rating for the input product`

---------------------------------
## Just want to quickly look at some notebooks, without executing any code?

* <a href="https://github.com/AhemdMahmoud/Wish.com/blob/main/Wish_com.ipynb"><img src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg" alt="Render nbviewer" /></a>
