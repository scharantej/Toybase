## Flask Application Design for a Toy Shopping Website

### Overview
The provided problem outlines the need for a Python Flask application to create a toy shopping website specializing in kids' sports products. The following design defines the necessary HTML files and routes for this application.

### HTML Files
- index.html: Main landing page of the website, displaying a list of toy categories.
- category.html: Displays a list of toys within a specific category.
- product.html: Displays detailed information about a particular toy.
- cart.html: Displays the items in the user's shopping cart.

### Routes
**Main Routes**
- `/`: Renders the index.html page, displaying the toy categories.
- `/category/<category>`: Renders the category.html page, displaying toys in a specific category.
- `/product/<product_id>`: Renders the product.html page, displaying details of a specific toy.

**Cart Routes**
- `/cart`: Renders the cart.html page, displaying the items in the user's cart.
- `/add_to_cart/<product_id>`: Adds a toy to the user's cart.
- `/remove_from_cart/<product_id>`: Removes a toy from the user's cart.
- `/checkout`: Handles the checkout process and payment.

**Additional Routes**
- `/about`: Displays the about us page.
- `/contact`: Displays the contact us page.