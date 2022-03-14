## Custom hook for react: useWindowSize

### How to use it?

```
import React from 'react';
import useWindowSize from '@revolt-digital/use-window-size';

export default () => {
    const { width, height } = useWindowSize(); 

    return <div>Hello there!</div>;
};
```

### Integrate

```yarn add @revolt-digital/use-window-size```

The lib was made in typescript.
So, to integrate it add in your tsconfig.json that line:

```
{
  "compilerOptions": {
    ...
  },
  "include": [
    ...
    "node_modules/@revolt-digital/use-window-size/**.ts"
  ],
  "exclude": ["node_modules"]
}

```
