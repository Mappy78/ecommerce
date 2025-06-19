# ecommerce

a simple spring boot project that implements E-Commerce Order System.

description: users can buy a product with a coupon. that's it. there are no detailed implements of payment or products. 

business scope: online shopping center 

domain models
entities
- user
- product
- coupon
- order: orderItem list. cal total cost.
- orderItem: buying product by quantity with coupon

business services
- orderProduct
- calculateDiscount
