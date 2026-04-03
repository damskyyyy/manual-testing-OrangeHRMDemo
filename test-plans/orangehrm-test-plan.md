# Test Plan: OrangeHRM Open Source Demo

**Prepared by:** QA Tester
**Date:** 2026-04-03

## 1. Introduction
This document outlines the testing strategy for the OrangeHRM demo application. Since this is an exploratory and functional manual testing exercise, the focus is on verifying core user flows that are essential for typical HR operations.

## 2. Testing Scope
**In Scope:**
- Authentication Module (Login / Logout)
- Admin Module (System User Management)
- PIM (Personnel Information Management) - Adding and tracking employees
- Leave Module - Applying for time-off
- Recruitment Module - Vacancy management
- Directory - Finding employee records
- Buzz - Internal social networking posts
- **Negative Testing** - Error message verification, mandatory field validation, and data constraint checks for all modules.

**Out of Scope:**
- Performance and Load testing (it's a public demo site)
- Security testing
- Admin system configurations
- Automated testing (this is strictly a manual effort)

## 3. Test Environment
- **Browser:** Google Chrome (Latest)
- **OS:** MacOS 
- **Environment:** Live Demo Server (https://opensource-demo.orangehrmlive.com)

## 4. Test Strategy
I'll be performing functional testing based on black-box techniques. 
1. **Smoke Testing:** Ensure the app loads, login works, and main menus are accessible.
2. **Functional Testing:** Execute predefined test cases for the PIM and Leave modules.
3. **Exploratory Testing:** Look around the edges of inputs (e.g., leaving mandatory fields blank, checking dropdown behaviors) to find edge cases.

## 5. Deliverables
- Test Plan (this doc)
- Documented Test Cases (in markdown)
- Bug Reports (if issues are found)
- Final Test Execution Summary
