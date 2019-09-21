API used: 28 (Min API: 26)
Tested on: Pixel C AVD (API28, Landscape orientation only)


Toolbar:
Reset - will reset the doll to its starting size, and position
About - will pop a dialog showing the app name, my name, student number 
	(Click "OK" button in the info dialog will dismiss the dialog)
A radio button group to choose which model to show.


Ragdolls:

1. Doll:
- The entire doll can be translated using the torso.
- Head, upper arms, lower arms, hand, legs, feet can be rotated, within the limits 50, 360, 135, 35, 90, 35.
- The legs can be stretched.
P.S. 
- According to Piazza Post @458: For rotation, if it stops touching the target for any reason (ex. moves so fast; move over limitation), it should stop movement. In this case you can't manipulate the target without lifting your finger and touching it again.
- Scaling uses focus point to decide interactive part. 


2. Tree:
Root - LeafBottom
     - LeafTop
Root: parent of LeafBottom, LeafTop. 
- Can not rotate.
- Can be translated. Entire tree will be translated.
- Can be stretched in width (root becomes wider or thinner).

LeafBottom / LeafTop: child of root.
- Can rotate within the limit - 45 degrees. Rotate pivot point is the top of the 
- Can not be translated.
- Can not be stretched.
