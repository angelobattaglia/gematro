# Fork of Gematro

This is a fork of the popular cryptography/gematria calculator called Gematro, hosted at [gematro.com](https://gematro.com).
This fork aims to add new ciphers as fast as possible! It also has no
google analytics tags, meaning that it's privacy-oriented. 

Feel free to fork it and/or send pull requests.

## List of my personal modifications

In "calc/calc.js", row 25, I've set the Extra Ciphers as always visible

```javascript
var optShowExtraCiphers = true // false // enable extra ciphers
```

In "calc/ciphers.js" I've added the "QWERTY" ciphers: the extended QWERTY, the ordinal QWERTY and the reduced QWERTY. All with their respective reverse ciphers.

## How to contribute

Just drop a pull request with your favorite cipher and its background.
The ciphers can be added in the "calc/ciphers.js" file, you can see how the other ones are being implemented.

## Licence

I don't own this code, and this is a fork of the software [gematro.com](https://gematro.com).

