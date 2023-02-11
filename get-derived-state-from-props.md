**What is the purpose of `getDerivedStateFromProps()` lifecycle method?**

The purpose of **`getDerivedStateFromProps()`** is to provide a way to synchronize a component's internal state with its props. This lifecycle method is called before **`render()`** and it allows you to update the internal state based on changes in the props. It is used as an alternative to **`componentWillReceiveProps()`**