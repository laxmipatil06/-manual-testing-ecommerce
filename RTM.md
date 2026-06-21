# Requirements Traceability Matrix (RTM)
## Project: E-commerce Web Application Testing
## Website: https://www.saucedemo.com

---

## What is RTM?
RTM maps every requirement to its test cases ensuring 
100% requirements coverage and no requirement is missed.

---

## RTM Table

| Req ID | Requirement | Test Case IDs | Status |
|--------|-------------|---------------|--------|
| REQ001 | User should be able to login with valid credentials | TC001 | Covered |
| REQ002 | System should reject invalid login attempts | TC002, TC003 | Covered |
| REQ003 | Empty fields should show validation errors | TC004, TC005, TC006 | Covered |
| REQ004 | Locked out user should see appropriate message | TC007 | Covered |
| REQ005 | Password should be masked on screen | TC008 | Covered |
| REQ006 | Login page should load correctly | TC009, TC010 | Covered |
| REQ007 | Products page should load after login | TC011 | Covered |
| REQ008 | All products should be displayed with details | TC012, TC013, TC014, TC015 | Covered |
| REQ009 | User should be able to add products to cart | TC016, TC025 | Covered |
| REQ010 | User should be able to sort products | TC017, TC018, TC019, TC020 | Covered |
| REQ011 | User should be able to view product details | TC021, TC022, TC023, TC024 | Covered |
| REQ012 | Back button should work on detail page | TC026 | Covered |
| REQ013 | Cart should show correct item count | TC027, TC035 | Covered |
| REQ014 | User should be able to view cart | TC028, TC029, TC030 | Covered |
| REQ015 | User should be able to remove items from cart | TC031 | Covered |
| REQ016 | Continue shopping should work from cart | TC032 | Covered |
| REQ017 | User should be able to proceed to checkout | TC033 | Covered |
| REQ018 | User should be able to add multiple products | TC034 | Covered |
| REQ019 | Checkout page should load correctly | TC036 | Covered |
| REQ020 | Checkout should accept valid user details | TC037 | Covered |
| REQ021 | Checkout should validate empty fields | TC038, TC039, TC040 | Covered |
| REQ022 | Checkout overview should show order details | TC041, TC042 | Covered |
| REQ023 | User should be able to complete purchase | TC043, TC044 | Covered |
| REQ024 | User should be able to cancel checkout | TC045 | Covered |
| REQ025 | Logout option should be available | TC046 | Covered |
| REQ026 | Logout should work correctly | TC047 | Covered |
| REQ027 | Protected pages should not be accessible after logout | TC048, TC049 | Covered |
| REQ028 | Navigation menu should work correctly | TC050 | Covered |

---

## Coverage Summary

| Module | Total Requirements | Test Cases | Coverage |
|--------|-------------------|------------|----------|
| Login | 6 | TC001-TC010 | 100% |
| Products Page | 5 | TC011-TC020 | 100% |
| Product Detail | 3 | TC021-TC026 | 100% |
| Shopping Cart | 9 | TC027-TC035 | 100% |
| Checkout | 10 | TC036-TC045 | 100% |
| Logout | 4 | TC046-TC050 | 100% |
| **Total** | **28** | **50** | **100%** |

---

## Bugs Found vs Requirements

| Req ID | Requirement | Bug ID | Bug Status |
|--------|-------------|--------|------------|
| REQ002 | Reject invalid login | BUG001, BUG002 | Open |
| REQ008 | Products displayed correctly | BUG003, BUG013 | Open |
| REQ013 | Cart count correct | BUG004 | Open |
| REQ010 | Sort products | BUG005 | Open |
| REQ009 | Add to cart | BUG006 | Open |
| REQ020 | Checkout validation | BUG007, BUG008 | Open |
| REQ022 | Checkout overview | BUG009 | Open |
| REQ024 | Cancel checkout | BUG010 | Open |
| REQ023 | Complete purchase | BUG011, BUG015 | Open |
| REQ025 | Logout navigation | BUG012 | Open |
| REQ009 | Add to cart performance | BUG014 | Open |

---

## Sign Off

| Role | Name | Date |
|------|------|------|
| QA Engineer | Laxmi Vaijanath Patil | June 2026 |
