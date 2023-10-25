### Product Operations

| Operation       | Description                                      | RESTful API Endpoint                 | HTTP Method |
|-----------------|--------------------------------------------------|--------------------------------------|-------------|
| Create Product  | Create a new product                             | `/products`                          | POST        |
| Read Product by ID | Retrieve details of a specific product by productID | `/products/{productID}`             | GET         |
| Update Product  | Update the details of an existing product by productID | `/products/{productID}`             | PUT         |
| Delete Product  | Delete a product by productID                   | `/products/{productID}`             | DELETE      |
| Search Products by Name | Search for products by product name and retrieve details | `/products/search?name={productName}` | GET         |
| Search Products by Price Range | Search for products within a price range | `/products/search?minPrice={minPrice}&maxPrice={maxPrice}` | GET |

### Order Operations

| Operation       | Description                                      | RESTful API Endpoint                 | HTTP Method |
|-----------------|--------------------------------------------------|--------------------------------------|-------------|
| Create Order    | Create a new order                               | `/orders`                            | POST        |
| Read Order by ID | Retrieve details of a specific order by orderID | `/orders/{orderID}`                 | GET         |
| Update Order    | Update the details of an existing order by orderID | `/orders/{orderID}`                 | PUT         |
| Delete Order    | Delete an order by orderID                       | `/orders/{orderID}`                 | DELETE      |
| Search Orders by Total Cost Range | Search for orders within a total cost range | `/orders/search?minCost={minCost}&maxCost={maxCost}` | GET |
| Search Orders by Date Range | Search for orders within a date range | `/orders/search?startDate={startDate}&endDate={endDate}` | GET |

### User Operations

| Operation       | Description                                      | RESTful API Endpoint                 | HTTP Method |
|-----------------|--------------------------------------------------|--------------------------------------|-------------|
| Create User    | Create a new user                               | `/users`                            | POST        |
| Read User by ID | Retrieve details of a specific user by userID   | `/users/{userID}`                   | GET         |
| Update User    | Update the details of an existing user by userID | `/users/{userID}`                   | PUT         |
| Delete User    | Delete a user by userID                         | `/users/{userID}`                   | DELETE      |
| Get User by Username | Retrieve details of a specific user by username | `/users/search?username={username}` | GET         |

### Credit Card Operations

| Operation           | Description                                      | RESTful API Endpoint                 | HTTP Method |
|---------------------|--------------------------------------------------|--------------------------------------|-------------|
| Create Credit Card  | Create a new credit card for a user              | `/creditcards`                       | POST        |
| Read Credit Card by CreditCardID | Retrieve details of a specific credit card by creditCardID | `/creditcards/{creditCardID}` | GET |
| Update Credit Card  | Update the details of an existing credit card by creditCardID | `/creditcards/{creditCardID}` | PUT |
| Delete Credit Card  | Delete a credit card by creditCardID              | `/creditcards/{creditCardID}` | DELETE |
| Get Credit Card by OrderID | Retrieve details of a credit card based on an orderID | `/creditcards/search?orderID={orderID}` | GET |


