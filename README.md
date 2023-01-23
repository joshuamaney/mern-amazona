# MERN AMAZONA

# Lessons

1. Introduction
2. Install Tools
3. Create React App
4. Create Git Repository
5. List Products
   1. create products arrazy
   2. add product images
   3. render products
   4. style products
6. Add Routing
   1. npm i react-router-dom
   2. create route for home screen
   3. create router for product screen
7. Create Node.JS Server
   1. npm init in root folder
   2. Update package.json set type: module
   3. add .js to imports
   4. Create server.js
   5. add start command as node backend/server.js
   6. require express
   7. create route for / return backend is ready
   8. move products.js from frontend to backend
   9. create route for /api/products
   10. return products
   11. run npm start
8. Fetch Products From Backend
   1. set proxy in package.json
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook
9. Manage State By Reducer Hook
   1. define reducer
   2. update fetch data
   3. get state from useReducer
10. Add Bootstrap UI Framework
    i. npm i react-bootstrap bootstrap
    ii. update App.js
11. Create Product and Rating Component
    i. create Rating component
    ii. create Product component
    iii. Use Rating component in Product component
12. Create Product Details Screen
    i. fetch product from backend
    ii. create 3 columns for image, info, and action
13. Create Loading and Message Component
    i. create loading component
    ii. use spinner component
    iii. create message component
    iv. create utils.js to define getError function
14. Implement Add To Cart
    i. Create React Context
    ii. define reducer
    iii. create store provider
    iv. implement add to cart button click handler
15. Complete Add To Cart
    i. check exist item in the cart
    ii. check count in stock in backend
16. Create Cart Screen
    i. create 2 columns
    ii. display items list
    iii. create action column
