# react-complete-e-commerce

## Repository for my react-complete-e-commerce project

A complete e-commerce platform using CRUD functions and connects the system to a database of MongoDB (Document database). Created a full-stack platform using JavaScript. The frontend was created using React and the backend was created using NodeJS, Express, MongoDB. Then I used Axios and Redux to link my backend with my frontend. I also used Postman to test my end points. 

 Programming Languages/Frameworks:
   - JavaScript
   - React
   - Redux
   - NodeJS
   - Express
   - MongoDB
   - Postman
   - Axios


### Home Page

![Home Page](screenshots/home.png 'Home Page')

### Search Page

![Search Page](screenshots/search.png 'Search Page')

### Product Page

![Product Page](screenshots/product-screen.png 'Product Page')

### Cart Page

![Cart Page](screenshots/cart.png 'Cart Page')

### Place Order Page

![Place Order Page](screenshots/place-order.png 'Place Order Page')

### Make Payment Page

![Make Payment Page](screenshots/make-payment.png 'Make Payment Page')

### My Order Page

![My Order Page](screenshots/my-order-screen.png 'My Order Page')

### Admin Users Page

![Admin Users Page](screenshots/admin-users.png 'Admin Users Page')

### Admin Products Page

![Admin Products Page](screenshots/admin-products.png 'Admin Products Page')

### Admin Orders Page

![Admin Orders Page](screenshots/admin-orders.png 'Admin Orders Page')

## Instructions

1. Make sure you have these installed

   - [NodeJS](https://nodejs.org/en/download/ "NodeJS")
     
   - [MongoDB](https://www.mongodb.com/try/download/community "MongoDB")
     
   - [Postman](https://www.postman.com/downloads/ "Postman")
     

2. Clone this repository into your local machine using the terminal 

   ```
   > git clone https://github.com/mohamedmostafa13/e-commerce3.git
   ```

3. backend setup (DO NOT cd to backend) (running on port you decide)

   ```
   > npm install
   ```

4. frontend setup (running on port 3000)
   ```
   > cd frontend
   ```

   ```
   > npm install
   ```

5. Insert data into the MongoDB database
   - Start MongoDB server
      ```
      > mongod
      ```

   - Enter mongo shell
      ```
      > mongo
      ```

   - Insert data into the MongoDB database
      ```
      > npm run data:import
      ```

6. Rename .env-example to .env
   and set these values
   ```
    NODE_ENV = development
    PORT = <>
    MONGO_URI = <>
    JWT_SECRET = <>
    PAYPAL_CLIENT_ID = <>
   
   ```
7. Runs both frontend and backend (cd to ROOT of project)
   ```
   > npm run dev
   ```

 Enjoy!

