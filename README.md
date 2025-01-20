# React Router DOM v6 Nested Route Parameter Bug

This repository demonstrates a bug in React Router DOM v6 where using route parameters in nested routes can lead to unexpected errors.

The bug occurs when a route parameter is used within a nested route. The error message is often unclear, making it difficult to diagnose the issue.

## Reproduction

1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Navigate to `/users/1`. You will see the error.

## Solution

The solution involves using the `useParams` hook to access the route parameter within the nested route component. This ensures that the parameter is correctly handled by React Router.