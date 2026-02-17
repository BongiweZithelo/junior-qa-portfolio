# Login Bug Report

## Bug ID: BUG_LOGIN_001
**Title:** User is able to log in with an empty password field

**Environment:**
- Web application
- Browser: Chrome

**Steps to Reproduce:**
1. Open the login page
2. Enter a valid username
3. Leave the password field empty
4. Click the Login button

**Expected Result:**
- The system should display an error message and prevent login.

**Actual Result:**
- The user is logged in successfully and redirected to the home page.

**Severity:** High  
**Priority:** High

**Notes:**
- This issue poses a security risk as authentication validation is bypassed.
