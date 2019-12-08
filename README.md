# styled-modern-css-reset

A styled-component wrapper for [modern-css-reset](https://github.com/hankchizljaw/modern-css-reset).

## Installation

```bash
npm install styled-modern-css-reset
```

## Usage

In the root component:

```jsx
import Reset from "styled-modern-css-reset";
import React, { Fragment } from "react";

export default () => (
  <Fragment>
    <Reset />

    <h1>Hello, World!</h1>
  </Fragment>
);
```

Alternatively, along with your app's global styles:

```js
import { reset } from "styled-modern-css-reset";
import { createGlobalStyle } from "styled-components";
import React from "react";

const globalStyles = createGlobalStyle`
  ${reset}

  // Other styles...
`;
```

## Hugs

[Andy Bell](https://twitter.com/hankchizljaw) — [modern-css-reset](https://hankchizljaw.com/wrote/a-modern-css-reset/)
