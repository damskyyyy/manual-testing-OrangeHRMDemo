# TC001-N: Verify Login with Invalid Credentials

**Module:** Authentication
**Priority:** High
**Test Type:** Negative / Functional

## Preconditions
- OrangeHRM demo site is accessible.

## Test Steps
1. Navigate to the login page.
2. Enter "Admin" in the Username field.
3. Enter "wrongpassword123" in the Password field.
4. Click the "Login" button.

## Expected Result
- User should NOT be logged in.
- An error message "Invalid credentials" should be displayed in a red callout.
- No navigation to the Dashboard should occur.

## Actual Result
- Error message "Invalid credentials" appeared in a red alert box at the top.
- No navigation to the dashboard occurred.

![Invalid Credentials Screenshot](/assets/screenshots/login_invalid_credentials_error.png)

## Status
✅ Pass
