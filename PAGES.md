## Login / Register page
It will have a login page, asking for the user email and user password. It will also have a 'REGISTER' button. That will lead directly to the /register page, asking for the user name, email and password.  
The user's info will be stored in a different database.  

## Search restaurant page
The index '/' page will be the main / home page, it will have a search for restaurant input, and the promotions of the day, on the bottom.  
The index shouldn't ask for the user login, but if the user search for a restaurant, it should track the position on where the user must be logged in in order to continue.  

## Choose items page
The /restaurant/items page will be the page where the user chooses it's food, such as: '5 apples, 2 oranges, 1 pineapple, 8 coconuts'.  
It will have a count up menu, such as:
```javascript
Apples [0]: +
```
The '+' will be a button, and will increase the amount of apples the user wants to buy.

## Finish order page
The last page before the payment. Will show the total amount of products in a list. It will also show the total amount of money R$.  
It will also show the payment options, and 3% discount on credit card.  

# Payment page
I still don't know much of this page yet, since I've never used a payment api before.  
TODO ...