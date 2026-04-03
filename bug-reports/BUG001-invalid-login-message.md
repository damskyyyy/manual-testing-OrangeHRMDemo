# BUG001: Missing field validation styling on empty login

**Status:** Open
**Severity:** Minor
**Environment:** Chrome Latest on MacOS

## Description
When a user attempts to log in without entering a username or password, the inline error message "Required" appears properly below the fields. However, the input field border doesn't turn red to indicate an error state in standard UX patterns, which can sometimes make the error less obvious if the user tabs away quickly.

## Steps to Reproduce
1. Navigate to the login page (`/web/index.php/auth/login`).
2. Leave both Username and Password fields completely blank.
3. Click the "Login" button.

## Expected Behavior
- Both input fields should display a red border or some visual highlight, and focus should ideally drop back to the first missing mandatory field (Username), in addition to the "Required" text.

## Actual Behavior
- The "Required" text is shown, but focus is lost, and the border highlight of the input field remains its neutral state.

## Workaround
- The user can still just click the field and type. It's a minor UX inconsistency rather than a functional blocker.

## Attachments
- *(Placeholder for screenshot here)* -> `assets/screenshots/bug001-empty-login.png` 
