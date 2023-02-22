# Test-Case-Examples that I wrote using a demo website: https://www.saucedemo.com/

**# Functional Test Cases**
-----------
**ID:** 1

**Description:**
Check if login works with correct credentials.

**Steps:**
1. Go to https://www.saucedemo.com/
2. Add a correct user/pass
3. Press Login button

**Expected result:**
The user should be able to login and is taken to his profile page.

**Test Data:**

user: standard_user

pass: secret_sauce

-----------

**ID:** 2

**Description:**
Check if relevant error message is shown when logging in with blocked user.

**Precondition:**
User is locked out

**Steps:**
1. Go to https://www.saucedemo.com/
2. Add user and password
3. Press Login button

**Expected result:**
Error message is displayed: "Epic sadface: Sorry, this user has been locked out."

**Test Data**

user: locked_out_user

pass: secret_sauce

----------

**ID:** 3

**Description:**
Check if login page can be accessed by entering the correct URL.

**Steps:**
1. Open web browser
2. Enter the login page URL to the base URL
3. Click enter key or go button on the browser

**Expected result:**
The login page should be displayed.

**Test Data:** 
URL Page: https://www.saucedemo.com/

----------

**ID:** 4

**Description:**
Check if login page is displayed, including relevant fields such as username and password fields.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser

**Expected result:**
The login page should be displayed with user and password fields that can be filled by users.

**Test Data:** 
URL Page: https://www.saucedemo.com/

----------
**ID:** 5

**Description:**
Check if login button is displayed.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser

**Expected result:**
The login button should be displayed on login page, underneath user and password fields.

**Test Data:** 
URL Page: https://www.saucedemo.com/

----------

**ID:** 6

**Description:**
Check if relevant error message is shown when logging in with correct user and wrong password.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add correct user and wrong password
5. Click Login button

**Expected result:**
Error message should be displayed: " Epic sadface: Username and password do not match any user in this service".

**Test Data:** 

user: standard_user

pass: secretsauce

----------
**ID:** 7

**Description:**
Check if relevant error message is shown when logging in with wrong user and correct password.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add wrong user and correct password
5. Click Login button

**Expected result:**
Error message should be displayed: " Epic sadface: Username and password do not match any user in this service"

**Test Data:** 

user: standarduser

pass: secret_sauce

----------
**ID:** 8

**Description:**
Check if relevant error message is shown when user and password fields are not filled.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Do not fill any value in user and password fields
5. Click Login button

**Expected result:**
Error message should be displayed: " Epic sadface: Username is required".

**Test Data:** 
N/A

----------
**ID:** 9

**Description:**
Check if relevant error message is shown when user and password fields are not filled.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Do not fill any value in user and password fields
5. Click Login button

**Expected result:**
Error message is displayed: " Epic sadface: Username is required".

**Test Data:** 
N/A

----------
**ID:** 10

**Description:**
Check if X button located at the end of username field is working.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Write username or any text in the username field
5. Click on X button 

**Expected result:**
Value is erased from the field.

**Test Data:** 
N/A

----------
**ID:** 11

**Description:**
Check if user is able to logout successfully.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. CLick on upper left side three line menu button
7. Click on Logout 

**Expected result:**
User is logged out.

**Test Data:** 

user: standard_user

pass: secretsauce

----------
**ID:** 12

**Description:**
Check if user is redirected to the correct page after a successful login.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button

**Expected result:**
User is redirected to products page.

**Test Data:** 

user: standard_user

pass: secret_sauce

-------
**ID:** 13

**Description:**
Check whether the user can add products to the cart, and if the "add to cart" button is clickable.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Click on " Add to cart" button for a product

**Expected result:**
The user has product in his cart, after clicking " Add to cart" button.

**Test Data:** 

user: standard_user

pass: secret_sauce

-------

**ID:** 14

**Description:**
Check whether the count is increasing after adding new items to cart.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Click on " Add to cart" button for a product
7. Check the counter for number of items

**Expected result:**
The number of items in cart is visible and incresing when another items are added.

**Test Data:** 

user: standard_user

pass: secret_sauce

-------

**ID:** 15

**Description:**
Check if the same item is added multiple times to the cart.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Click on " Add to cart" button for a product multiple times

**Expected result:**
The product can be added in cart multiple times.

**Test Data:** 

user: standard_user

pass: secret_sauce

-------
**ID:** 16

**Description:**
Check if products are displayed by low to high price when selecting Price (low to high) in filter box.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Click Price (low to high) on filter box


**Expected result:**
Products are displayed according to increasing prices.

**Test Data:** 

user: standard_user

pass: secret_sauce

-------
**ID:** 17

**Description:**
Check if products are displayed by high to low price, when selecting Price (high to low) in filter box.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Click Price (high to low) in filter box 


**Expected result:**
Products are displayed according to decreasing prices.

**Test Data:** 

