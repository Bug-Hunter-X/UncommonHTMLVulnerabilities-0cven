# Uncommon HTML Bugs
This repository demonstrates two uncommon but important HTML bugs:

1. **Accessing Non-Existent Properties:**  Attempting to access a property that doesn't exist on a dynamically created element might not throw an immediate error, but could lead to unexpected behavior (undefined values) and subtle bugs.
2. **Insecure Use of `innerHTML`:** Directly using user input with `innerHTML` creates a significant cross-site scripting (XSS) vulnerability.  Sanitization is crucial to prevent this security risk.

The `bug.html` file shows the buggy code.  `bugSolution.html` demonstrates how to address these issues.