# TC006: Search for an employee in the Directory

**Module:** Directory
**Priority:** Low
**Test Type:** Functional

## Preconditions
- User is logged in.
- Multiple employees exist in the organization.

## Test Steps
1. Click on "Directory" from the left-hand navigation menu.
2. In the "Employee Name" search box, type the first few letters of an existing employee (e.g., "Odis").
3. Select the matching name from the autocomplete dropdown.
4. Select a specific "Job Title" from the dropdown (e.g., "Chief Executive Officer").
5. Click the "Search" button.

## Expected Result
- The directory grid should refresh and display only the contact cards matching the criteria.
- Clicking on the contact card should bring up their professional details natively.

## Actual Result
- Logged in successfully and navigated to Directory.
- Searched for "Odis".
- System returned "No Records Found" and marked the input as "Invalid".
- Verified that "Odis Adalwin" does not exist in the current demo environment data.

![Directory Search Recording](/assets/screenshots/tc006_directory_search.webp)

## Status
❌ Fail (Data not found in demo environment)
