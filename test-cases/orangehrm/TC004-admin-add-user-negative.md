# TC004-N: Verify Password Mismatch for System User

**Module:** Admin / User Management
**Priority:** Medium
**Test Type:** Negative / Functional

## Preconditions
- User is logged in as Admin.
- User is on the "Add User" form.

## Test Steps
1. Navigate to Admin > User Management > Users.
2. Click "+ Add".
3. Enter "TestAdmin@123" in the Password field.
4. Enter "TestAdmin@456" in the Confirm Password field.
5. Fill in other mandatory fields (User Role, Status, Employee Name, Username).
6. Click "Save".

## Expected Result
- User should NOT be successful in saving the record.
- A "Passwords do not match" or similar error should appear below the Confirm Password field.

## Actual Result
- "Passwords do not match" message appeared below the Confirm Password field.
- Save button did not proceed with record creation.

![Password Mismatch Screenshot](/assets/screenshots/tc004n_admin_password_mismatch_error.png)

## Status
✅ Pass
