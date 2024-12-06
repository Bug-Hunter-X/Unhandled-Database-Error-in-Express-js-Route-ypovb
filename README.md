# Unhandled Database Error in Express.js Route

This repository demonstrates a common error in Express.js applications: the lack of proper error handling when interacting with databases. The `bug.js` file shows a route handler that does not handle potential errors during database operations.  The `bugSolution.js` file provides a corrected version with robust error handling.

## Bug
The original code omits error handling, which could lead to unhandled exceptions and application crashes if the database query fails.

## Solution
The solution includes explicit error checking and appropriate responses to prevent application crashes and provide informative error messages to the client.