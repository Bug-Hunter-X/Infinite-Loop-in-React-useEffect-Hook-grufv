# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React applications: an infinite loop caused by an incorrectly used `useEffect` hook. The component tries to update the count state within the useEffect's callback, leading to a continuous re-render cycle.  The solution demonstrates the correct usage of dependency arrays in `useEffect` to prevent this issue.