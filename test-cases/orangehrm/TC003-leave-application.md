# TC003: Apply for Annual Leave

**Module:** Leave Management
**Priority:** Medium
**Test Type:** Functional

## Preconditions
- User is logged in.
- Employee exists and has a leave entitlement configured in the system.

## Test Steps
1. Click on "Leave" from the left-hand navigation menu.
2. Click on "Apply" in the top menu bar.
3. Select "CAN - FMLA" (or any available valid option) from the Leave Type dropdown.
4. Select a From Date (e.g., tomorrow's date using the date picker).
5. Select a To Date (e.g., the day after tomorrow).
6. Enter "Taking some personal time off for family matters" in the Comments field.
7. Click the "Apply" button.

## Expected Result
- A success toast message should appear ("Successfully Saved/Applied").
- The page should reload or navigate to My Leave to confirm the leave request is recorded as "Pending Approval".
- The balance in the leave balance indicator should decrease accordingly.

## Actual Result
- Logged in successfully and navigated to Leave -> Apply.
- User had no leave balance initially. Navigated to Entitlements > Add Entitlements to add 20 days of CAN - FMLA.
- Returned to Apply, filled out CAN - FMLA from 2026-10-05 to 2026-12-05.
- Submitted application and form saved successfully.
- Record appears under "My Leave" with "Pending Approval" status.

![Leave Application Recording](/assets/screenshots/tc003_leave_application.webp)

## Status
✅ Pass
