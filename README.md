# Wish.com [https://www.wish.com/]
## Define the problem
* The dataset is the wish.com product dataset
* the dataset has alot of noise and missing values and a lot of things need to data preprocessing
* **the problem is** i have some features for the product and i need to predict the product rating to help Wish.com to know if this priduct will be good for people or not to publish the product on the website or not 

---
# goal
* The goal is to predict product ratings based on other information available about a product on Wish.com. The rating range from 1 to 5. The higher the rating for a product, the more satisfied for the customers. When you have a new product to list on wish.com, you may use this model to predict how probable people will like it before actually listing it. Also , by doing so, we may better determine under what circumstances a product will be highly rated, as well as the wish.com consumer base.
# what is the input 
the input is the features of the product to predict the rating value but the model will select this features from the data input

* `price` : price for the buyer

* `retail_price `: Retail price, or reference price in other stores/places. Used by the seller to indicate a regular value or the price before discount.

* `currency_buyer` : currency of the prices

* `units_sold` : Number of units sold. Lower bound approximation by steps

* `uses_ad_boosts `: Whether the seller paid to boost his product within the platform (highlighting, better placement or whatever).

* `rating` : Mean product rating.

* `rating_count` : Total number of ratings of the product

* `badges_count` : Number of badges the product or the seller have.

* `badge_local_product` : A badge that denotes the product is a local product. Conditions may vary (being produced locally, or something else). Some people may prefer buying local products rather than. 1 means Yes, has the badge.

* `badge_product_quality `: Badge awarded when many buyers consistently gave good evaluations 1 means Yes, has the badge

* `badge_fast_shipping `: Badge awarded when this product's order is consistently shipped rapidly

* `tags` : tags set by the seller

* `product_color` : Product's main color

* `product_variation_size_id` : One of the available size variation for this product

* `product_variation_inventory` : Inventory the seller has. Max allowed quantity is 50

* `shipping_option_price `: shipping price

* `shipping_is_express` : whether the shipping is express or not. 1 for True

* `countries_shipped_to` : Number of countries this product is shipped to. Sellers may choose to limit where they ship a product to

* `inventory_total` : Total inventory for all the product's variations (size/color variations for instance)

* `has_urgency_banner` : whether there was an urgency banner with an urgency

* `merchant_rating` : merchant's rating
* `Merchant Has Profile Picture`: Indicates whether the merchant selling the product has a profile picture on the platform.
  
## ⚠ _ Note: Not all the columns are present in the above description


## What is the output?
the out put is the prediction `rating for the input product`

---------------------------------
## Just want to quickly look at some notebooks, without executing any code?

* <a href="https://github.com/AhemdMahmoud/Wish.com/blob/main/Wish_com.ipynb"><img src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg" alt="Render nbviewer" /></a>
