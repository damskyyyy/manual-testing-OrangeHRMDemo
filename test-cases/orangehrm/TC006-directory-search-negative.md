# TC006-N: Verify Search Directory for Non-Existent Employee

**Module:** Directory
**Priority:** Low
**Test Type:** Negative / Functional

## Preconditions
- User is logged in.

## Test Steps
1. Navigate to Directory.
2. Enter "Zylx123 NonExistent" in the Employee Name search field.
3. Wait for the result or click "Search".

## Expected Result
- The search result should indicate "No Records Found" or provide a clear message that no employee matches the name.
- No contact cards should be displayed.

## Actual Result
- System marked the name as "Invalid" below the input field and no new cards were rendered.

![Invalid Directory Search Screenshot](/assets/screenshots/tc006n_directory_invalid_search_error.png)

## Status
✅ Pass
