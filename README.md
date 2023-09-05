# Redgif

 Download gifs from Redgifs programtically.

 ### Features

 Zero dependencies.

 Gets the highest quality.

 If not, fallback to standard quality.

 Much more stable than scraping methods.

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

gifId refers to the ID extracted from the full URL.

Use the appropriate file extension to save, can be .jpg or .mp4 for example.

### License

AGPL-3.0 ©️ Zubin