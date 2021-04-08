Ecommerce-website
Technologies used:
HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
React: Components, Props, Events, Hooks, Router, Axios
Redux: Store, Reducers, Actions
Node & Express: Web API, Body Parser, File Upload, JWT
MongoDB: Mongoose, Aggregation
Development: ESLint, Babel, Git, Github,
Deployment: Heroku
Run Locally
1. Clone repo
$ git clone https://github.com/syed-ahmed-au9/mern-app
$ cd mern-app
2. Setup MongoDB
Local MongoDB
Install it from here
Create .env file in root folder
Set MONGODB_URL=mongodb://localhost/bestbuy
Atlas Cloud MongoDB
Create database at https://cloud.mongodb.com
Create .env file in root folder
3. Run Backend
$ npm install
$ npm start
4. Run Frontend
# open new terminal
$ cd frontend
$ npm install
$ npm start5. Seed Users and Products
Run this on chrome: http://localhost:5000/api/users/seed
It returns admin email and password
Run this on chrome: http://localhost:5000/api/products/seed
It creates 6 sample products
6. Admin Login
Run http://localhost:3000/signin
Enter admin email and password and click signin
