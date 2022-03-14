## Custom hook for react: useWindowSize

### Install

```yarn add @revolt-digital/use-window-size```

### How to use it?

```
import React from 'react';
import useWindowSize from '@revolt-digital/use-window-size';

export default () => {
    const { width, height } = useWindowSize(); 

    return <div>Hello there!</div>;
};
```
