#E-Commerce Website - Node.js and MongoDB

#Description:
This project is an E-Commerce website built using Node.js for server-side scripting and MongoDB for database storage. The application includes key features such as user authentication (Login/Signup), a Home page displaying products, a shopping cart, and a Contact Us page.

#Table of Contents

-Installation
-Usage
-Features
-Dependencies
-Configuration
-Contributing
-License

#Installation
> Clone the repository to your local machine:
    git clone https://github.com/your-username/your-project.git

> Navigate to the project directory:
    cd your-project

> Install the required dependencies:
    npm install

#Usage
To run the application, use the following command:
    bashnpm start
Access the application in your web browser at http://localhost:3000.

#Features
1. User Authentication
    Signup: Users can create accounts by providing necessary information.
    Login: Registered users can log in securely.
2. Product Catalog
    The Home page displays a catalog of products available for purchase.
3. Shopping Cart
    Users can add products to their shopping cart and proceed to checkout.
4. Contact Us Page
    Users can use the Contact Us page to send inquiries or feedback.

#Dependencies
The project relies on the following dependencies:

express: Web application framework for Node.js.
mongoose: MongoDB object modeling tool.
bcryptjs: Library for hashing passwords.
express-session: Middleware for session management.
passport: Authentication middleware.
hbs: Templating engine for rendering views.

> Install these dependencies using the command:
    npm install express mongoose bcryptjs express-session body-parser hbs 

#Configuration
1. MongoDB Connection
Configure your MongoDB connection string in the config.js file:
    // config.js

module.exports = {
  mongoURI: 'your-mongodb-connection-string',
  secretKey: 'your-secret-key-for-session',
};

Replace 'your-mongodb-connection-string' with your actual MongoDB connection string and 'your-secret-key-for-session' with a secret key for session management.


Thank You !
