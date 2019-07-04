Window Size: Fixed, 650 X 650

Basic Features:
1. Create a new drawing.
2. Load a drawing from a file (i.e. a file that previously saved, which replaces the current drawing).
3. Save the current drawing.
4. Select, erase, draw and fill shapes including line, circles and rectangles.
5. Change drawing colour and line thickness.
...


Additional Features:
1. Customizable color palette: right-click a color button and choose a new color for that button from a color-chooser dialog to customize color buttons in the palette.

2. Half-way group shapes: add an option "Group" (multiSelector), which can select multiple shapes, then dragged as a single entity.

For multiSelector, if click on other places not shapes, shape selection will be cleared; next click on a shape will start an new selection. Or press "ESC" will clear shape selection as well. 

Moving as an entity has an issue (no time to figure it out before due): currently it will show the bounding rect and show the excepted move using the bounding rect, but inside elements are moving incorrectly by itself ...


Icon Image:
Icon images are created by myself using iPad.
If the image is failed to read, text will show on the icon instead for indication.


Overlap Rule:
Early created shapes are under later created image. When using selection / erase / fill, the topmost shape contain the mouse click point will be selected / erased / filled.

Control Disable:
- erase / multiSelector: controls for color and line thickness will be disable
- fill: control for line thickness will be disable
- rest: controls are all enabled

Selected controls(tool, color ...) will be highlighted by thicker border. If color is chosen by "Chooser" button, the "Chooser" button will be highlighted.
Selected shapes will be highlighted by dashed line.

Load: load the canvas (actually shapes) from a txt file
Save: save current canvas (actually shapes) info to a txt file

...
