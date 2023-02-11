**When are we using the useMemo hook and why?**

useMemo is a hook that allows you to memoize a value. It is used to optimize the performance of a component by only re-computing a value if its dependencies have changed. This can be useful for avoiding expensive calculations or rendering operations. Here's an example of how to use the useMemo hook:

```
import React, { useMemo } from 'react';

function MyComponent({ data }) {
  const memoizedValue = useMemo(() => {
    // Perform an expensive calculation here, such as filtering an array or computing a value
    return data.filter(item => item > 5);
  }, [data]);

  return (
    <div>
      {memoizedValue.map(item => (
        <p key={item}>{item}</p>
      ))}
    </div>
  );
}
```

In this example, the useMemo hook is used to memoize the result of filtering data so that the calculation is only performed when data changes. The second argument to useMemo is an array of dependencies, in this case [data]. When the dependencies haven't changed, the previous result is returned, avoiding the expensive calculation.



