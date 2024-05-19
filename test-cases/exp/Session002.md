# Exploratory Testing Session

## Session Information
- **Session ID:** Session002
- **Charter:** Explore password reset functionality
- **Tester:** Bob Smith
- **Date:** 2024-05-19
- **Duration:** 2 hours
- **Test Environment:**
  - **Device/Browser:** Firefox
  - **Operating System:** macOS
  - **Version:** 90.0

## Test Notes
### Areas Explored
- Password reset feature

### Test Actions
1. Navigate to the login page.
2. Click "Forgot Password".
3. Enter the registered email address.
4. Check email and click the reset link.
5. Attempt to reset the password.

### Observations
- Password reset emails are sent correctly.
- The password reset link in the email sometimes causes the computer to explode.

## Findings
### Issues/Defects
1. **Defect ID:** [DEF002](../../defects/DEF002.md)
   - **Description:** Resetting the password causes the computer to explode.
   - **Severity:** 
     - [ ] Critical
     - [x] Major
     - [ ] Minor
     - [ ] Trivial
   - **Status:**
     - [x] New
     - [ ] Triaged
     - [ ] In Progress
     - [ ] Fixed
     - [ ] In Review
     - [ ] Resolved
     - [ ] Closed
   - **Related Issue:** [Issue #2](https://github.com/your-repo/issues/2)

### Other Findings
- The password reset flow is mostly functional but critical due to the explosion issue.

## Comments
The password reset functionality works in general, but the intermittent issue with the password reset link causing the computer to explode needs urgent attention.

## Sign-off
### Tester Sign-off
- **Name:** Bob Smith
- **Signature:** B. Smith
- **Date:** 2024-05-19

### Product Owner Sign-off
- **Name:** Jane Doe
- **Signature:** J. Doe
- **Date:** 2024-05-19
