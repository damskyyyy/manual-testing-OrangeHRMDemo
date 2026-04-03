# TC010: Verify Recruitment Add Candidate

**Module:** Recruitment / Candidates
**Priority:** High
**Test Type:** Functional / Positive

## Preconditions
- User is logged in as Admin or Recruitment Manager.

## Test Steps
1. Navigate to Recruitment > Candidates.
2. Click "+ Add".
3. Enter First Name: "John", Middle Name: "Q", Last Name: "Sample".
4. Enter a valid email: "john.sample@example.com".
5. Select a Vacancy (e.g., "Software Engineer").
6. Click "Save".

## Expected Result
- The candidate should be successfully saved.
- A "Successfully Saved" message should appear.
- Redirect to the Candidate profile or history should occur.

## Actual Result
- Successfully added candidate "John Q Sample" for the "Software Engineer" vacancy.
- Application redirected to the candidate profile page.

![Add Candidate Success](/assets/screenshots/tc010_add_candidate_success.png)

## Status
✅ Pass
