# React Router v6 useParams Hook Issue

This repository demonstrates a common error in React Router v6 where the `useParams` hook returns `undefined` when used outside of a route component. The error occurs when attempting to access route parameters in a component that isn't directly nested within a route defined by `<Route path="...">`.

The `bug.js` file showcases the incorrect usage, resulting in the error.  The `bugSolution.js` file provides the correct implementation.