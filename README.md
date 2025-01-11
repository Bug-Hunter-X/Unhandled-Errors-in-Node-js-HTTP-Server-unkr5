# Unhandled Errors in Node.js HTTP Server

This repository demonstrates a common error in Node.js applications: lack of proper error handling in HTTP servers.  The initial `bug.js` file shows a server without error handling. The `bugSolution.js` demonstrates improved error handling using `try...catch` blocks and event listeners for `'error'` events.