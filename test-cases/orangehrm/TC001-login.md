# TC001: Verify Admin Login functionality

**Module:** Authentication
**Priority:** High
**Test Type:** Functional

## Preconditions
- OrangeHRM demo site is accessible.
- Valid admin credentials are known (`Admin` / `admin123`).

## Test Steps
1. Open the browser and navigate to `https://opensource-demo.orangehrmlive.com/web/index.php/auth/login`
2. Enter `Admin` in the Username field.
3. Enter `admin123` in the Password field.
4. Click on the "Login" button.

## Expected Result
- User should be successfully logged in and redirected to the Dashboard page (`/web/index.php/dashboard/index`).
- The profile picture and "Dashboard" title should be clearly visible in the header.

## Actual Result
- Successfully navigated to the login page.
- Entered credentials for Admin.
- Logged in successfully and dashboard loaded in about 3-4 seconds. Profile picture and "Dashboard" title were visible.

![Dashboard screenshot](/assets/screenshots/orangehrm_dashboard.png)

## Status
✅ Pass
