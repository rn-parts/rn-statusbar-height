# rn-statusbar-height

> A library that gets statusbar height for React Native

## Installation

```bash
$ npm install --save rn-statusbar-height
# OR
$ yarn add rn-statusbar-height
```

## Usage

```js
import { getStatusBarHeight } from 'rn-statusbar-height'

// 59 - on iPhone 14 (PRO)
// 47 - on iPhone 12 (Max)
// 44 - on iPhone X
// 20 - on iOS device
// X - on Android platfrom (runtime value)
// 0 - on all other platforms (default)
console.log(getStatusBarHeight())
```

## Contribution

If you want to add some features, feel free to submit PR.

## License

[MIT](LICENSE).