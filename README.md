# SApp - Shopping Assistant Application

## Overview
Idea is to develop shopping assistant, which will help you manage your shopping list. More extensive description of application is presented below.

## Idea
Application lets you make shopping list. You can add products to list, share list with other people, like family members. Every person who has access to list can view and add new items to list. When you go shopping you can cross out products from list. Products will be crossed out, but you can still see them until you hit “Finished shopping” button which will remove bought items.

You can also create shops. When you go to specific shop, and cross out products application will remember order in which you cross them out, so next time you go to that specific shop it will display items in that particular order, so you won’t waste time searching what you should buy. You can have multiple shops and order of products will depend on choosed shop. Of course if you can always display products in alphabetical order.  It’s also possible to change the order of products for specific shop manually. Remember! You can always share your shop map with your friends!

Other useful feature is adding products to categories. You can add one product to multiple categories. You can view your list by categories. So if you are in for example new shop and you enter vegetables section, then you can view vegetables and then you will see only vegetables, so you can grab them at once. 

In feature I am planning to implement voice support for listing products and adding products to list, so you can open your fridge, look what you need and just list those products aloud and application will add them to list automatically. 

## Key Functions:
* Ability to create account, login
* Ability to create list and share it with others
* Adding and removing products from the list
* Creating shop map and share it with others
* Sorting products by shop (choose shop) 
* Assigning categories to products
* Filtering by category
* Finishing shoping (removing crossed out items)

## Technologies:
* Neo4j - rest of data
* Postgresql - user specific data
* Spring stack (Boot, Data, Security)
* Thymeleaf/Vue.js
* Docker
