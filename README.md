# react-native-vision-camera-v3-barcode-scanner

The frame processor plugin for scanning barcodes using Google ML Kit library for react-native-vision-camera with high performance.

## 🚨 Required Modules

| Module | Version |
| :---: | :---: |
| react-native-vision-camera | 4.0.0 |
| react-native-worklets-core | 1.2.0 |

## 💻 Installation

```sh
npm install react-native-vision-camera-v3-barcode-scanner
yarn add react-native-vision-camera-v3-barcode-scanner
```

## 👷Features

- [X] Easy To Use.
- [X] Works Just Writing few lines of Code.
- [X] Works With React Native Vision Camera.
- [X] Works for Both Cameras.
- [X] Works Fast.
- [X] Works With Android 🤖 and IOS.📱
- [X] Written With Kotlin and Objective-C.

## 💡 Usage

```js
import { Camera } from 'react-native-vision-camera-v3-barcode-scanner';

const [barcodes,setBarcodes] = useState(null)

console.log(barcodes)

<Camera
  options={{
    codeType: "all",
    }}
  style={StyleSheet.absoluteFill}
  device={device}
  callback={(data) => setBarcodes(data)}
  {...props}
/>
```

---

## ⚙️ Options

| Name |  Type    |  Values  | Default |
| :---:   | :---: | :---: |  :---: |
| codeType | String  | all, code-39, code-93, codabar, ean-13, ean-8, itf, upc-e, upc-a, qr, pdf-417, aztec, data-matrix, code-128 | all |
