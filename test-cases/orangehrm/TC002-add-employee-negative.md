# TC002-N: Verify Validation for Missing Mandatory fields in PIM

**Module:** PIM
**Priority:** Medium
**Test Type:** Negative / Functional

## Preconditions
- User is logged in.
- User is on the "Add Employee" form.

## Test Steps
1. Navigate to PIM > Add Employee.
2. Enter "John" in the First Name field.
3. Leave the Last Name field empty.
4. Click "Save".

## Expected Result
- User should NOT be successful in saving the record.
- "Required" or similar validation error should appear below the Last Name field.
- Red highlight should indicate the error state.

## Actual Result
- Red "Required" message appeared below the Last Name field.
- Record was not saved.

![Missing Last Name Screenshot](/assets/screenshots/tc002n_pim_missing_lastname_error.png)

## Status
✅ Pass
