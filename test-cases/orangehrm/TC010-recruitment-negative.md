# TC010-N: Verify Recruitment Add Candidate Negative

**Module:** Recruitment / Candidates
**Priority:** Medium
**Test Type:** Functional / Negative

## Preconditions
- User is logged in.

## Test Steps
1. Navigate to Recruitment > Candidates.
2. Click "+ Add".
3. Enter "InvalidEmail" (without @ or .) in the Email field.
4. Fill in other mandatory fields.
5. Click "Save".

## Expected Result
- Validation message "Expected format: admin@example.com" or similar should appear below the Email field.
- Data should not be saved.

## Actual Result
- Entered "InvalidMail" in the email field.
- System threw an immediate "Expected format: admin@example.com" error.

![Candidate Email Error](/assets/screenshots/tc010n_candidate_email_error.png)

## Status
✅ Pass
