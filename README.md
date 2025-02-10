# React Router Dom v6 Catch-all Route Issue

This repository demonstrates a common issue encountered when using catch-all routes (`/*`) in React Router Dom v6.  The catch-all route unexpectedly matches even when other routes should be taking precedence.  The solution shows how to correctly structure routes to avoid this problem.

## Problem

The provided `App.js` demonstrates the issue.  The `/*` route intended for 404 handling is always triggered, regardless of the URL.  This prevents other routes from correctly matching.