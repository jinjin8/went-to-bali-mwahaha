# E-Commerce

### Description
This app was created to meet specifications to refactor an existing app as a third Ruby on Rails independent project at Epicodus. It uses bcrypt to allow users to create an account and admin authentication for maintaining the site. All data dynamically persists via Postgres with ActiveRecord.

### Requirements
  * Ruby
  * Rails
  * ActiveRecord
  * Postgres

### Setup

  * `git clone https://github.com/jinjin8/went-to-bali-mwahaha`
  * `cd went-to-bali-mwahaha`
  * `bundle install`
  * Start Postgres server
  * `rake db:create`
  * `rake db:migrate`
  * `rake db:seed` to populate the site
  * `rails s`
  * Open browser and navigate to http://localhost:3000/

### Specifications:
Required AJAX tasks:
1. AJAX applied to adding items & updating total number of items on index page.
2. AJAX applied to show&hide product details; product detail includes an image.
3. AJAX applied to deleting items from the shopping cart & updating total price.

Refactored & tested:
1. Ensure that users can't order a negative number of items.
2. Add flash messages for signing up, signing in and signing out.
3. Add validations to all models.
4. Fix row height for products.
5. Add product update and delete functionality for admins.
6. Add further AJAX functionality to Admin CRUD.

### Technologies Used
  * HTML
  * CSS, Bootstrap, SASS Materialize
  * JavaScript
  * Ruby
  * Rails
  * Faker
  * Postgres
  * PSQL
  * ActiveRecord
  * bcrypt

### Support and contact details
  _jincamou@gmail.com_

### License
  _MIT_ &copy; _2017_ **jin camou**
