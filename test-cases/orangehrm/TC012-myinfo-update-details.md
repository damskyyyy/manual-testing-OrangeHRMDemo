# TC012: Verify My Info Personal Details Update

**Module:** My Info
**Priority:** Medium
**Test Type:** Functional / Positive

## Preconditions
- User is logged in.

## Test Steps
1. Navigate to "My Info" in the main menu.
2. Click on "Personal Details".
3. Modify the "Other Id" field (e.g., "AG Tester").
4. Select/Modify "Marital Status" (e.g., "Single").
5. Click "Save".

## Expected Result
- A success toast message "Successfully Saved" should appear.
- Redirect/Reload should show the updated information.

## Actual Result
- Successfully updated "Other Id" to "AG Tester" and "Marital Status" to "Single".
- A success toast message was displayed.

![My Info Profile Update](/assets/screenshots/tc012_my_info_update_profile.png)

## Status
✅ Pass
