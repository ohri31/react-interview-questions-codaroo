**What will happen if you use `setState()` in constructor?**

If you use **`setState`** in the constructor, it will cause the component to re-render before it is added to the DOM. This can cause unexpected behavior and should be avoided. Instead, it is recommended to initialize the state with the constructor's props and use **`setState`** in **`componentDidMount`**.