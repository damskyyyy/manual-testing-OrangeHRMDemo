# TC004: Add a new system user in Admin

**Module:** Admin
**Priority:** High
**Test Type:** Functional

## Preconditions
- User is logged in as Admin.
- User is on the Dashboard page.

## Test Steps
1. Click on "Admin" from the left-hand navigation menu.
2. In the "User Management" section, navigate to "Users".
3. Click the "+ Add" button.
4. Select "Admin" or "ESS" under User Role.
5. In the "Employee Name" autocomplete field, type "John" and select a valid employee from the dropdown list.
6. Set Status to "Enabled".
7. Enter a unique Username (e.g., `testadmin99`).
8. Enter a valid Password (e.g., `TestAdmin@123`) and confirm the password.
9. Click "Save".

## Expected Result
- A success toast message "Successfully Saved" should appear.
- User should be redirected to the System Users grid.
- The newly created user `testadmin99` should be visible in the list and searchable.

## Actual Result
- Logged in successfully and navigated to Admin -> User Management.
- Clicked "+ Add" button.
- Registered Admin role for an existing employee (Auto AdminOne...).
- Inputted unique username testadmin8821 with a valid password.
- Saved successfully. Searching for testadmin8821 in the grid successfully returns the newly created User.

![Add System User Recording](/assets/screenshots/tc004_admin_add_system_user.webp)

## Status
✅ Pass
