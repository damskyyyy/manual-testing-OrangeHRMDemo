# TC009-N: Verify Performance KPI Creation Negative

**Module:** Performance / KPIs
**Priority:** Medium
**Test Type:** Functional / Negative

## Preconditions
- User is logged in as Admin.

## Test Steps
1. Navigate to Performance > Configure > KPIs.
2. Click "+ Add".
3. Leave "Job Title" field as "-- Select --".
4. Enter "Test Indicator" in the Indicator field.
5. Click "Save".

## Expected Result
- Validation error "Required" should appear below the Job Title dropdown.
- Data should not be saved.

## Actual Result
- Attempted to save with an empty Job Title.
- System displayed "Required" in red below the dropdown.

![KPI Validation Error](/assets/screenshots/tc009n_kpi_validation_error_1775208721905.png)

## Status
✅ Pass
