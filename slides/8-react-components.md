<!-- section-title: React Components -->

# React Components

You can import your React Components into the `.mdx` files and use them as in a normal React project.

Let's create a `src` folder in the root of your project folder, inside we'll create a folder called `components` and a file called `Counter.js`

Inside `Counter.js` we paste the following example code:

```js
import React, { useState } from "react";

const Counter = () => {
  const [count, setCount] = useState(0);

  return (
    <div className="react-component">
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>Click me!</button>
      <button onClick={() => setCount(0)}>Reset</button>
    </div>
  );
};

export default Counter;
```

---

And inside of your `.mdx` file:

```md
import Counter from '../src/components/Counter';

<Counter />
```

You now have a React Component working directly on the slide, very handy in combination with code blocks to show the source code and the execution of the component.
