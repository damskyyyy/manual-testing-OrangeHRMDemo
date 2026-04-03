# TC005: Create a new job vacancy in Recruitment

**Module:** Recruitment
**Priority:** Medium
**Test Type:** Functional

## Preconditions
- User is logged in as an Admin or Hiring Manager.
- A valid Job Title exists in the system to link the vacancy to.

## Test Steps
1. Click on "Recruitment" from the left-hand menu.
2. Click on the "Vacancies" tab.
3. Click the "+ Add" button.
4. Enter a Vacancy Name (e.g., "Senior QA Engineer").
5. Select a Job Title from the dropdown.
6. Assign a Hiring Manager by typing and selecting a valid employee name.
7. Enter a Number of Positions (e.g., `3`).
8. Toggle the "Publish in RSS feed and web page" to ON.
9. Click "Save".

## Expected Result
- A success toast message "Successfully Saved" should appear.
- The Vacancy should immediately appear in the Active Vacancies list.

## Actual Result
- Logged in successfully and navigated to Recruitment -> Vacancies.
- Clicked "+ Add" button.
- Filled in form data. First attempt triggered 422 Unprocessable Entity error.
- Reloaded and retried with 'Senior QA Engineer QA99-v2'.
- Saved successfully and confirmed record exists in the Edit Vacancy form.

![Create Vacancy Recording](/assets/screenshots/tc005_create_vacancy.webp)

## Status
✅ Pass
