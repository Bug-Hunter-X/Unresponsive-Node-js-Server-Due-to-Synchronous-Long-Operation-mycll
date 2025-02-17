# Unresponsive Node.js Server

This repository demonstrates a common Node.js issue: an unresponsive server caused by a long-running synchronous operation within the request handler.  The provided `server.js` file contains a simple HTTP server that simulates a time-consuming task, blocking the event loop and making the server unresponsive.

The solution, `serverSolution.js`, demonstrates how to address this using asynchronous programming with promises or async/await to prevent blocking the event loop.