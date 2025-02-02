# React Native useState Type Error: Incompatible State Update

This repository demonstrates a less common but potentially problematic error in React Native applications: a type error stemming from incompatible updates to state variables managed using the `useState` hook.  The issue arises when the new value assigned to a state variable using `setCount` differs in type from its initial value.

The `bug.js` file illustrates the problematic code.  The `bugSolution.js` file provides a corrected version that demonstrates how to prevent this error using type checking and careful handling of state updates.

This type of error, while less frequent due to React Native's less strict type system compared to TypeScript, can lead to unexpected behavior and crashes. Understanding and addressing it is crucial for building robust and reliable React Native applications.