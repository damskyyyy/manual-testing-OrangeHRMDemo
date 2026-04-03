# TC005-N: Verify Validation in Create Vacancy

**Module:** Recruitment
**Priority:** Medium
**Test Type:** Negative / Functional

## Preconditions
- User is logged in as Admin or Hiring Manager.
- User is on the Recruitment > Vacancies > Add Vacancy form.

## Test Steps
1. Navigate to Recruitment > Vacancies.
2. Click "+ Add".
3. Leave the Vacancy Name field blank.
4. Fill in other fields (Job Title, Hiring Manager).
5. Click "Save".

## Expected Result
- User should NOT be successful in saving the vacancy.
- A "Required" validation message should appear below the Vacancy Name field.

## Actual Result
- "Required" message appeared below the Vacancy Name field.
- Redirect to the list did not occur; stayed on the same form.

![Missing Vacancy Name Screenshot](/assets/screenshots/tc005n_recruitment_missing_vacancy_name_error.png)

## Status
✅ Pass
