# Test Cases — E-commerce Web Application
## Website: https://www.saucedemo.com
## Total Test Cases: 50+

---

## MODULE 1: LOGIN PAGE

| TC ID | Test Title | Steps | Expected Result | Status |
|-------|-----------|-------|-----------------|--------|
| TC001 | Login with valid credentials | 1. Open saucedemo.com 2. Enter valid username 3. Enter valid password 4. Click Login | User lands on products page | Pass |
| TC002 | Login with invalid password | 1. Enter valid username 2. Enter wrong password 3. Click Login | Error message appears | Pass |
| TC003 | Login with invalid username | 1. Enter wrong username 2. Enter valid password 3. Click Login | Error message appears | Pass |
| TC004 | Login with empty username | 1. Leave username empty 2. Enter password 3. Click Login | Username required error appears | Pass |
| TC005 | Login with empty password | 1. Enter username 2. Leave password empty 3. Click Login | Password required error appears | Pass |
| TC006 | Login with both fields empty | 1. Leave both fields empty 2. Click Login | Error message appears for both fields | Pass |
| TC007 | Login with locked out user | 1. Enter locked_out_user 2. Enter valid password 3. Click Login | Error message — user locked out | Pass |
| TC008 | Password is masked | 1. Type password in password field | Password shows as dots not plain text | Pass |
| TC009 | Login button is visible | 1. Open saucedemo.com | Login button is visible and clickable | Pass |
| TC010 | Page title is correct | 1. Open saucedemo.com | Page title shows Swag Labs | Pass |

---

## MODULE 2: PRODUCTS PAGE

| TC ID | Test Title | Steps | Expected Result | Status |
|-------|-----------|-------|-----------------|--------|
| TC011 | Products page loads after login | 1. Login with valid credentials | Products page loads with all items | Pass |
| TC012 | All products are displayed | 1. Login 2. Check products page | 6 products are visible | Pass |
| TC013 | Product name is displayed | 1. Login 2. Check each product | Each product has a name | Pass |
| TC014 | Product price is displayed | 1. Login 2. Check each product | Each product shows price | Pass |
| TC015 | Product image is displayed | 1. Login 2. Check each product | Each product has an image | Pass |
| TC016 | Add to cart button works | 1. Login 2. Click Add to Cart on any product | Product added to cart | Pass |
| TC017 | Sort by price low to high | 1. Login 2. Select Price Low to High | Products sorted correctly | Pass |
| TC018 | Sort by price high to low | 1. Login 2. Select Price High to Low | Products sorted correctly | Pass |
| TC019 | Sort by name A to Z | 1. Login 2. Select Name A to Z | Products sorted alphabetically | Pass |
| TC020 | Sort by name Z to A | 1. Login 2. Select Name Z to A | Products sorted reverse alphabetically | Pass |

---

## MODULE 3: PRODUCT DETAIL PAGE

| TC ID | Test Title | Steps | Expected Result | Status |
|-------|-----------|-------|-----------------|--------|
| TC021 | Click on product name opens detail page | 1. Login 2. Click product name | Product detail page opens | Pass |
| TC022 | Product detail shows name | 1. Open product detail page | Product name is displayed | Pass |
| TC023 | Product detail shows price | 1. Open product detail page | Product price is displayed | Pass |
| TC024 | Product detail shows description | 1. Open product detail page | Product description is displayed | Pass |
| TC025 | Add to cart from detail page | 1. Open product detail 2. Click Add to Cart | Product added to cart | Pass |
| TC026 | Back button works on detail page | 1. Open product detail 2. Click Back | Returns to products page | Pass |

---

## MODULE 4: SHOPPING CART

| TC ID | Test Title | Steps | Expected Result | Status |
|-------|-----------|-------|-----------------|--------|
| TC027 | Cart icon shows item count | 1. Add product to cart | Cart icon shows count 1 | Pass |
| TC028 | Open cart page | 1. Add product 2. Click cart icon | Cart page opens with added product | Pass |
| TC029 | Product name in cart | 1. Add product 2. Open cart | Product name is visible in cart | Pass |
| TC030 | Product price in cart | 1. Add product 2. Open cart | Product price is visible in cart | Pass |
| TC031 | Remove product from cart | 1. Add product 2. Open cart 3. Click Remove | Product removed from cart | Pass |
| TC032 | Continue shopping button works | 1. Open cart 2. Click Continue Shopping | Returns to products page | Pass |
| TC033 | Checkout button works | 1. Add product 2. Open cart 3. Click Checkout | Checkout page opens | Pass |
| TC034 | Add multiple products to cart | 1. Add 3 products to cart | All 3 products visible in cart | Pass |
| TC035 | Cart count updates correctly | 1. Add 2 products | Cart count shows 2 | Pass |

---

## MODULE 5: CHECKOUT

| TC ID | Test Title | Steps | Expected Result | Status |
|-------|-----------|-------|-----------------|--------|
| TC036 | Checkout page loads | 1. Add product 2. Open cart 3. Click Checkout | Checkout information page loads | Pass |
| TC037 | Checkout with valid details | 1. Enter First Name 2. Enter Last Name 3. Enter Zip Code 4. Click Continue | Moves to checkout overview | Pass |
| TC038 | Checkout with empty first name | 1. Leave First Name empty 2. Click Continue | Error message appears | Pass |
| TC039 | Checkout with empty last name | 1. Leave Last Name empty 2. Click Continue | Error message appears | Pass |
| TC040 | Checkout with empty zip code | 1. Leave Zip Code empty 2. Click Continue | Error message appears | Pass |
| TC041 | Checkout overview shows product | 1. Complete checkout info | Product details visible in overview | Pass |
| TC042 | Checkout overview shows total price | 1. Complete checkout info | Total price is displayed | Pass |
| TC043 | Finish button completes order | 1. Complete checkout 2. Click Finish | Order confirmation page appears | Pass |
| TC044 | Order confirmation message shows | 1. Complete order | Thank you message appears | Pass |
| TC045 | Cancel checkout works | 1. On checkout page 2. Click Cancel | Returns to cart page | Pass |

---

## MODULE 6: LOGOUT

| TC ID | Test Title | Steps | Expected Result | Status |
|-------|-----------|-------|-----------------|--------|
| TC046 | Logout option is available | 1. Login 2. Click burger menu | Logout option is visible | Pass |
| TC047 | Logout works correctly | 1. Login 2. Click burger menu 3. Click Logout | User is logged out and returns to login page | Pass |
| TC048 | Cannot access products after logout | 1. Logout 2. Try to access products URL directly | Redirected back to login page | Pass |
| TC049 | Session expires after logout | 1. Logout 2. Click back button | Login page appears not products page | Pass |
| TC050 | Menu opens and closes | 1. Login 2. Click burger menu 3. Click X | Menu closes correctly | Pass |
