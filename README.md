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

### Check if WebviumHashHelper Object undefined or not
```js
if (!(WebviumHashHelper === undefined)) {
    // Webvium Browser
} else {
    // Other browser, or the interface is disabled
}
```

// data coming soon

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