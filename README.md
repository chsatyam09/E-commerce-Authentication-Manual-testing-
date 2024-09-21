# E-Commerce Authentication Manual Testing
"Repository showcasing my learning journey with Manual Testing – exploring testing concepts, methodologies, and real-world projects with test cases and reports."

## Project Overview

This repository showcases manual testing for the **Authentication Module** of an e-commerce application. 
The authentication process includes features like User Registration, Login, Password Reset,  and Logout.
 The aim of this project is to ensure that the authentication functionalities work as intended and meet the specified requirements.

## Features Tested

1. **User Registration**
   - New user sign-up
   - Field validation (username, email, password, etc.)
   - Email verification

2. **User Login**
   - Valid user login with correct credentials
   - Invalid login attempts (wrong username or password)
   - Field validation and error messages

3. **Password Reset**
   - Forgot password functionality
   - Email verification for password reset
   - Reset password workflow

4. **Logout**
   - User logout from the system
   - Session invalidation after logout

## Testing Methodology

The following testing methodologies were applied:

- **Functional Testing:** Ensuring each feature works as per the requirements.
- **Boundary Value Analysis:** Checking edge cases like minimum and maximum input lengths for username, password, etc.
- **Negative Testing:** Inputting invalid data to check error handling and validation.
- **Regression Testing:** Ensuring that new updates do not break existing functionality.

## Test Scenarios

1. **User Registration**
   - Verify registration with valid details.
   - Verify error message for missing mandatory fields.
   - Validate error message for an already registered email.
   - Check weak password validation (e.g., password length less than 6 characters).

2. **User Login**
   - Verify login with valid credentials.
   - Verify error message for invalid credentials.
   - Check login after password reset.
   - Verify session timeout after a period of inactivity.

3. **Password Reset**
   - Verify password reset flow using a registered email.
   - Verify error message for unregistered email.
   - Validate the strength of the new password.

4. **Logout**
   - Verify that a logged-in user can log out.
   - Check if the session is properly invalidated after logout.
   - Verify login is required again after logging out.

## Tools Used

- **Jira**: For tracking bugs and managing test cases.
- **Excel/Google Sheets**: For writing and organizing test cases.
- **Manual Testing**: No automation is used in this project.

## Bug Tracking

All discovered bugs during the testing phase have been logged and tracked using **Jira**. Bugs are categorized based on severity and priority.

## Test Documentation

1. **Test Plan**: Details the scope, approach, resources, and schedule of the testing activities.
2. **Test Scenrio**: 
3. **Test Cases**: Covers step-by-step test cases for all scenarios in the authentication module.


## Conclusion

This repository serves as a comprehensive guide to manual testing for the authentication module of an e-commerce system. The test cases ensure that the system is robust, secure, and user-friendly.

## Future Enhancements

- **Automation Testing:** Planning to automate the test cases using Selenium WebDriver.
- **Performance Testing:** Checking the performance of the authentication module under high traffic.
- **Security Testing:** Ensuring strong encryption and secure handling of user credentials.

---

### Author

**[Satyam Raj ]**  
Manual Tester  (Learning Automation Tetsing )


---

Thank you for visiting this repository. Feel free to contribute or raise issues!
