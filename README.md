# cordova-plugin-decimal-keyboard-wkwebview

Cordova plugin to show decimal keyboard on iPhones

## Install

```bash
cordova plugin add --save cordova-plugin-decimal-keyboard-wkwebview
```

## Usage

```html
<input type="text" pattern="[0-9]*" decimal="true">
```

Input type number will not work, try to use text with [0-9] pattern instead.

<img src="screenshots/basic-usage.png" width="25%" height="25%" /> <img src="screenshots/basic-usage-typed-content.png" width="25%" height="25%" />

## Multiple decimals

```html
<input type="text" pattern="[0-9]*" decimal="true" allow-multiple-decimals="true">
```

<img src="screenshots/multiple-decimals.png" width="25%" height="25%" />

### Different decimal character

```html
<input type="text" pattern="[0-9]*" decimal="true" allow-multiple-decimals="false" decimal-char=",">
```

If you want to localize decimal character, you can change using decimal-char attribute
<img src="screenshots/different-decimal-char.png" width="25%" height="25%" />

## Known Issues
* Does not handle screen rotation.
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
