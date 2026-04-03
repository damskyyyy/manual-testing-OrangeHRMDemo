# TC002: Add a new employee in PIM

**Module:** PIM (Personnel Information Management)
**Priority:** High
**Test Type:** Functional

## Preconditions
- User is successfully logged in.
- User is currently on the Dashboard page.

## Test Steps
1. Click on "PIM" from the left-hand navigation menu.
2. Click on the "Add Employee" tab in the top navigation bar.
3. Upload a sample profile picture (optional, but good for testing).
4. Enter "John" in the First Name field.
5. Enter "Doe" in the Last Name field.
6. Notice the automatically generated Employee Id (or simply enter a custom one like `EMP9999`).
7. Click the "Save" button.

## Expected Result
- A success toast message or notification should appear saying "Successfully Saved".
- The user is redirected to the "Personal Details" view for the newly created employee.
- The First Name and Last Name fields should correctly reflect "John" and "Doe".

## Actual Result
- Logged in successfully.
- Navigated to PIM > Add Employee.
- Entered John Doe. Initial Employee ID (0440) was taken. Changed to 19283746.
- Clicked Save. Successfully redirected to Personal Details.
- Employee ID 19283746 verified.

![Add Employee Recording](/assets/screenshots/tc002_add_employee.webp)

## Status
✅ Pass
