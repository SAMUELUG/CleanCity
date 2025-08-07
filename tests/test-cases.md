✅ TC-01: User Registration with Valid Inputs
Preconditions: User is on the registration page
Test Steps:

Open registration page

Enter valid full name, email, and password

Click “Register”
Expected Result: User account is created and redirected to the dashboard
Priority: High

✅ TC-02: Login with Valid Credentials
Preconditions: Registered user exists
Test Steps:

Open login page

Enter valid email and password

Click “Login”
Expected Result: User is logged in and redirected to dashboard
Priority: High

✅ TC-03: Login with Invalid Credentials
Preconditions: Invalid email/password combination
Test Steps:

Open login page

Enter incorrect email or password

Click “Login”
Expected Result: Error message appears (e.g., “Invalid credentials”)
Priority: Medium

✅ TC-04: Schedule a Waste Pickup
Preconditions: User is logged in
Test Steps:

Navigate to “Schedule Pickup” page

Fill in address, date, and waste type

Submit form
Expected Result: Request appears in dashboard under “Pending Pickups”
Priority: High

✅ TC-05: Cancel a Scheduled Pickup
Preconditions: Pickup already scheduled
Test Steps:

Navigate to scheduled pickups list

Click “Cancel” on an upcoming pickup
Expected Result: Status updates to “Cancelled” or pickup is removed from list
Priority: Medium

✅ TC-06: Form Validation - Required Fields
Preconditions: User is on any form (e.g., registration or schedule form)
Test Steps:

Leave all fields empty

Click Submit
Expected Result: Validation errors are shown next to required fields
Priority: High

✅ TC-07: Responsive Design - Mobile View
Preconditions: Using mobile emulator (Chrome DevTools)
Test Steps:

Load dashboard on mobile screen width (e.g., 375px)
Expected Result: All UI components adapt without overlap or layout breaks
Priority: Medium

✅ TC-08: Accessibility - Keyboard Navigation
Preconditions: Any interactive page open
Test Steps:

Use TAB key to navigate through elements

Observe focus outline and logical flow
Expected Result: All buttons, links, and inputs are reachable via keyboard
Priority: Medium

✅ TC-09: Blog Post Creation (Admin)
Preconditions: Logged in as Admin
Test Steps:

Navigate to Admin Panel

Click “Add Blog Post”

Enter title, content, and publish
Expected Result: New post is listed in the blog section
Priority: Medium

✅ TC-10: Data Persistence Using localStorage
Preconditions: User schedules a pickup
Test Steps:

Complete pickup form

Reload the page or close and reopen browser
Expected Result: Data persists from localStorage and is reflected in the UI
Priority: Medium
