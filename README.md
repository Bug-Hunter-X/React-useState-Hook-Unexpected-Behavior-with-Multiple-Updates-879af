# React useState Hook Unexpected Behavior
This example demonstrates a potential issue when using the `useState` hook in React.  If you update the state multiple times synchronously using a value derived from the previous state, you might observe unexpected behavior. The second `setCount` call overwrites the first one resulting in incorrect update. 

## How to reproduce
1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Observe that clicking the increment button does not produce expected result.