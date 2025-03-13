# Shopping-App-
Creating a simple shopping app with python
Key Features & Requirements
1. User & Admin Login
•	Welcome message: "Welcome to the Demo Marketplace"
•	Separate login systems for users and admin.
•	Used demo databases for login verification and session ID creation.
•	Admin can log in only with correct credentials (error message on invalid login).

2. Product Catalog
•	Categories: Example (Footwear, Clothing, Electronics).
•	Products should have Product ID, Name, Category ID, and Price.
•	Both users and admin can view the product catalog.
3. User Functionalities
•	View Cart: Users can check items added to their cart.
•	Add to Cart: Users can add products to their cart using Session ID, Product ID, and Quantity.
•	Remove from Cart: Users can remove items.

4. Payment & Checkout
•	Users can checkout using Net Banking, PayPal, UPI, Debit Card.
•	Show messages after checkout: 
o	"Your order is successfully placed"

5. Admin Functionalities
•	Add Products: Admin can add products with details.
•	Update Products: Admin can modify product details.
•	Delete Products: Admin can remove products from the catalog.
•	Category Management: Admin can add/remove product categories.
•	Admin cannot interfere with user operations.

Implementation Plan 
1. Data Structures
•	Use dictionaries or lists to store users, products, and categories.
2. Functions
•	login_user() and login_admin()
•	view_catalog()
•	add_to_cart(), remove_from_cart(), view_cart()
•	checkout()
•	admin_add_product(), admin_update_product(), admin_delete_product()
•	admin_add_category(), admin_delete_category()
•	
We'll use dictionaries and lists to store users, admin, products, categories, and carts.
Data Structure Plan
•	users: Dictionary storing username-password pairs for user login.
•	admin: Dictionary storing admin credentials.
•	categories: Dictionary storing category ID and names.
•	products: List of dictionaries containing product details.
•	carts: Dictionary storing user-specific shopping carts.


