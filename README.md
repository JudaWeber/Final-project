 # Final project - HackerU final project

Welcome to my E-Commerce Hacker-U project. This is a fullstack project built from scratch with frontend and backend, fully responsive to all mobiles and PC.

### Install node_modules:
`npm i`

### In order to run server side:
## `npm run dev`

- Runs the app with nodemon
- The page will reload if you make edits
- The print at the terminal will be purple with the message:

`server run on: http://:localhost : 8181`

And if there are no login errors you should see the message painted in purple:

`connected to MongoDb!`

### In order to run client side:
`npm start`
- `server run on: http://:localhost : 8282`

## Postman requests documentation of my project:
https://documenter.getpostman.com/view/23238664/2s93eVYEcz

### Technologies used to create the Backend:
* Node.js
* mongoose
* dotend
* bcryptjs
* multer
* morgan
* express.js

### Technologies used to create the Frontend:
* React
* Bootstrap
* CSS
* joi-browser
* axios
* React-Bootstrap
* toastify
* JavaScript



### Login as admin example:
- Email: admin@gmail.com
- Password: 123456aA!

### Login as user example:
- Email: user@gmail.com
- Password: 123456aA!


There are two types of users - admin and normal user.
#### As normal user:
A normal user can add,edit, and remove items from cart.

#### As admin user:
An admin has the ability to manage by creating new products, editing or deleting existing products, change user type (to admin), delete users.

## Frontend:

#### Header - Navigation bar
The header section includes all the links and options necessary for users to navigate the website easily, such as search bar, login and registration.

#### Add new product
Using the admin panel, an admin can create a new product by providing details such as the product name, image, price,and description, ensuring that customers have all the necessary information before making a purchase.

#### Register
The registration process involves the user entering their personal details, which are then validated by joi-browser system to ensure that the information provided is accurate and meets the website's requirements for creating an account. A new user cannot be created if email is already in use.
I coded regex validation for both my password and email to ensure that they met the necessary requirements and provided a secure user experience.

#### Login
When logging into website, users are required to provide their login credentials, which are then validated by joi-browser to ensure that the information entered is accurate and matches the user's account details.

#### Store page
The store page allows users to browse and view all available products, making it easy for them to find what they are looking for and make a purchase.

#### Search bar
Search bar allows users to search for specific products by typing in relevant keywords, and displays a list of products that match the query along with the corresponding URL.

#### Cart
Adding to cart requires login.
The cart feature displays a list of all products that have been added by the user, along with their corresponding prices.

#### Product card
A product card displays all relevant information about a particular item, including product details, images, and price, while also featuring an "Add to Cart" button for easy purchasing.

#### Footer
The footer section contains all the important information that customers may need, such as contact details, links to social media pages.


#### Redux
In my ecommerce project, I used Redux to efficiently manage the flow of data between the backend and frontend, allowing me to easily retrieve and update information from the backend as needed, and providing a centralized store for application state that could be accessed by components throughout the frontend, resulting in a more streamlined and responsive user experience.

--------------------------
## Backend:

#### Hashed password
To ensure the security of user data in the project, hashed passwords can be used in Node.js by generating a unique salt value for each password, combining the salt and password, and then using a hashing algorithm such as bcrypt to securely store the resulting hash in a database, making it virtually impossible for unauthorized users to access sensitive information even if they manage to gain access to the database.

#### Backend architecture
the backend organized using a model-view-controller (MVC) architecture, with controllers, routes, models, middlewares, and configuration files all serving specific roles in managing data and functionality within the application, allowing for a more modular and organized approach to development that makes it easier to maintain and scale the project over time.

#### Authorization and authentication
In my ecommerce project, I employed robust authentication and authorization mechanisms in the backend to ensure that only authorized users had access to sensitive data and functionality, utilizing techniques such as user authentication and role-based access control to authenticate and authorize user actions and manage access to different parts of the application based on user privileges and permissions, resulting in a more secure and reliable ecommerce platform for users and admins.

#### MongoDB
I utilized the MongoDB cloud database to store and manage all of the project's data, including user account information, and more.








