# Functional Testing

#### Preconditions:

- Website Trussardi (https://www.trussardi.com/en/it) is opened
- Stable internet connection

#### Test Case №1: The cart page loads
Preconditions:
None
##### Steps:
1. Open the site and close all popups in the way that content is clickable
##### Result: 
Header top lings, logo image, header navigation bar, search, shopping cart, images, footer navigation, footer copyright blocks, footer contacts, footer newsletter are rendered

#### Test Case №2: A single product page loads
Preconditions:
None
##### Steps:
1. Click on the main picture in the page with a model
2. Click on the Medium Nadir tote bag picture

##### Result: 
Single product page is loaded: Title, price, properties, ADD TO CART button and description are displayed

#### Test Case №3: The New Collection Men page loads
Preconditions:
None
##### Steps:
1. Hover on NEW COLLECTION button on the header
2. Click on MEN button

##### Result: 
NEW COLLECTION for Men page is loaded: Images of goods, names and cost are displayed, when you click on a product, you go to the page with the product

#### Test Case №4: A customer can add a product to their cart
Preconditions:
Main page is opened.
##### Steps:
1. Click on the main picture in the page with a model
2. Click on the Medium Nadir tote bag picture
3. Click on the Black color
4. Select One size
5. Click on the Add to cart

##### Result: 
Cart popup is opened. Title, id, properties and total price are displayed here. SHOPPING BAG button & checkout and coupon code field, apply button are displayed. Clothes are added to the bag.
---------
#### Test Case №5: Find a store works
Preconditions:
Website https://www.trussardi.com/en/it is opened.
##### Steps:
1. Click on EN/IT button : Window with other buttons is opened and displayed (SHIPPING TO: ITALY. button Change Country, button Find A Store, button Localize Me)
2. Click on Find A Store : Page is opened, maps & shops list is displayed (The map is interactive, you can click on the name of the shops)

#### Test Case №6: A customer can open cart page as a guest
Preconditions
Website https://www.trussardi.com/en/it is opened.
At least one clothing is added to the cart.
All possible popups are closed in such way, that cart in the header is clickable.
Account not logged in
##### Steps : Result
1. Hover on the cart in the header
2. Click on the cart in the header : My cart with Total price is displayed
3. Change Quantity of items in the bag: Total is recalculated according to the amount of items
4. Enter a coupon code: The total cost has been recalculated
5. Click on Checkout : Cart page is opened 

#### Test Case №7: Viewing the empty cart
Preconditions
Nothing is added to the bag.
##### Steps:
1. Open the site and close all popups in the way that cart in the header is clickable
2. Click on the cart in the header : Cart page is opened, "YOUR SHOPPING CART IS EMPTY" and button "CONTINUE SHOPPING" is opened

#### Test Case №8: Invalid Search result
Preconditions:
Main page is opened.

##### Steps:
1. Click on the search button on the header and type MEDFSGDFSHGDSF text

##### Result: 
No product found window is opened and NO RESULTS "MEDFSGDFSHGDSF" text is rendered

#### Test Case №9: Valid Search result
Preconditions:
Main page is opened.

##### Steps:
1. Click on the search button on the header and type Medium Nadir tote bag text : Bags with given name is displayed(text, image, title, price)
2. Click on the first bag : Medium Nadir tote bag page is opened, single product page is loaded: Title, price, properties, ADD TO CART button and description are displayed

#### Test Case №10: Social media buttons work
Preconditions:
Main page is opened.
##### Steps:
1. Click on the social media buttons in the footer of the page

##### Result: 
The desired social network opens
