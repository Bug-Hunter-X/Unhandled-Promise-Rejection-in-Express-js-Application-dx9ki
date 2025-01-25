# Unhandled Promise Rejection in Express.js

This repository demonstrates a common error in Express.js applications: neglecting to handle promise rejections in asynchronous operations.  Failure to handle such rejections can lead to unexpected application crashes or, worse, silent failures without any indication to the user or developer.

The `bug.js` file showcases the problematic code, while `bugSolution.js` presents the corrected version with comprehensive error handling.

## How to reproduce

1. Clone this repository.
2. Navigate to the directory: `cd unhandled-promise-rejection`
3. Install dependencies: `npm install express`
4. Run the buggy application: `node bug.js`
5. Observe the behavior (it may crash or produce no output on error).
6. Run the fixed application: `node bugSolution.js`
7. Note that the fixed version handles errors gracefully.