# Bug Report — E-commerce Web Application
## Website: https://www.saucedemo.com
## Total Bugs Found: 15+

---

## BUG 001
**Bug ID:** BUG001
**Title:** Error message not specific for invalid username
**Module:** Login
**Severity:** Medium
**Priority:** High
**Steps to Reproduce:**
1. Open saucedemo.com
2. Enter wrong username
3. Enter valid password
4. Click Login
**Expected Result:** Error should say "Invalid username"
**Actual Result:** Generic error message appears
**Status:** Open

---

## BUG 002
**Bug ID:** BUG002
**Title:** Locked out user error message is confusing
**Module:** Login
**Severity:** Medium
**Priority:** High
**Steps to Reproduce:**
1. Enter locked_out_user as username
2. Enter valid password
3. Click Login
**Expected Result:** Clear message saying account is locked with support contact
**Actual Result:** Generic locked out message with no further guidance
**Status:** Open

---

## BUG 003
**Bug ID:** BUG003
**Title:** Product images are identical for all products
**Module:** Products Page
**Severity:** High
**Priority:** High
**Steps to Reproduce:**
1. Login with valid credentials
2. View all products on products page
**Expected Result:** Each product should have unique image
**Actual Result:** All products show same image
**Status:** Open

---

## BUG 004
**Bug ID:** BUG004
**Title:** Cart count does not decrease after removing item
**Module:** Shopping Cart
**Severity:** High
**Priority:** High
**Steps to Reproduce:**
1. Login
2. Add 2 products to cart
3. Open cart
4. Remove one product
**Expected Result:** Cart count should decrease to 1
**Actual Result:** Cart count still shows 2
**Status:** Open

---

## BUG 005
**Bug ID:** BUG005
**Title:** Sort order resets after navigating back to products
**Module:** Products Page
**Severity:** Medium
**Priority:** Medium
**Steps to Reproduce:**
1. Login
2. Sort products by Price Low to High
3. Open any product detail page
4. Click Back button
**Expected Result:** Sort order should be maintained
**Actual Result:** Sort order resets to default
**Status:** Open

---

## BUG 006
**Bug ID:** BUG006
**Title:** No confirmation message when adding product to cart
**Module:** Shopping Cart
**Severity:** Low
**Priority:** Medium
**Steps to Reproduce:**
1. Login
2. Click Add to Cart on any product
**Expected Result:** Success message should appear confirming product added
**Actual Result:** No confirmation message shown
**Status:** Open

---

## BUG 007
**Bug ID:** BUG007
**Title:** Checkout allows special characters in First Name field
**Module:** Checkout
**Severity:** Medium
**Priority:** Medium
**Steps to Reproduce:**
1. Login and add product to cart
2. Go to checkout
3. Enter special characters like @#$ in First Name field
4. Click Continue
**Expected Result:** Validation error should appear
**Actual Result:** Form accepts special characters and proceeds
**Status:** Open

---

## BUG 008
**Bug ID:** BUG008
**Title:** No maximum length validation on zip code field
**Module:** Checkout
**Severity:** Low
**Priority:** Low
**Steps to Reproduce:**
1. Go to checkout
2. Enter very long number in zip code field
3. Click Continue
**Expected Result:** Maximum length validation should trigger
**Actual Result:** Field accepts unlimited characters
**Status:** Open

---

## BUG 009
**Bug ID:** BUG009
**Title:** Tax amount calculation not shown clearly
**Module:** Checkout
**Severity:** Medium
**Priority:** Medium
**Steps to Reproduce:**
1. Add products to cart
2. Complete checkout information
3. View checkout overview
**Expected Result:** Tax calculation breakdown should be clearly shown
**Actual Result:** Tax amount shown but no breakdown of how it is calculated
**Status:** Open

---

## BUG 010
**Bug ID:** BUG010
**Title:** Back button on checkout overview goes to products not cart
**Module:** Checkout
**Severity:** Medium
**Priority:** High
**Steps to Reproduce:**
1. Add product to cart
2. Go through checkout
3. On overview page click Cancel
**Expected Result:** Should return to cart page
**Actual Result:** Returns to products page losing cart context
**Status:** Open

---

## BUG 011
**Bug ID:** BUG011
**Title:** No email confirmation after order completion
**Module:** Checkout
**Severity:** Low
**Priority:** Low
**Steps to Reproduce:**
1. Complete entire checkout process
2. Click Finish
**Expected Result:** Order confirmation email should be sent
**Actual Result:** No email confirmation is sent
**Status:** Open

---

## BUG 012
**Bug ID:** BUG012
**Title:** Burger menu accessible on login page
**Module:** Navigation
**Severity:** Low
**Priority:** Low
**Steps to Reproduce:**
1. Open saucedemo.com login page
**Expected Result:** Burger menu should not be visible on login page
**Actual Result:** Burger menu icon is visible but non functional
**Status:** Open

---

## BUG 013
**Bug ID:** BUG013
**Title:** Product description truncated on products page
**Module:** Products Page
**Severity:** Low
**Priority:** Low
**Steps to Reproduce:**
1. Login
2. View products page
3. Read product descriptions
**Expected Result:** Full description should be visible or expandable
**Actual Result:** Description is truncated with no read more option
**Status:** Open

---

## BUG 014
**Bug ID:** BUG014
**Title:** No loading indicator when adding multiple items quickly
**Module:** Shopping Cart
**Severity:** Low
**Priority:** Low
**Steps to Reproduce:**
1. Login
2. Rapidly click Add to Cart on multiple products
**Expected Result:** Loading indicator should appear
**Actual Result:** No loading indicator shown
**Status:** Open

---

## BUG 015
**Bug ID:** BUG015
**Title:** Order history not available after completing purchase
**Module:** Checkout
**Severity:** High
**Priority:** High
**Steps to Reproduce:**
1. Complete full purchase
2. Try to find order history
**Expected Result:** Order history should be accessible from account
**Actual Result:** No order history feature exists
**Status:** Open