user: standard_user

pass: secret_sauce

-------

**ID:** 18

**Description:**
Check if the products name are displayed from A to Z, when selecting NAME (A to Z) in filter box.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Click NAME (A to Z) in filter box 


**Expected result:**
Products name are displayed from A to Z.

**Test Data:** 

user: standard_user

pass: secret_sauce

-------
**ID:** 19

**Description:**
Check if the products name are displayed from Z to A, when selecting NAME (Z to A) in filter box.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Click NAME (Z to A) in filter box 


**Expected result:**
Products name are displayed from Z to A.

**Test Data:** 

user: standard_user

pass: secret_sauce

---------

**ID:** 20

**Description:**
Check if every product has a relevant image displayed.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Add username and password
5. Click Login button
6. Check the image for every product

**Expected result:**
Every product has a relevant image.

**Test Data:** 

user: standard_user

pass: secret_sauce

------
**ID:** 21

**Description:**
Check if user can go into details screen for a specific product.

**Steps:**
1. Login with user
2. Click on the image for a specific product


**Expected result:**
Details screen for specific product is displayed.

**Test Data:** 

user: standard_user

pass: secret_sauce

------
**ID:** 22

**Description:**
Relevant image is displayed in details screen for specific product.

**Steps:**
1. Login with user
2. Click on the image for a specific product
3. Check image product

**Expected result:**
Relevant image is displayed for specific product.

**Test Data:** 

user: standard_user

pass: secret_sauce

------
**ID:** 23

**Description:**
The product price is displayed in details screen.

**Steps:**
1. Login with user
2. Click on a product 

**Expected result:**
Price is displayed.

**Test Data:** 

user: standard_user

pass: secret_sauce

------
**ID:** 24

**Description:**
Relevant description and information about the product is displayed in details screen.

**Steps:**
1. Login with user
2. Click on a product 

**Expected result:**
Product information and description is displayed.

**Test Data:** 

user: standard_user

pass: secret_sauce

------
**ID:** 25

**Description:**
User can add to cart item by clicking "Add to cart" button from details screen of a product.

**Steps:**
1. Login with user
2. CLick on a product 
3. Click "Add to cart" button

**Expected result:**
Product is added to cart.

**Test Data:** 

user: standard_user

pass: secret_sauce

------
**ID:** 26

**Description:**
Counter for items is increasing after clicking "Add to cart" button from details screen of a product.

**Steps:**
1. Login with user
2. CLick on a product 
3. Click "Add to cart" button
4. Check counter for number of items

**Expected result:**
Counter reflects correct number of items.

**Test Data:** 

user: standard_user

pass: secret_sauce

------

**ID:** 27

**Description:**
Item is removed after clicking on "Remove" button from details screen of a product.

**Steps:**
1. Login with user
2. CLick on a product 
3. Click "Add to cart" button
4. Click "Remove" button

**Expected result:**
Item is removed from cart.

**Test Data:** 

user: standard_user

pass: secret_sauce

------

**ID:** 28

**Description:**
Check if user is redirected to the Check out page after clicking "Checkout" button.

**Steps:**
1. Login with user
2. CLick on a product 
3. Click "Add to cart"
4. Go into the Cart
5. Click "Checkout" 

**Expected result:**
User is redirected to checkout information field.

**Test Data:** 

user: standard_user

pass: secret_sauce

------

**ID:** 29

**Description:**
User can return to products page by clicking "Continue shopping" button.

**Steps:**
1. Login with user
2. Click on Cart
3. Click "Continue Shopping"

**Expected result:**
Product page is displayed.

**Test Data:** 

user: standard_user

pass: secret_sauce

------

**ID:** 30

**Description:**
User should not checkout without having any product in cart.

**Steps:**
1. Login with user
2. Click on Cart
3. Click "Checkout"
4. Fill in the fields
5. Click "Continue" 
6. Click "Finish"

**Expected result:**
User should not be able to checkout with empty cart.
**Test Data:** 

user: standard_user

pass: secret_sauce

------

**ID:** 31

**Description:**
Check if relevant text error is displayed when Name field is not filled in the checkout page.

**Steps:**
1. Login with user
2. Click on Cart
3. Click "Checkout"
4. Do not fill any value in "First name" field
5. Click "Continue" 

**Expected result:**
Error message is displayed: "Error: First Name is required".

**Test Data:** 

user: standard_user

pass: secret_sauce

------

**ID:** 32

**Description:**
Verify that clicking "All items" from the submenu, displayes all items.

**Steps:**
1. Login with user
2. Click on menu 
3. Click on "All items"

**Expected result:**
Page with all items is displayed.

**Test Data:** 

user: standard_user

pass: secret_sauce

------

**ID:** 33

**Description:**
Information page is displayed when clicking "About" button from menu.

**Steps:**
1. Login with user
2. Click menu button 
3. Click "About"

