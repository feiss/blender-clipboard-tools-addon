# Clipboard tools add-on

![screenshot](clipboardtools.png)

Copies to the clipboard the position, rotation or scale of the selected object
```js
// Example output:
1, 4.3, 24
```

It can also copy the **geometry** (vertices and faces) of the selected object.
```js
// Example output:
var Plane = {
  vertices: [-1.56, 0.0, 1.56, 1.56, 0.0, 1.56, -1.56, 0.0, -1.56, 1.56, 0.0, -1.56],
  faces: [0, 1, 3, 2]
}
```


## Installation

1. Download [clipboard_tools.py](clipboard_tools.py)
2. In Blender, go to Edit > Preferences > Add-ons and click on `Install...`.
3. Select the add-on file from your drive, and set the add-on checkbox on.

