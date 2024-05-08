# User Management v1 Project Report

## Challenges and Solutions

### 1. The Case of the Confusing Error Messages (Character Limit Issue #7)
- [Issue #7: Character Limit](https://github.com/k-0016/user_management_v1/issues/7)
- *Problem:* Users exceeded the character limit in a form field and were greeted with confusing error messages.

### 2. Ghosting Errors (Email Uniqueness Issue #6)
- [Issue #6: Email Uniqueness](https://github.com/k-0016/user_management_v1/issues/6)
- *Problem:* Users trying to update their email addresses encountered silent errors when the new email was already taken.

### 3. When Numbers Go Negative (List User Issue #5)
- [Issue #5: List User](https://github.com/k-0016/user_management_v1/issues/5)
- *Problem:* Providing a negative number to the user listing function caused the API to freeze without explanation.

### 4. Blank Passwords: A Security Nightmare (Registration Issue #4)
- [Issue #4: Registration](https://github.com/k-0016/user_management_v1/issues/4)
- *Problem:* Some users were able to register with blank passwords, presenting a major security risk.

### 5. The Broken Email Verification Saga (Issue #2)
- [Issue #2: Email Verification](https://github.com/k-0016/user_management_v1/issues/2)
- *Problem:* Email verification issues ranged from emails not being sent to verification tokens not working.

## Project Features Implemented

### Robust User Search and Filtering
- Implemented a search and filtering system, allowing administrators to find users based on nickname, email, role, and status.
- Added sorting and pagination functionalities to streamline navigation.
- Sorting by sort_key with both ascending and descending ordering.
- Comprehensive test cases are included to ensure the feature works reliably.

### Implementation Branch
The branch containing the search and filtering feature implementation can be found here:  
- [User Search Feature Branch](https://github.com/k-0016/user_management_v1/tree/user-search-feature)

### Full Project Report
For a more detailed overview of the project and additional documentation, refer to the full report available here:
- [Full Project Report](https://github.com/k-0016/user_management_v1/blob/main/Report.docx)

### Conclusion
A total of 108 test cases were passed, 93 original and 15 created to test issues and feature functionality. These changes and improvements have made the user management system more user-friendly, secure, and efficient. Tackling these challenges head-on with refined error handling and validation has made the project more resilient and user-centric.
