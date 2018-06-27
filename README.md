# IBM Northstar Colors

Minimalist module with [IBM's Northstar color palette](https://www.ibm.com/standards/web/design/color-palette/).

## Installation

```shell
npm install ibm-northstar-colors -S
```

## Usage

Apply colors individually.

```javascript
const palette = require('ibm-northstar-colors').colors;
const backgroundColor = palette.blue90;
```

Apply colors from a grade (core, 10, 20, 30, 40, 50, 60, 70, 80, 90).

```javascript
const palette = require('ibm-northstar-colors').grade50;
const red = palette.red;
const green = palette.green;
const yellow = palette.yellow;
const blue = palette.blue;
```

## License

MIT