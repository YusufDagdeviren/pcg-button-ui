# pcg-button-ui

> different button react components

[![NPM](https://img.shields.io/npm/v/pcg-button-ui.svg)](https://www.npmjs.com/package/pcg-button-ui) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm i pcg-button-ui
```
[Npmjs Link](https://www.npmjs.com/package/pcg-button-ui)

## Usage

```jsx
import React from 'react'

import { Button } from 'pcg-button-ui'
import 'pcg-button-ui/dist/index.css'

const App = () => {
  return(
  <>
    <Button text="Text Button" type="text"/>
    <br /><br />
    <Button text="Default Button" type="default"/>
    <br /><br />
    <Button text="Dashed Button" type="dashed"/>
    <br /><br />
    <Button text="Primary Button" type="primary"/>
    <br /><br />
    <Button text="Link Button" type = "link"/>
  </>
  )
}

export default App
```

## License

MIT © [YusufDagdeviren](https://github.com/YusufDagdeviren)