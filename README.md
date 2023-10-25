# REST API Design : UIN: 234008952
All the element operations have the basic CRUD (Create, Read, Update, Delete). Apart from this a few more relevant operations are mentioned.
Create -> POST  
Read -> PUT  
Delete -> DELETE  
Update -> PUT  

# Product Operations

| Operation       | Description                                      | RESTful API Endpoint                 | HTTP Method |
|-----------------|--------------------------------------------------|--------------------------------------|-------------|
| Create   | Create a new product. Product data in HTTP request body. Product details HTTP request body.                        | `/products`                          | POST        |
| Read  | Retrieve details of a specific product by productID | `/products/{productID}`             | GET         |
| Update   | Update the details of an existing product by productID. Product details in HTTP request body | `/products`             | PUT         |
| Delete   | Delete a product by productID.          | `/products/{productID}`             | DELETE      |
| Search Products by Name | Search for products by product name and retrieve details. | `/products/search?name={productName}` | GET         |
| Search Products by Price Range | Search for products within a price range | `/products/search?minPrice={minPrice}&maxPrice={maxPrice}` | GET |

# Order Operations

| Operation       | Description                                      | RESTful API Endpoint                 | HTTP Method |
|-----------------|--------------------------------------------------|--------------------------------------|-------------|
| Create | Create a new order. Order details in HTTP request body.                               | `/orders`                            | POST        |
| Read  | Retrieve details of a specific order by orderID | `/orders/{orderID}`                 | GET         |
| Update | Update the details of an existing order by orderID. Order details in HTTP request body | `/orders`                 | PUT         |
| Delete | Delete an order by orderID                       | `/orders/{orderID}`                 | DELETE      |
| Search Orders by Total Cost Range | Search for orders within a total cost range | `/orders/search?minCost={minCost}&maxCost={maxCost}` | GET |
| Search Orders by Date Range | Search for orders within a date range | `/orders/search?startDate={startDate}&endDate={endDate}` | GET |

# Credit Card Operations

| Operation           | Description                                      | RESTful API Endpoint                 | HTTP Method |
|---------------------|--------------------------------------------------|--------------------------------------|-------------|
| Create | Create a new credit card for a user. Credit card details in HTTP request body              | `/creditcards`                       | POST        |
| Read | Retrieve details of a specific credit card by creditCardID | `/creditcards/{creditCardID}` | GET |
| Update | Update the details of an existing credit card by creditCardID. Credit card details in HTTP request body. | `/creditcards` | PUT |
| Delete | Delete a credit card by creditCardID              | `/creditcards/{creditCardID}` | DELETE |
| Search Credit Card by OrderID | Retrieve details of a credit card based on an orderID | `/creditcards/search?orderID={orderID}` | GET |


# User Operations

| Operation       | Description                                      | RESTful API Endpoint                 | HTTP Method |
|-----------------|--------------------------------------------------|--------------------------------------|-------------|
| Create | Create a new user. User details in HTTP request body.                               | `/users`                            | POST        |
| Read | Retrieve details of a specific user by userID   | `/users/{userID}`                   | GET         |
| Update | Update the details of an existing user by userID. User details in HTTP request body. | `/users`                   | PUT         |
| Delete | Delete a user by userID                         | `/users/{userID}`                   | DELETE      |
| Get User by Username | Retrieve details of a specific user by username | `/users/search?username={username}` | GET |



