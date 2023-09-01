# Redgif

 Download gifs from Redgifs programtically.

### Usage

#### For use in a project

```js
const { getGif } = require("redgif")
```

#### For use in a module

```js
import { getGif } from "redgif"
```

### Install

```shell
npm i redgif
```

### Methods

### getGif() Generates downloaded gif returned as buffer

#### Params: [url]

```js
const buffer = await getGif(gifId)
fs.writeFileSync("redgif.mp4", buffer)
```

### License

AGPL-3.0 ©️ Zubin