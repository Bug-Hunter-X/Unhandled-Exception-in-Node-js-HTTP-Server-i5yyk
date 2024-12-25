# Node.js Unhandled Exception Example

This repository demonstrates an example of an unhandled exception in a Node.js HTTP server and how to properly handle it.

## Bug

The `bug.js` file contains a simple HTTP server that throws an unhandled exception if the request URL is '/error'. This leads to the server crashing without proper error handling or logging.

## Solution

The `bugSolution.js` file demonstrates how to properly handle the exception using a `try...catch` block and logging the error to the console.  This prevents the server from crashing and allows for graceful error handling.  Additionally, it provides a more informative response to the client.