# TC009: Verify Performance KPI Creation

**Module:** Performance / KPIs
**Priority:** Medium
**Test Type:** Functional / Positive

## Preconditions
- User is logged in as Admin.

## Test Steps
1. Navigate to Performance > Configure > KPIs.
2. Click "+ Add".
3. Select a Job Title (e.g., "Account Assistant").
4. Enter a KPI name (e.g., "Manual Test - Performance Index").
5. Set Minimum Rating to 1 and Maximum Rating to 10.
6. Click "Save".

## Expected Result
- A "Successfully Saved" message should appear.
- The new KPI should be listed in the KPI table for the "Account Assistant" job title.

## Actual Result
- System successfully saved the KPI "Manual Test - Performance Index" for the job title "Account Assistant".
- Verified the record in the KPI list.

![KPI Success](/assets/screenshots/tc009_performance_kpi_success.png)

## Status
✅ Pass
