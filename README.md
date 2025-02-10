Checkout and Special Offer Page
Table of Contents
Features Tested
Test Plan
Test Scenarios
Test Cases
Bug Reports
Summary Report
Getting Started
Running the Tests
Contributing
License
Features Tested
Checkout Process
Objective: Verify that the checkout process works as expected, including adding items to the cart, reviewing the cart, and completing the order.
Key Checks:
Items can be added and removed from the cart.
The cart updates the item quantities correctly.
The user can successfully proceed to payment.
Correct pricing and taxes are applied.
The user can apply discount codes or coupons successfully.
The order confirmation page displays the correct details.
Special Offer Page
Objective: Ensure that the special offer page is displayed correctly and that users can take advantage of the offers.
Key Checks:
Special offers are displayed correctly on the page.
Offers can be redeemed during checkout.
Offers have valid expiration dates and are correctly hidden or marked expired when the date has passed.

Test Plan
Scope
In Scope: Checkout process functionality and special offer page.
Out of Scope: Other features of the web application not related to checkout or special offers.
Test Environment
Browser: Chrome, Firefox, and Safari
Operating System: Windows 10, macOS
Test Strategy
Manual Testing: Initial exploratory testing.

Test Scenarios
Checkout Process
Verify that the checkout page loads correctly.
Verify that items can be added to the cart.
Verify that items can be removed or quantities adjusted in the cart.
Verify that the user can proceed to the payment page.
Verify that correct pricing, taxes, and discounts are applied.
Verify that an order confirmation page is displayed with the correct details.
Special Offer Page
Verify that the special offers page is accessible from the homepage.
Verify that the offers are displayed correctly.
Verify that users can apply a special offer during checkout.
Verify that expired offers are hidden or marked expired.
Verify that the special offers are displayed with the correct expiration date and terms.

Test Cases
Checkout Process
TC001: Verify that the checkout page loads correctly.
TC002: Verify that items can be added to the cart.
TC003: Verify that the cart can be updated (quantity change, item removal).
TC004: Verify that the user can proceed to payment.
TC005: Verify that correct pricing and taxes are applied.
TC006: Verify that discount codes or coupons can be applied.
TC007: Verify that the order confirmation page displays correct details.
Special Offer Page
TC008: Verify that the special offers page is accessible.
TC009: Verify that special offers are displayed correctly.
TC010: Verify that a special offer can be applied during checkout.
TC011: Verify that expired offers are hidden or marked expired.
TC012: Verify that offers are displayed with correct expiration date and terms.

Bug Reports
Bug 001: Cart Item Quantity Not Updating
Description: Changing the quantity of an item in the cart does not update the total price.
Severity: High
Steps to Reproduce:
Add an item to the cart.
Change the quantity of the item.
Observe that the total price does not update accordingly.
Expected Result: The total price should update when the item quantity is changed.
Actual Result: The total price remains the same.
Bug 002: Special Offer Code Not Applying
Description: Special offer code cannot be applied during checkout.
Severity: Medium
Steps to Reproduce:
Navigate to the checkout page.
Enter a valid special offer code.
Click "Apply."
Expected Result: The discount should be applied to the total price.
Actual Result: No discount is applied.
Bug 003: Expired Special Offers Still Visible
Description: Expired special offers are still displayed on the special offers page.
Severity: Low
Steps to Reproduce:
Visit the special offers page.
Check if expired offers are listed.
Expected Result: Expired offers should be hidden or marked as expired.
Actual Result: Expired offers are still visible.

Summary Report
Test Execution Summary
Total Test Cases: 60
Passed: 44
Failed: 16
Success Rate: 66.67%
Key Findings
Two critical bugs were identified:
Cart item quantity does not update correctly.
Special offer code cannot be applied during checkout.
One minor bug: Expired special offers are still visible.
Recommendations
Fix the issue where cart item quantities are not updating correctly.
Resolve the problem preventing special offer codes from being applied.
Hide or mark expired special offers correctly.
