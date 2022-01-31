# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

#----Requirements-----#
    * Ruby version ~3.0.2
    * Rails version ~6.1.4
    * Node version (above 14)
    * Npm version ~8.3.0
    * Elastic-search
    * Redis (for action cabel)

#-------Deployment---------#
    * Just build Docker (command:- sudo docker-compose build)
    * Compose up the Docker (command:- sudo docker-compose up)
    * After composing up just create the database of the docker container in another terminal (command:- sudo docker-compose run web rails db:create RAILS_ENV=production)
    * Load the schema in the docker container (command:- sudo docker-compose run web rails db:schema:load)
    * To create admin load seed (command:- sudo docker-compose run web rails db:seed)

#-------Description about application-----#
    *Intro
        This is a shopping website named "Shopdrag" which helps user to buy different types of products like clothes, mobile, television etc and some 
        services like Massage,haircut,spa etc. ShopDrag is an interactive e-commerce solution providing almost all product and services in one place.
        There is no need to login or signup to view products in ShopDrag, in fact one can add products to cart without logging in, when they login with 
        their account then the product will automatically get added to their cart linked to their account.
        The registered customer can view, add the product to cart or can directly buy the product (without adding it to his/her cart). 
        He/she has to pay online to buy the product or service.
    
    *Roles
        1. Admin:-
                Admin can add/delete/edit Products, Product Variants, Product Services, Category and can manage Users.
                Admin can check and print stats of the total sale and total registered User.
                
        2. Seller:-
                Seller can manage their products/services only i.e they can add/delete/edit their Products, Product Variants, Product Services only.
                Seller can also check and print stats of their sale.

        3. Buyer:-
                A Buyer can add Product Variants,Product Services to their cart and also can buy them directly or from their cart.A buyer can also 
                search Products/Product Services, add unavailable products in their wishlist.



* ...
#   O n l i n e - S t o r e 
 
 