# TC008-N: Verify Attendance Punch Negative

**Module:** Time / Attendance
**Priority:** Low
**Test Type:** Negative

## Preconditions
- User is logged in.

## Test Steps
1. Navigate to Time > Attendance > Punch In/Out.
2. Attempt to change the Date/Time manually (if editable).
3. If not editable, attempt to click "Punch" multiple times rapidly or with no content in mandatory fields (if any).

## Expected Result
- System should handle any unexpected input or empty note fields according to UI rules.
- If notes are mandatory, it should show a validation error.

## Actual Result
- Entered "99:99" in the time field.
- System automatically cleared the field and displayed a red "Required" validation error.

![Invalid Time Error](/assets/screenshots/tc008n_invalid_time_error.png)

## Status
✅ Pass
