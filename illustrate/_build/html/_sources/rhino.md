# Rhinoceros 3D

## Generating a File in Rhino

Open Rhinoceros. If using [UFApps](https://info.apps.ufl.edu), click the button to Login to UFApps. Select the UFApps - Graphics option.

To manage files, you will have to use the M Drive, accessible from the virtual desktop. To upload files to the M Drive, click on the side bar to the left, and the Open File Transfer panel at the top of the side bar. Click Upload, and Choose Files. To download files to your computer from the M Drive, click Download, then open a new window with your M Drive, navigate to the file you want to transfer, select it, and click CTRL + C or COMMAND + C. The file should appear in the File Transfer panel, click the download arrow, and select the download location. Transferring files is easier with the Horizon Client. Open the M Drive in the Horizon Client and open a separate file folder on your local computer. Highlight and drag the files from your local computer to the M Drive.

To open Rhinoceros in UFApps, click on the Windows icon at the bottom center, and start typing Rhinoceros. Click to open Rhino 7. You might be prompted to select a template, or the program may load without offering this option. If the program loads, exit out of all the smaller menus. Then click File -> New, and select the Large Objects - Centimeters option.

You will see 4 different viewing windows, which allow users to build models in three dimensions. We will be working exclusively in two dimensions, so we only need a single viewing window. Double-click on the Top button to view only the Top angle.

You can now save your file by clicking File -> Save, and choosing a file name to save in your M Drive.

## Basic Navigation and Interface

At the top of the Rhino window, you should see a set of toolbars. I recommend only using the Standard Toolbar Group. You can right-click on the upper toolbar, hover over Show Toolbar, and turn on or off any toolbars.


You will also want the Layers panel to be displayed. This panel should already be visible at the right side of the screen. If not, click on Panels -> Layers.

The Main toolbar should be displayed at the left. If not, right-click outside of the viewing area, hover over Show Toolbar, and turn on Main. Drag the toolbar to the left to dock it to the left side of the screen.

You will also want the Osnap options displayed. Click on Osnap at the bottom of the screen. The options should be docked just above. If not, drag the window to the bottom of the screen to dock it.

To navigate around the viewing window, right-click and drag. A left-click and drag is used to select.

## Importing a Scanned Drawing

To import a scan or any other image, click Surface -> Plane -> Picture. Also, turn on the Ortho option at the bottom of the screen. The Ortho option will force any object to be orthogonal (oriented at 90-degree angles). Once the Picture option is selected, click anywhere in the viewport, drag, and click again. The image will now be displayed in the viewport.

Depending on how the image loaded, you may need to rotate it. Next to Command: at the top-left of the screen, type Rotate and press Enter. Select the object to rotate, click anywhere on the object to define the center of rotation, drag and click to create the first reference point (with the Ortho option still on), then drag your mouse to rotate the object manually. Alternatively, you can type the angle of rotation next to Angle or first reference point (180, for example), and click Enter.

To scale the drawing, determine the size of the object. A profile drawing of a 2 x 2 m excavation unit, for example will have a horizontal dimension of 2 m. Draw a reference line measuring 2 m. Choose the Polyline option in the Main menu at left. Turn on the Grid Snap option at the bottom (and the Ortho), which will force any drawings to align to the grid. Click to place the first point of the line, then click again to place the second point of the line. At the bottom left, you will see the length of the line, drag until it reaches 200 cm, and click. Then press Enter. Alternatively, you can define the length of the line after placing the first point by typing a value (200, for example) in the Command window, next to Next point of polyline. Click again, and press Enter. You should now have a straight, horizontal line measuring 200 cm.

Click on the scanned image to select, and then drag to line up with your line. The left side of the drawing should match the left point of the 200-cm line. You will want to turn off the Grid Snap and Ortho options to line up the drawing accurately.

Next, select the drawing, and type Scale in the Command window, and press Enter. Select the origin point, which should be the left side of the drawing. Turn Ortho on, and click the right side of the drawing. Drag this point to match the right side of the 200-cm line. Turn on Osnap, and click End, to match with the end of the line. Click in the viewport to complete the scale command.

The scanned image should now be correctly scaled. However, you will likely need to fine tune the scale and rotation iteratively several times to improve the accuracy.

Add vertical polylines to define the shape of the profile drawing. Click Polyline, and turn on Osnap and Ortho. Click on the left point of the horizontal polyline and drag down to complete the left vertical polyline. Then, do the same with the right vertical polyline. Make the lines longer than they need to be; the lengths can later be edited.

Now that the basic shape of the profile has been defined, fine tune the scale and rotation of the scanned image one last time.

## Using Layers to Organize Your Drawing

Before the drawing gets more complicated, we can define several layers to separate different elements of the drawing. In the Layers pane, you will see several layers available, including the Default. The active layer will be in bold text with a check mark. To change the active layer, double-click any layer in the Layers pane.

Choose the bottom layer, right click and Rename Layer to something like Sketch. Select the scanned image in the viewport, right-click the Sketch layer in the Layers pane, and click Change Object Layer. The scanned image is now in a separate layer. Make sure the Sketch layer is not active. You can turn the layer on and off by clicking the light bulb, and lock it by clicking the lock. For the rest of the drawing, we can lock the scanned image so that it does not move and cannot be selected. We can also change the color of the layer by clicking the color next to the lock. For the scanned image, the color will not affect the scan but rather the frame around it. For other layers, the color will affect the drawing.

Rename the other layers and add new ones by clicking New Layer in the Layers pane. I recommend the following layers in this order (you can reorder layers by selecting the layer in Layers pane clicking Move Up or Move Down):

Hypothetical

Rocks

Faced

Limestone Fill

Sandstone Fill

Lot

Soils

Sketch

Other layers will depend on the drawing, for example, if the drawing includes any artifacts, tree roots, etc.

We can now put our first polylines in the Lot layer. Select all of the lines by left-clicking and dragging (if the Sketch layer is locked, the sketch will not be selected). Alternatively, click each line individually while holding shift to select all lines. Right-click Lot in the Layers panel, and select Change Object Layer.

## Drawing the Limits of the Excavation Drawing

So far, we have three polylines creating three sides of a box. We need to add the surface and the lower excavation limits. In contrast to the sides of the unit, these lines will not be perfectly straight.

Make sure the Lot layer is active. We will now draw the surface of the excavation by interpolating a line. Navigate in top toolbar Curve -> Free-Form -> Interpolate Points. This option allows you to force a line to pass through specific points, interpolating curves between the points. You will have to practice to become familiar with this tool. You want to make sure the lines you draw are not too straight and not too smooth. With Osnap on and the Near option selected, begin drawing the interpolated curve from the intersection of the surface with the left limit of the excavation. Click to trace along the surface line until reaching the right limit of the excavation. Click Enter. Now do the same with the lower limit of the excavation. We now have the limits of the excavation defined, however, we have to clean up the drawing. To view the lines, turning off the Sketch layer can help.

First, we can delete our initial 200-cm horizontal line, which was merely a guide to help scale the scanned image. Click the line to select and press Delete. Next, we want to trim the vertical lines, which likely extend beyond the limits of the excavation. In the Command window, type Trim and press Enter. You will be prompted to Select cutting objects. These are the lines that will define where your vertical lines should stop. Click the surface line and lower limit line to select them, then press Enter. You will then be prompted to Select object to trim. Click the portions of the left and right vertical lines that extend outside of the excavation, then press Enter. As you click, you will see each line segment removed. If you ever make a mistake, you can press Escape, or Edit -> Undo. Alternatively, if your vertical lines do not extend beyond the limits of the excavation but instead are not long enough, type Extend in the Command window. You will be prompted to Select boundary objects, which in this case will be either the surface or lower limit of excavation line, then press Enter. When prompted to Select curve to extend, select the appropriate line, and press Enter.

## Drawing the Lots and Adding a Fill for Soils

Referring to the scanned image sketch, use the Interpolate Points option to draw in the limits of each lot. You may also need to refer to field notes or the report to determine the appropriate width of each lot. Note that the Polyline option can be used not only to draw a line but also to measure distances. Select Polyline, draw the line, and refer to the measurement at lower left. Press Escape to cancel drawing a permanent line.

Once each lot has been drawn, we can add a fill to represent that lot's soil. Make sure the Soils layer is active, then select all of the lines drawn (turn off the Sketch layer if necessary). In the toolbar at top, just under the Command window, change the Standard tab to Drafting. Click on the Hatch icon. If a window pops up, turn on the check box marked Boundary. Doing so will use the boundary lines to determine the limits of the hatch fill. In the Command window, next to Click inside regions to keep, make sure the CombineRegions option is set to No. If it says Yes, click on Yes to change it to No. Doing so will treat each fill as a separate object, rather than combining them all into a single object. Nexts, click inside each region to generate a fill (between the lot lines). When done, press Enter. The Hatch window will pop up again. Make sure Boundary is still selected and the Solid pattern should be the default. Click OK. You will now have fills representing each soil layer. Before moving on, you can now lock the Lot and Soils layers. I also recommend turning off the Soils layer so it does not obstruct the rest of the drawing.

## Drawing Rocks and Other Objects

Make the Rocks layer active. Tracing over the sketch, draw in each rock. To close a line, click on the first point of that line. The Interpolate Points curve will sometimes make high curvature lines, especially when changing the direction of the line suddenly. Adding additional points in these areas will reduce this curvature. You can undo any point by clicking Undo in the Command window (not under Edit). You will need Osnap on to close curves, but sometimes the line can snap to previously drawn objects. You can turn Osnap on and off when necessary as you draw lines.

When rocks touch each other, it is best not to draw additional closed curves for each rock. In other words, rocks next to each other will share the same line where they touch, rather than having multiple overlapping lines.

You can also use the Layers to draw different types of lines. Most lines will be solid lines representing rocks. Other lines will represent hypothetical shapes of rocks (dashed lines), faced rocks (double line weight), etc. For now, place these lines in different layers.

At times, you might draw several individual line segments that actually represent a single line. To combine them, select them, and type Join in the Command window.

Alternatively, you might want to split a line into multiple segments. Type Split in the Command window, and the follow the directions to split a line, in a similar fashion to the Trim command (the latter deletes line segments, while Split separates them).

