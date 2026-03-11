Bug 1

Title: Incorrect validation message when name contains less than 3 characters

Steps to reproduce
 1. Open registration page
 2. Enter name with less than 3 characters
 3. Click “Register”

Expected result

System should display a message that name must contain at least 3 characters.

Actual result

System shows message:
“Please fill in your name/surname”.

Severity

Low

⸻

Bug 2

Title: Discount block overlaps product price on tablet resolution

Steps to reproduce
 1. Open product page
 2. Resize browser window to tablet resolution
 3. Observe product card

Expected result

Product elements are displayed correctly without overlapping.

Actual result

Discount block (div det_product_shop) overlaps the product price.

Severity

Medium

⸻

Bug 3

Title: Registration form displays validation error only for the first empty field

Steps to reproduce
 1. Open registration page
 2. Leave all fields empty
 3. Click “Register”

Expected result

System should show validation errors for all required fields.

Actual result

System displays error only for the name/surname field.

Severity

Low