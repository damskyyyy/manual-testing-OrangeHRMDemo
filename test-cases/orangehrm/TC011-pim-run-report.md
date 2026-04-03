# TC011: Verify PIM Sample Report Execution

**Module:** PIM / Reports
**Priority:** Low
**Test Type:** Functional / Positive

## Preconditions
- User is logged in.

## Test Steps
1. Navigate to PIM > Reports.
2. Search for "PIM Sample Report" or locate it in the list.
3. Click the "Run" icon (play icon) for the report.

## Expected Result
- The system should render a data table with employee statistics/records.
- "Displaying Records" should be shown at the bottom.

## Actual Result
- System rendered a data table with 99 employee records.
- Columns like Employee Id, First Name, Last Name, and Date of Birth were visible.

![PIM Sample Report Results](/assets/screenshots/tc011_pim_sample_report_results.png)

## Status
✅ Pass
