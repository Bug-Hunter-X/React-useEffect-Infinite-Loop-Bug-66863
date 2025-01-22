# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook.  The `useEffect` hook, without a dependency array, runs after every render, potentially leading to infinite loops and performance issues. This example shows how to fix it.

## Bug
The `bug.js` file contains a React component with a `useEffect` hook that lacks a dependency array. This causes the effect to run on every render, leading to an infinite loop, resulting in continuous re-renders and console logging.