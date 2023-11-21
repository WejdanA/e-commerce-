# Project: E-commerce Website

This projecet consits of tow part:

- front-end
- back-end

## Front-end E-commerce Website

The frontend interacts with mock data stored locally in the project. Ones the backen-end finalized, this data will be connected to the backend.

Please, do not spend time on creating your own server. Use the files that are in the `./public/mock/*` as mock data.

Tech Stack: React, TypeScript, and React/Redux Toolkit. Styling: CSS/SASS and Bootstrap.

**Data Sources:**

- Products: id, name, description, categories, variants, sizes
- Categories: id, name
- Orders: id, productId, userId, purchasedAt
- Users: id, firstName, lastName, email, password, role (visitor or admin)

**Pages:**

1. [x] Home page (list all the products)
2. [x] Product page (contain the details of a product)
3. [x] Admin page
4. [x] Cart page

**Functionalities for a Visitor:**

- [x] Get list of products
- [x] Filter products by categories or price
- [x] Search products by name
- [x] Add products to a cart
- [x] Remove products from a cart

**Functionalities for an Admin:**

- [x] Add a new product, update info of a product, remove a product
- [x] list all users, delete or block a user.
- [x] list all orders
- [x] Add a new category, update info of a category, remove a category

**Authentication:**

- [x] Implement register and login functionality via email and password
- [x] Protect the routes based on login and admin status

**Form Validation:**

- [x] Implement form validation.

**Addtional:**

- [x] Messages, show loading, success, and error messages (e.g., when loading products list or adding new product)
- [x] Implement pagination feature
- [x] Create a Profile Page (only available if user logs in), implement editing user profile feature (user can change first name, last name)

## Back-end E-commerce Website

The back-end will be updated soon

Tech Stack: Express, TypeScript, MongoDB and Mongoose Toolkit.

# Run the projecet

1. git clone https://github.com/WejdanA/e-commerce-.git
2. cd e-commerce
3. install npm
4. npm start
