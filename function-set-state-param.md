**Why do we need to pass a function to setState()?**

We need to pass a function to **`setState()`** instead of an object because **`setState()`** is asynchronous, it batches multiple calls together and it only updates the component once. By passing a function, we ensure that the latest state is used when the component re-renders.