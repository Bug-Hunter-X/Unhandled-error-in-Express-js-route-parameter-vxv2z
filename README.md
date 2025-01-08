# Express.js Route Parameter Error Handling

This repository demonstrates a common error in Express.js route handlers: failure to handle invalid input in route parameters.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides the corrected version with robust error handling.

**Problem:**
The original code lacks checks for the validity of the `userId` parameter, making the app vulnerable to crashes when non-numeric IDs are used. 

**Solution:**
The corrected code incorporates input validation and error handling to gracefully manage invalid `userId` values, preventing app crashes and returning appropriate HTTP error responses.