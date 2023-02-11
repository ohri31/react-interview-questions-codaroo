**Can you explain the useEffect hook with examples?**
The useEffect hook allows you to run side effects, such as fetching data or updating the DOM, in a functional component. It takes a callback function as its first argument, which is called after the component has rendered. Here's an example of how to use the useEffect hook:

```
import React, { useState, useEffect } from 'react';

const ExampleComponent = () => {
  const [count, setCount] = useState(0);

  useEffect(() => {
    document.title = `Count: ${count}`;
  }, [count]);

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>Click me</button>
    </div>
  );
};
```

export default ExampleComponent;
In this example, the useEffect hook is used to update the document title whenever the count state changes. The hook takes a callback function as its first argument, which is called after the component has rendered. The second argument to the hook is an array of dependencies, which determines when the hook should re-run. In this case, the hook only re-runs when the count state changes.