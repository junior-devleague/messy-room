
## Tools

LMB = Left Mouse Button / Left Side of Mouse
RMB = Right Mouse Button / Right Side of Mouse

Scene Tools | Path | Description
----------- | ---- | -----------
Tumble | Option + LMB | Orbit around the scene.
Track | 2 Finger Swipe | Move around the scene side to side.
Dolly | Option + RMB | Zoom in and out of the scene.
Frame Current | F | Displays current selection.
Frame All | A | Displays all objects in the scene.

Modeling Tools | Path | Description
-------------- | ---- | -----------
Move Tool | W | Move selected object(s).
Rotate Tool | E | Rotate selected object(s).
Scale Tool | R | Scale selected object(s).
Last Used Tool | Y | Use last tool used on selected object(s)
Soft Selection | B | Modify object components with a range of influence.
Change Range of Soft Selection | Hold B + LMB Drag | Modifies range of influence to increase/decrease.

Display Tools | Path | Description
------------- | ---- | -----------
Smooth Mesh Off | 1 | Turns off smoothed preview.
Cage + Smooth Mesh Display | 2 | Creates a wireframe cage showing the original mesh and the smooth preview.
Smooth Mesh On | 3 | Displays the smoothed preview.

Other Tools | Path | Description
---------- | ---- | -----------
Hotbox | Hold Space | Shortcut menu.
Panel Layout | Space | Shows all four panels with different views.
Component Menu | Hold LMB | Shortcut menu with Component Mode Selection options.

## Backface Culling
1. Create a Polygon.
2. Select Mesh Display Menu -> Reverse.
3. Select Display Menu -> Polygons -> Backface Culling.

## nCloth
1. Go into your ```FX Menu Set```.
2. Select the object that will be the nCloth in ```Object Mode```. The object should turn green when selected.
3. Click on the nCloth Menu -> Create nCloth.
4. Click anywhere else in your ```View Panel``` to deselect all objects.
5. Click on the Fields/Solvers Menu -> Gravity.
6. Select the object that will be the collider in ```Object Mode```. The object should turn green when selected.
7. Click on the nCloth Menu -> Create Passive Collider.
8. Press the Play Button in your Playback Controls to see the nCloth animation.

## Create Layers
1. In your ```Channel Box```, click on the ```Channel Box/Layer Editor``` tab on the very right.
2. Select the objects that you'd like to place on the same layer in ```Object Mode```. The object(s) should be green/white when selected.
3. In the ```Layer Editor``` at the bottom of the ```Channel Box```, click on the Display Menu -> Layers Menu -> Create Layer from Selected.
4. A new layer will appear in the ```Layer Editor```. Double click this layer to rename it and change other properties.
5. There are three boxes to the left of your layer. (Left to Right): 1st Box -> Visibility, 3rd Box -> Ability to be selected. (R (Reference) = Turns off selectability and keeps original display mode, T (Template display) = Turns off selectability and displays the template view of objects.

## Load the Paint Effects Menu
1. Click on the gear icon at the left bottom corner of your shelf.
2. Select ```Load Shelf```.
3. Load ```shelf_PaintEffects.mel``` by double clicking it.

## Multi Cut Tool
1. Make sure you are currently in your ```Modeling Menu Set```.
2. In ```Object Mode```, select the object you want to cut on. Your object should turn green when selected.
3. Go into your ```Mesh Tools``` Menu -> Multi Cut.
4. The tool is now activated and your object should turn blue. Click on an area of the edge or vertex on the object selected where you want to start the cut. Select the next area(s) where you want the cut to be placed. The final cut should be on an edge or vertex. Press Enter to finalize that cut. Exit Multi-Cut by selecting the arrow/cursor in your ```Tool Box```, or press Q on your keyboard.

## Extrude Tool
1. Make sure you are currently in your ```Modeling Menu Set```.
2. The Extrude tool works on flat surfaces. Stay in ```Object Mode``` if you are working with a ```Polygon Plane```. Go into ```Face Selection``` mode to select faces.
3. Click on the ```Edit Mesh``` Menu -> Extrude. Click and drag on the direction that you want the extrusion to take place in. Double click the values in the smaller Extrude menu box to change the number of divisions that are created.

## Resources
[http://help.autodesk.com/view/MAYAUL/2017/ENU/?guid=GUID-F4FCE554-1FA5-447A-8835-63EB43D2690B] (Maya Interface)
