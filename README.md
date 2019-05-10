# qrcode-js
rebuild with other library for use
From: https://github.com/davidshimjs/qrcodejs

## description

QRCode.js is javascript library for making QRCode. QRCode.js supports Cross-browser with HTML5 Canvas and table tag in DOM. QRCode.js has no dependencies.

## Usage

1. Create html tag for containing QRCode

```html
<div id="qrcode"></div>
```

2. new an instance

```js
new QRCode(document.getElementById('qrcode'), "https://www.google.com/");
```

or with some options

```js
var qrcode = new QRCode(document.getElementById('qrcode'), {
  text: "https://www.google.com/",
  width: 128,
  height: 128,
  colorDark: "#000000",
  colorLight: "#ffffff",
  correctLevel: QRCode.CorrectLevel.H
});
```

3. methods

```js
qrcode.clear(); // clear the code
qrcode.makeCode("http://naver.com"); // make another code
```

## Browser Compatibility

IE6~10, Chrome, Firefox, Safari, Opera, Mobile Safari, Android, Windows Mobile, ETC.

## License

MIT License

## Contact

twitter @davidshimjs