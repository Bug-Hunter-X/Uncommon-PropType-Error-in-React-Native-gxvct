# Uncommon PropType Error in React Native

This repository demonstrates an uncommon PropType error in React Native and its solution.  The error arises from passing incorrect data types to a component's props.  This often leads to unexpected behavior or crashes.

## Problem

The `MyComponent` component expects a numeric `count` prop.  The initial implementation passes a string, causing the error.

## Solution

The solution involves passing the correct data type (a number) to the `count` prop.  This ensures the component functions as expected.

## How to reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run the application on an Android emulator or iOS simulator.  Observe the error in `IncorrectPropUsage.js`
4. Then switch to `CorrectPropUsage.js` to see the working example.

This example highlights the importance of carefully checking and matching prop types when building React Native applications to avoid subtle errors.