# Missing Return Statement in Next.js 15 Functional Component

This repository demonstrates a common error in Next.js 15: a missing `return` statement in a functional component.  Next.js 15's stricter error handling will throw an error if a functional component doesn't explicitly return JSX. 

## Bug
The `pages/about.js` file contains a functional component that omits a `return` statement. This causes a runtime error when the `/about` route is accessed.

## Solution
The `pages/aboutSolution.js` file demonstrates the corrected code.  Adding a `return` statement with valid JSX resolves the issue.

This simple example highlights the importance of carefully reviewing your components to ensure all functional components properly return JSX.  