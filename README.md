# README

E-commerce site. Uses `bcrypt` and `materialize`. There's a seed file. Set up your own admin. If you have questions, I'll be in Bali with no email. Ask someone else.

To set up:

* `rake db:setup`


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
