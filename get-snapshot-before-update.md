**What is the purpose of `getSnapshotBeforeUpdate()` lifecycle method?**

The purpose of **`getSnapshotBeforeUpdate()`** is to capture some information from the DOM before it is potentially changed. This lifecycle method is called right before the browser updates the DOM and it allows you to capture the current scroll position or other information that you might want to use later.