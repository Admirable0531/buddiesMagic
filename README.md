# buddiesMagic

Static maimai / maimai DX song data — difficulty levels, categories, and jacket icon IDs — packaged as plain JS arrays for use in other tools or bots.

## Files

- `buddiesMagic.js` — song list with `dx` (deluxe flag), `lv` (difficulty ratings per chart), `v` (version), `n` (song name), and `ico` (icon hash).
- `buddiesPlusMagic.js` — extended/updated dataset.

## Usage

Import the array directly into a Node or browser project:

```js
const songs = require('./buddiesMagic.js');
```
