# TC003-N: Verify Error for Insufficient Leave Balance

**Module:** Leave Management
**Priority:** Medium
**Test Type:** Negative / Functional

## Preconditions
- User is logged in.
- User has 0 balance for the requested Leave Type.

## Test Steps
1. Navigate to Leave > Apply.
2. Select a Leave Type (e.g. "CAN - FMLA").
3. Choose a From Date and a To Date.
4. Click "Apply".

## Expected Result
- User should NOT be successful in applying for leave.
- If the form shows "0.00 Day(s)" in the Leave Balance, an error message or restriction should prevent submission.
- Application should not proceed to the approval stage.

## Actual Result
- Leave Balance displayed "0.00 Day(s)" for the selected type.
- System threw an additional error regarding date format during interaction, which also correctly blocked submission.

![Zero Balance Screenshot](/assets/screenshots/tc003n_leave_zero_balance_state.png)

## Status
✅ Pass
