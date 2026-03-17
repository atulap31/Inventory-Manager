Inventory Manager Application
A full-stack web application for managing product inventory with user authentication, session management, and file upload capabilities. Built with Node.js, Express, and EJS templating.

Features - 
 User Management
 User registration and login system
 Session-based authentication
 Logout functionality with session destruction
 Last visit tracking via cookies
 Product Management
 View all products in inventory
 Add new products with image upload
 Update existing product details
 Delete products with confirmation
 Product validation on creation

Technical Features - 
 File upload handling with Multer
 Form validation using Express-Validator
 EJS layouts for consistent UI
 Cookie parsing for user preferences
 Session management for authenticated routes
 Static file serving

Technology Stack
Backend: Node.js, Express.js
Templating: EJS, Express-ejs-layouts

Middleware:
express-session
cookie-parser
multer (file upload)
express-validator

Frontend: CSS, JavaScript

Project Structure
Inventory Manager
├── src/
│   ├── controllers/
│   │   ├── product.controller.js
│   │   └── user.controller.js
│   ├── middlewares/
│   │   ├── auth.middleware.js
│   │   ├── file-upload.middleware.js
│   │   ├── lastVisit.middleware.js
│   │   └── validation.middleware.js
│   ├── models/
│   │   ├── product.model.js
│   │   └── user.model.js
│   └── views/
│       ├── (EJS template files)
├── public/
│   ├── css/
│   │   ├── headers.css
│   │   └── index.css
│   ├── images/
│   └── js/
│       └── main.js
├── index.js
└── package.json

Dependencies
json
{
  "cookie-parser": "^1.4.7",
  "ejs": "^3.1.9",
  "express": "^4.18.2",
  "express-ejs-layouts": "^2.5.1",
  "express-session": "^1.19.0",
  "express-validator": "^7.0.1",
  "multer": "^2.1.1"
}

Security Features - 
 Session-based authentication
 Password validation
 Protected routes requiring login
 Input validation on server-side
 Secure file upload handling

Frontend Features -
 Responsive product grid layout
 Product images display
 Confirmation dialogs for delete operations
 User email display in header
 Last visit timestamp display

Contributing
Feel free to submit issues and enhancement requests!

