# rn-statusbar-height

[![npm version](https://badgen.net/npm/v/rn-statusbar-height)](https://npm.im/rn-statusbar-height) [![npm downloads](https://badgen.net/npm/dm/rn-statusbar-height)](https://npm.im/rn-statusbar-height)

> A library that gets statusbar height for React Native.
>
> If you found this helpful, don't forget to leave a star 🌟. 

## Installation

```bash
$ npm install --save rn-statusbar-height
# OR
$ yarn add rn-statusbar-height
```

## Usage

```js
import { getStatusBarHeight } from 'rn-statusbar-height'

// 59 - iPhone 14 Pro / 14Pro Max / 15 series
// 47 - iPhone 12 / 12Pro / 13 / 13Pro / 13Pro Max / 14 / 14 Plus
// 44 - on iPhoneX
// 20 - on iOS device
// X - on Android platfrom (runtime value)
// 0 - on all other platforms (default)
console.log(getStatusBarHeight())

// will be 0 on Android, because You pass true to skipAndroid
console.log(getStatusBarHeight(true));
```

## References
[ovr/react-native-status-bar-height](https://github.com/ovr/react-native-status-bar-height)

[The Screen Sizes of iPhones](https://useyourloaf.com/blog/iphone-15-screen-sizes/)

## Contribution

If you want to add some features, feel free to submit PR.

## License

[MIT](LICENSE).