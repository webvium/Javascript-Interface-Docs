# Documentation

### Check if undefined or not
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
