# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js where a long-running synchronous operation within the HTTP request handler blocks the event loop, causing the server to become unresponsive.  The `server.js` file contains the problematic code, while `serverSolution.js` provides a solution using asynchronous operations.