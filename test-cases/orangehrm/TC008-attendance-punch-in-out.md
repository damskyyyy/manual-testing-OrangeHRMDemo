# TC008: Verify Attendance Punch Out/In

**Module:** Time / Attendance
**Priority:** High
**Test Type:** Functional / Positive

## Preconditions
- User is logged in.

## Test Steps
1. Navigate to Time > Attendance > Punch In/Out.
2. Observe the current status (e.g., "Punched In" or "Punched Out").
3. Enter a note (e.g., "Manual Testing - Antigravity").
4. Click the "Punch Out" or "Punch In" button.

## Expected Result
- The system should successfully record the action.
- A success toast message "Successfully Saved" should appear.
- The button should toggle to the next state (e.g., if Punched Out, next state should be Punch In).

## Actual Result
- System successfully recorded the Punch Out action with the note "Manual Testing - Antigravity Phase 2".
- Application redirected to the Punch In form.

![Punch Out Success](/assets/screenshots/tc008_punch_out_success_state.png)

## Status
✅ Pass
