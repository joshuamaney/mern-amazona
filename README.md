# MERN AMAZONA

# Lessons

1. Introduction
2. Install Tools
3. Create React App
4. Create Git Repository
5. List Products
   - create products arrazy
   - add product images
   - render products
   - style products
6. Add Routing
   - npm i react-router-dom
   - create route for home screen
   - create router for product screen
7. Create Node.JS Server
   - npm init in root folder
   - Update package.json set type: module
   - add .js to imports
   - Create server.js
   - add start command as node backend/server.js
   - require express
   - create route for / return backend is ready
   - move products.js from frontend to backend
   - create route for /api/products
   - return products
   - run npm start
8. Fetch Products From Backend
   - set proxy in package.json
   - npm install axios
   - use state hook
   - use effect hook
   - use reducer hook
9. Manage State By Reducer Hook
   - define reducer
   - update fetch data
   - get state from useReducer
10. Add Bootstrap UI Framework
    - npm i react-bootstrap bootstrap
    - update App.js
11. Create Product and Rating Component
    - create Rating component
    - create Product component
    - Use Rating component in Product component
12. Create Product Details Screen
    - fetch product from backend
    - create 3 columns for image, info, and action
13. Create Loading and Message Component
    - create loading component
    - use spinner component
    - create message component
    - create utils.js to define getError function
14. Implement Add To Cart
    - Create React Context
    - define reducer
    - create store provider
    - implement add to cart button click handler
15. Complete Add To Cart
    - check exist item in the cart
    - check count in stock in backend
16. Create Cart Screen
    - create 2 columns
    - display items list
    - create action column
17. Complete Cart Screen
    - click handler for inc/dec item
    - click handler for remove item
    - click handler for checkout
18. Create Sign-in Screen
    - create sign-in form
    - add email and password
    - add sign-in button
19. Connect to MongoDB Database
    - option 1 create atlas mongodb database
    - option 2 install local mongodb database
    - npm i mongoose
    - connect to mongodb database
20. Seed Sample Data
    - create Product model
    - create User model
    - create seed route
    - use route in serve.js
    - seed sample product
21. Seed Sample Users
    - create User model
    - seed sample users
    - create user routes
22. Create Sign In Backend API
    - create sign in api
    - npm i jsonwebtoken
    - define generateToken
23. Complete Sign In Screen
    - handle submit action
    - save token in store and local storage
    - show user name in header
24. Create Shipping Screen
    - create form inputs
    - handle save shipping address
    - add checkout wizard bar
25. Create Sign Up Screen
    - create input forms
    - handle submit
    - create backend api
26. Implement Select Payment Method Screen
    - create input forms
    - handle submit
27. Create Place Order Screen
    - show cart items, payment and address
    - handle place order action
    - create order create api
28. Implement Place Order Action
    - handle place order action
    - create order create api
29. Create Order Screen
    - create backend api for order/:id
    - fetch order api in frontend
    - show order information in 2 columns
30. Pay Order By PayPal
    - generate paypal client id
    - create api to return client id
    - install react-paypall.js
    - use PayPalScriptProvider in index.js
    - use usePayPalScriptReducer in Order Screen
    - implement loadPayPalScript function
    - render paypal button
    - implement onApprove payment function
    - create pay order api in backend
31. Display Order History
    - create order screen
    - create order history api
    - use api in the frontend
32. Create Profile Screen
    - get user info from context
    - show user information
    - create user update api
    - update user info
33. Publish to Heroku
    - create and config node project
    - serve build folder in frontend folder
    - create heroku account
    - connect it to github
    - create mongodb atlas database
    - set database connection in heroku env variables
    - commit and push
