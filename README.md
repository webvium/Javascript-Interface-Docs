# Documentation

### Check if Webvium Object undefined or not
```js
if (!(Webvium === undefined)) {
    // Webvium Browser
} else {
    // Other browser, or the interface is disabled
}
```

---------------------------------------

### Webvium.showToast(message)

Show a normal toast message to the user.

__Arguments__

* `message` - The message you want to show.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.showToast("Hello World");
}
```

---------------------------------------

### Webvium.showToast(message, delay)

Show a normal toast message to the user with custom delay.

__Arguments__

* `message` - The message you want to show.
* `delay` - Either 0 or 1. Default is 0.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.showToast("Hello World", 0);
}
```

---------------------------------------

### Webvium.showToastError(message)

Show a red toast message to the user.

__Arguments__

* `message` - The message you want to show.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.showToastError("An Error Occured.");
}
```

---------------------------------------

### Webvium.showToastError(message, delay)

Show a red toast message to the user with custom delay.

__Arguments__

* `message` - The message you want to show.
* `delay` - Either 0 or 1. Default is 0.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.showToastError("An Error Occured", 0);
}
```

---------------------------------------

### Webvium.showToastSuccess(message)

Show a blue toast message to the user.

__Arguments__

* `message` - The message you want to show.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.showToastSuccess("Done.");
}
```

---------------------------------------

### Webvium.showToastSuccess(message, delay)

Show a blue toast message to the user with custom delay.

__Arguments__

* `message` - The message you want to show.
* `delay` - Either 0 or 1. Default is 0.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.showToastSuccesss("Done.", 0);
}
```

---------------------------------------

### Webvium.copyToClipboard(message)

Copy a message directly to user clipboard.

__Arguments__

* `message` - The message you want to copy.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.copyToClipboard("Hello World");
}
```

---------------------------------------

### Webvium.vibrate(long)

Vibrate user device.

__Arguments__

* `long` - The time the device will vibrate in miliseconds.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.vibrate(3000);
}
```

---------------------------------------

### Webvium.currentVersion()

Get the user webvium current version.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    console.log(webvium.currentVersion());
}
```

---------------------------------------

### Webvium.showNotification(title, description, link)

Send user a notification.

__Arguments__

* `title` - The title of your notification must be concise and short.
* `description` - The description or body of your notification.
* `link` - Action that the user could do. Must start at `https://` or `http://`

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.showNotification("Hello World", "Lorem ipsum dolor ier adao adjf", "https://github.com/webvium");
}
```

---------------------------------------

### Webvium.textToSpeech(message)

Text To Speech API

__Arguments__

* `message` - The message you want the user to hear.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.textToSpeech("Hello World");
}
```

---------------------------------------

### Webvium.print()

Print the current web page.

__Example__

```js
let webvium = Webvium;

if (!(webvium === undefined)) {
    webvium.print();
}
```
---------------------------------------

### Check if WebviumHashHelper Object undefined or not
```js
if (!(WebviumHashHelper === undefined)) {
    // Webvium Browser
} else {
    // Other browser, or the interface is disabled
}
```

---------------------------------------

### WebviumHashHelper.encodeMD5(text, boolean)

Converts the text to the popular MD5

__Arguments__

* `text` - The plain text you want to encrypt
* `boolean` - If the encoder gonna use random bytes to encode it.

__Example__

```js
let webviumHashHelper = WebviumHashHelper;

if (!(webviumHashHelper === undefined)) {
    webviumHashHelper.encodeMD5("Hello World", false);
}
```

---------------------------------------

### WebviumHashHelper.encodeSHA(type, text, boolean)

Converts the text to the popular SHA

__Arguments__

* `type` - Its either of SHA-1, SHA-224, SHA-256 and SHA-384.
* `text` - The plain text you want to encrypt
* `boolean` - If the encoder gonna use random bytes to encode it.

__Example__

```js
let webviumHashHelper = WebviumHashHelper;

if (!(webviumHashHelper === undefined)) {
    webviumHashHelper.encodeSHA("SHA-1", "Hello World", false);
}
```

---------------------------------------

### WebviumHashHelper.encodeXOR(text, key)

Converts the text to the XOR

__Arguments__

* `text` - The plain text you want to encrypt
* `key` - The key that encoder needs to encode and decode the XOR

__Example__

```js
let webviumHashHelper = WebviumhashHelper;

if (!(webviumHashHelper === undefined)) {
    webviumHashHelper.encodeXOR("Hello World", "E");
}
```

---------------------------------------

### WebviumHashHelper.encodeCaesar(text, padding)

Converts the text to Caesar Cipher

__Arguments__

* `text` - The plain text you want to encrypt
* `padding` - The padding that encoder needs to encode and decode the Caesar

__Example__

```js
let webviumHashHelper = WebviumhashHelper;

if (!(webviumHashHelper === undefined)) {
    webviumHashHelper.encodeCaesar("Hello World", 13);
}
```

---------------------------------------

### WebviumHashHelper.encodeAES256(text, key, saltPhrase)

Converts the text to AES-256 encryption algorithm

__Arguments__

* `text` - The plain text you want to encrypt
* `key` - The key that the encoder will use to encrypt the text.
* `saltPhrase` - Random text phrase that the encoder will use to hardened the encryption

__Example__

```js
let webviumHashHelper = WebviumhashHelper;

if (!(webviumHashHelper === undefined)) {
    webviumHashHelper.encodeAES256("Hello World", "nmnm", "qwqe");
}
```

---------------------------------------

### WebviumHashHelper.decodeAES256(text, key, saltPhrase)

Decodes the encrypted text using AES-256 encryption algorithm

__Arguments__

* `text` - The plain text you want to encrypt
* `key` - The key that the encoder will use to encrypt the text.
* `saltPhrase` - Random text phrase that the encoder will use to hardened the encryption

__Example__

```js
let webviumHashHelper = WebviumhashHelper;

if (!(webviumHashHelper === undefined)) {
    webviumHashHelper.decodeAES256("Hello World", "nmnm", "qwqe");
}
```


---------------------------------------

### WebviumHashHelper.getRandomBytes()

Decodes the encrypted text using AES-256 encryption algorithm

__Returns__

* `byte[]` - A secure random byte

__Example__

```js
let webviumHashHelper = WebviumhashHelper;

if (!(webviumHashHelper === undefined)) {
    console.log(webviumHashHelper.getRandomBytes());
}
```

---------------------------------------

### Check if WebviumSearchHelper Object undefined or not
```js
if (!(WebviumSearchHelper === undefined)) {
    // Webvium Browser
} else {
    // Other browser, or the interface is disabled
}
```

// data coming soon

---------------------------------------

### Check if WebviumSearchSuggestion Object undefined or not
```js
if (!(WebviumSearchSuggestion === undefined)) {
    // Webvium Browser
} else {
    // Other browser, or the interface is disabled
}
```

// data coming soon

---------------------------------------

### Check if WebviumThemeHelper Object undefined or not
```js
if (!(WebviumThemeHelper === undefined)) {
    // Webvium Browser
} else {
    // Other browser, or the interface is disabled
}
```

// data coming soon