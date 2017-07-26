# DolphinNBT
Javascript NBT parser and writer for browser

##Embedment

To embend DolphinNBT to your website first download the file `DolphinNBT.js` or `DolphinNBT.min.js` (it doesn't matter, but the second is just takes up less disk size) and place them into the same directory as your HTML file.
Write `<script src="DolphinNBT.js"></script>` or `<script src="DolphinNBT.js"></script>` into the HTML head tag (it depends which file you use).
Since many NBT files are complressed, DolphinNBT requires pako.js to decompress and compress data. If the data is not compressed pako will not be used and does not have to be embedded. But if data is processed and pako is not embedded, DolphinNBT will throw an error.
Therefore, **it is recommended to embed pako.js**:
Download pako.min.js from [its github page](https://github.com/nodeca/pako/tree/master/dist) and place the file in the same directory as your HTML page and DolphinNBT.js and write `<script src="pako.min.js"></script>` into your HTML head tag.

##Example



