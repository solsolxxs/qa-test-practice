Test Case 1

Title: Registration with valid data

Steps:
 1. Open registration page
 2. Enter valid name (≥3 characters)
 3. Enter valid email
 4. Enter valid password
 5. Click “Register”

Expected result:
User account is created successfully.

⸻

Test Case 2

Title: Registration with empty fields

Steps:
 1. Open registration page
 2. Leave all fields empty
 3. Click “Register”

Expected result:
System displays validation errors for all required fields.

⸻

Test Case 3

Title: Registration with name shorter than 3 characters

Steps:
 1. Open registration page
 2. Enter name with 1–2 characters
 3. Enter valid email and password
 4. Click “Register”

Expected result:
System displays message that the name must be at least 3 characters long.

⸻

Test Case 4

Title: Check responsive layout on tablet resolution

Steps:
 1. Open product page
 2. Resize browser window to tablet resolution
 3. Observe all UI elements

Expected result:
All elements are displayed correctly without overlapping (discount, price, buttons).

⸻

Test Case 5

Title: Login with valid credentials

Steps:
 1. Open login page
 2. Enter registered email and password
 3. Click “Login”

Expected result:
User successfully logs into their account.