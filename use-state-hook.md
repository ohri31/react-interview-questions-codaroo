**Can you explain the useState hook with examples?**
The useState hook allows you to add state to a functional component. It returns an array with two values: the current state and a function to update it. Here's an example of how to use the useState hook:

```
const [count, setCount] = useState(0);

<p>You clicked {count} times</p>
<button onClick={() => setCount(count + 1)}>
  Click me
</button>```
