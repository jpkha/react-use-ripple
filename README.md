# react-use-ripple

> A react hook to create material design ripples for components

[![NPM](https://img.shields.io/npm/v/react-use-ripple.svg)](https://www.npmjs.com/package/react-use-ripple) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save react-use-ripple
```

## Usage

```tsx
import React from "react";
import { useRipple } from "react-use-ripple";
import { useRef } from "react";

const App = () => {
  const ref = useRef();
  useRipple(ref);

  return (
    <button className="btn" ref={ref}>
      Button
    </button>
  );
};

export default App;
```

## License

MIT © [cbadger85](https://github.com/cbadger85)
