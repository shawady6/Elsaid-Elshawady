# PWA - السعيد عزت الشوادي

## الملفات
- `index.html`
- `manifest.json`
- `sw.js`
- `icons/icon-192.png`
- `icons/icon-512.png`

## الصور
ضع صور الموقع داخل:
`images/`

وبنفس الأسماء:
`01.jpeg` إلى `234.jpeg`

إذا كانت الصور JPG بدل JPEG، غيّر في `index.html`:
```js
const IMAGE_EXTENSION = ".jpeg";
```
إلى:
```js
const IMAGE_EXTENSION = ".jpg";
```

## رفع التعديلات
```bash
git add .
git commit -m "Convert website to PWA"
git push
```

بعد الـ deploy افتح الموقع من Chrome على الموبايل، وسيظهر خيار تثبيت الموقع عندما يعتبر المتصفح الموقع قابلاً للتثبيت.
