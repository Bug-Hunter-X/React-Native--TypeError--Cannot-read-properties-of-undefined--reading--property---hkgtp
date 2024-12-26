# React Native: TypeError: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common error in React Native applications and its solution.
The error, `TypeError: Cannot read properties of undefined (reading 'property')`, arises when you attempt to access a property of an object that is currently undefined or null.  This often happens when working with asynchronous operations, such as fetching data from an API.

The `bug.js` file shows the problematic code, while `bugSolution.js` provides a corrected version using optional chaining and a loading state.

## Problem
Accessing object properties before the object is fully populated with data leads to this error.  The solution involves using conditional rendering to handle the case where the data is still loading or preventing accessing of the property until it is valid.