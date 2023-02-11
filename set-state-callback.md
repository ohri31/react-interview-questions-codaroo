**What is the purpose of callback function as an argument of `setState()`?**

The callback function passed as an argument to **`setState`** is called after the state has been updated and the component has re-rendered. It can be used to perform any additional actions, such as sending a network request, that depend on the updated state.