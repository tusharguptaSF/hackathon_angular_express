# OrganicWorld

## Problem Statement

Organic World have started business in 2013 as a organic food store. It started in a 100 sqft store at Detroit. Because of high quality products, resonable price and steady supply the store became popular, currently operates with twenty stores in Detroit and planning to open multiple stores across the country.

Organic World wants to digitize their operation. The objective of Organic world is to create a brand of itself and increase their customer volume.

## Proposed Solution

In order to increase their product consumers Organic world needs a solution that will help to reach out to users over the Web for buying their products.

## HIGH LEVEL REQUIREMENTS

- All webpages should have NavigationBar to move through the website easily. The navigation bar should consisit of a logo of the brand, search input and three buttons ‘Home’, ‘Login’, ‘Products’ and ‘Cart’ where Products Button is a dropdown with different categories of products and login is a modal with.
- All webpages also consist a footer which consist links to all webpages to access quickly and social media icons to connect through social medias.
- The landing page should consist of A carousel of products and a multi column layout below which consist of info about the company and partners.
- The Product page should display the account dropdown button with logout, list of products in a card grid format of tree cards per row. Every card should consist of Quantity, ‘Add to cart’ buttons.
- The Account page should consist of information about the user which can be updated by user.
- The cart page should consist of list of products added and their quantities and price in a table format and features like delete a product, update a product quantity,also a checkout button.
- Use Express to create the backend of the application.
- postgrew as database should be used 

## The roles in this application are

- Customer: View differents products available in store and buy directly through online transaction

## TECH STACK

- Angular8
- Material
- Jasmine
- Protractor
- nodejs
- express
- typescript
- postgres

## API ENDPOINTS
  
  1. For the products
     - GET    - http://localhost:3000/products/all          - get all products
     - GET    - http://localhost:3000/products/{category}   - get products in a category  
     - GET    - http://localhost:3000/products/search/{id}  - get a particular product

  2. For Order
     - POST   - http://localhost:8761/orders                - save a new order
     - GET    - http://localhost:8761/orders?customerId=    - get a customer orders


