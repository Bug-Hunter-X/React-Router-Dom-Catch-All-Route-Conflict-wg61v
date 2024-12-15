# React Router Dom Catch-All Route Conflict

This repository demonstrates a common issue in React Router v6 where a catch-all route (`/*`) interferes with other, more specific routes.  The catch-all route, intended to handle 404 errors, unintentionally intercepts all navigation attempts, preventing access to other defined paths. 

The `App.js` file contains the buggy code that illustrates the problem. The solution is in `AppSolution.js`.