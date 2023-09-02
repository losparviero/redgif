# Redgif

 Download gifs from Redgifs programtically.

### Usage

```js
import { getGif } from "redgif"
```

### Install

```shell
npm i redgif
```

### Methods

### getGif() Generates downloaded gif returned as buffer

#### Params: [gifId]

```js
const buffer = await getGif(gifId)
fs.writeFileSync("redgif.mp4", buffer)
```

### License

AGPL-3.0 ©️ Zubin