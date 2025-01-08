# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.

The `bug.js` file shows a route handler that attempts to parse a user ID from the request parameters.  However, it lacks proper error handling if the user ID is not a valid integer. This can lead to unexpected behavior or even crashes.

The `bugSolution.js` file provides a corrected version with robust error handling, demonstrating how to gracefully handle invalid user IDs and return appropriate error responses.