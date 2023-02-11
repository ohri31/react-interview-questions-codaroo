**How to create refs?**
To create a ref, you can use the **`useRef`** hook, which returns a ref object. You can then assign this object to a ref attribute on a JSX element. Here's an example:

```
import React, { useRef } from 'react';

function Example() {
  const inputRef = useRef(null);

  const handleClick = () => {
    inputRef.current.focus();
  };

  return (
    <div>
      <input type="text" ref={inputRef} />
      <button onClick={handleClick}>Focus the input</button>
    </div>
  );
}
```