**Expected result:**
Page with information about Sauce Labs is displayed.

**Test Data:** 

user: standard_user

pass: secret_sauce

------

**ID:** 34

**Description:**
Verify that "x" button from left side menu is working.

**Steps:**
1. Login with user
2. Click left side menu button 
3. Click "X" button

**Expected result:**
Menu is closed.

**Test Data:** 

user: standard_user

pass: secret_sauce

------

**ID:** 35

**Description:**
Relevant text error is displayed when "Last Name" field is not filled in the checkout page.

**Steps:**
1. Login with user
2. Click on Cart
3. Click "Checkout"
4. Do not fill any value in "Last Name" field
5. Click "Continue" 

**Expected result:**
Error message is displayed: "Error: Last Name is required"

**Test Data:** 

user: standard_user

pass: secret_sauce

----------

**ID:** 36

**Description:**
Relevant text error is displayed when "Zip/Postal code" field is not filled in the checkout page.

**Steps:**
1. Login with user
2. Click on Cart
3. Click "Checkout"
4. Do not fill any value in "Zip/Postal code" field
5. Click "Continue" 

**Expected result:**
Error message is displayed: "Error: Zip/Postal code is required".

**Test Data:** 

user: standard_user

pass: secret_sauce

----------

**ID:** 37

**Description:**
Total price of the order includes taxes and shipping fee.

**Steps:**
1. Login with user
2. Click on Cart
3. Click "Checkout"
4. Fill Name, Last Name and Zip/Postal Code 
5. Click "Continue" 
6. Check cart total price

**Expected result:**
Total price of the order includes the transport fee and taxes.

**Test Data:** 

user: standard_user

pass: secret_sauce

----------

**ID:** 38

**Description:**
User is able to cancel checkout process by using "Cancel" button.

**Steps:**
1. Login with user
2. Click on Cart
3. Click "Checkout"
4. Fill Name, Last Name and Zip/Postal Code 
5. Click "Continue" 
6. Click "Cancel" button 
7. 
**Expected result:**
Checkout page is closed, user is redirected to cart.

**Test Data:** 

user: standard_user

pass: secret_sauce

----------

**ID:** 39

**Description:**
User gets redirected to Twitter's company page, after clicking Twitter icon.

**Steps:**
1. Login with user
2. Click on Twitter icon (bottom left side)

**Expected result:**
User is redirected to Sauce Labs Twitter page.

**Test Data:** 

user: standard_user

pass: secret_sauce

----------

**ID:** 40

**Description:**
User gets redirected to Facebook's company page, after clicking Facebook icon.

**Steps:**
1. Login with user
2. Click on Facebook icon (bottom left side)

**Expected result:**
User is redirected to Sauce Labs Facebook page.

**Test Data:** 

user: standard_user

pass: secret_sauce

----------

**ID:** 41

**Description:**
User gets redirected to Linkedin's company page, after clicking Linkedin icon.

**Steps:**
1. Login with user
2. Click on Linkedin icon (bottom left side)

**Expected result:**
User is redirected to Sauce Labs Linkedin page.

**Test Data:** 

user: standard_user

pass: secret_sauce


**# Non-Functional Test Cases**
----------

**ID:** 1

**Description:**
Check if the web page is loading quickly when you login with correct credentials.

**Steps:**
1. Login with user and password
2. Observe the time it's taken to load the web page

**Expected result:**
The web page should be able to load quickly after you login with correct username and password.

**Test Data:** 

user: performance_glitch_user

pass: secret_sauce

----------
**ID:** 2

**Description:**
Check login performance when logging 100 users simultanously.

**Precondition:**
Using a tool for performance testing, load 100 simultanously users testing login functionality.

**Steps:**
1. Login 

**Expected result:**
No performance issues detected, user is redirected to products page.

**Test Data:** 

user: standard_user

pass: secret_sauce

----------
**ID:** 3

**Description:**
Verify if the font, text color, and color coding of the Login page is as per the standard.

**Precondition:**
Verify specifications for font, color coding and text color for login page.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser

**Expected result:**
Font, color coding and text color in login page meets the specifications.

**Test Data:** 

user: standard_user

pass: secret_sauce

--------

**ID:** 4

**Description:**
Check if user cannot enter the characters more than the specified range in each field.

**Steps:**
1. Open web browser
2. Enter https://www.saucedemo.com/ on the base URL
3. Click enter key or go button on the browser
4. Enter text that is longer than the maximum allowed length in each field

**Expected result:**
User is not able to enter more characters than is allowed.

**Test Data:** 

user: standard_user

pass: secret_sauce

--------

**ID:** 5

**Description:**
Check login page by pressing ‘Back button’ of the browser.

**Steps:**
1. Login 
2. Press 'Back button'

**Expected result:**
 User still remains logged in because auth session is still active
 
**Test Data:**

user: standard_user

pass: secret_sauce


