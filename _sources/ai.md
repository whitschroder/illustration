# Adobe Illustrator

## Opening the Drawing in Adobe Illustrator and Copying to the Template

Now open the .ai file in Adobe Illustrator. Open the template file in a new tab. Select all elements of your drawing by left clicking and dragging with the Selection tool. Use Edit -> Copy, then switch tabs to the template file. Unlock all layers, and in the hamburger menu, turn on Paste Remembers Layers. Then use Edit -> Paste.

Resize the drawing by selecting all elements, and matching your polyline scale to the template scale bar. You can move all elements by clicking inside the drawing and dragging, and rescale by holding the shift key and dragging one of the corners of the drawing. Then move the drawing to the center of the artboard. Resize the artboard by clicking Document Setup, the Edit Artboards. After resizing the artboard click the Select tool to exit out of the artboard. Unlock the Background layer and resize to match the artboard. Select and move the text (scale bar and legend) if necessary. Edit the scale bar text if necessary so that the higher value matches the scale. Now select the polyline you drew in Rhino to match the scale, and delete.

At any time, press ctrl 0 to zoom to the full extent. Use the Zoom tool to zoom in, or hold alt to zoom out. To move elements lightly (nudge), hold ctrl while pressing the up, down, left, or right arrows.

## Editing the Style of Elements

Next, going layer by layer, we will edit the styles to match our legend. Beginning with the Lot layer, select the surface and change the Brush Definition from Basic to Superficie (dotted line). Select the vertical sides of the excavation and change to Limites (dashed-dotted line). Select the lower limit of the excavation, and change to either Limites, Roca Madre, or the relevant style. Keep the extra lot lines for now, but we will delete them later.

Move to the next layer, which should be Faced stone. Select all elements in this layer by clicking the circle to the right of the layer in the Layers panel. Then change the brush to Roca Madre/Cara Piedra Tallada (double weighted line). Next, select all Hypothetical rock shapes, and change the brush style to Piedra o Rasgo Hipotetico (dashed line). Then, select all rocks, and change the brush style to Piedra Normal. Next, select all Limestone Fill and change the fill color to white (RGB: 255, 255, 255 or hex code #FFFFFF. Do the same with Sandstone Fill or any other objects. For sandstone, use the color shown in the legend (RGB: 150, 90, 56 or hex code #965A38). For any other objects, choose a suitable color to also be included in the legend.

## Changing the Soil Color

The next step is to edit the soil colors to match the Munsell designations assigned in the field. Refer to field notes or the report to find these field designations. The following website includes RGB approximations of the [Munsell color codes](https://pteromys.melonisland.net/munsell).

Select each soil layer fill and open the color picker in Adobe Illustrator by double-clicking on the fill color in the left menu. Referring to the field notes, we see that the first lot was assigned the Munsell color code 7.5YR 4/2. Navigating to the Munsell Color Palette website, edit the values at the right, and click Go to. The Selected color will update, with the appropriate RGB code. Using these numbers, edit the color in the Adobe Illustrator color picker and click OK. Proceed with the other lots.

## Adding Stippling to the Soils

To add texture to the soils, we use stippling of different weights. At times, the soil colors do not always align with the lots assigned in the field, so the stipples add additional information to identify each lot in the drawing.

With the Stippling layer selected, select the Paintbrush tool, and choose one of the scatter brushes under Brush Definition. Make sure the stroke color is set to black (RGB: 0, 0, 0 or hex code #000000). Hold the left mouse and drag to add the scatter brush. Using a single stroke is easier than multiple strokes; just hold the mouse down while snaking back and forth to fill the area of the first lot.

Next, we are going to mask areas outside of the first lot. First, select the soil fill representing the first lot and Edit -> Copy. Next, select the stipple you just drew. In the Transparency panel, click Make Mask. Click the black square (Click or Alt-Click to edit opacity mask). Then Edit -> Paste in Place. Make sure Clip is checked. If the stipple is no longer black, you might need to toggle Invert Mask on or off. Once the stipple is clipped and black, in the Transparency window, click back on the left square (Click to stop editing opacity mask). Proceed with each lot, selecting a different scatter brush for adjacent lots. You can repeat scatter brushes once you run out. Note that some scatter brushes are too dense and heavy and should not be used. Select the scatter brushes that are the least obtrusive. I prefer Scatter Brush 1, Scatter Brush 3, Scatter Brush 5, Scatter Brush 6, and Scatter Brush 7.

When done, select and delete the lines between each lot. These lines served as guides while completing the drawing and are no longer necessary.

## Editing and Adding Text

The final steps require editing the text. First, update the information at top right, which should include the site name and state. The next line should represent the lot number or unit number, whether the drawing is a plan or profile. If a plan, specify if the drawing represents the beginning or the end of the lot. If a profile, specify the direction. The third line is the year, and the final line is the name or names of the artist.

Now update the direction shown at the top of drawing. The angle should represent the compass direction from left to right. The orientation of the unit can be found in field notes or the report and converted to the appropriate direction by adding 90 degrees (and subtracting 360 if the value is larger than 360).

Double-check the scale bar, and remove any items in the legend that are not relevant to the drawing.

Add labels for each lot, with arrows. To add any additional text, use the Type tool, or copy and paste any text and then edit.

## Finishing Edits

Make any final edits, resizing elements, recentering objects, etc. You might notice "ghost" lines, especially along the left or right side of the drawing. These lines will appear light gray. These lines reflect issues with line and polygon features misaligning. To fix these lines, select any fill elements, and go to Object -> Path -> Offset Path. Change the offset to a low value (for example 0.01 cm). Adjust as necessary to eliminate these ghost lines. This step is not always necessary.

Resize the artboard, keeping in mind that this image will be copied into an 8.5 x 11 in. document.

## Exporting the Drawing

Go to File -> Export -> Export as, and save as JPEG. Change quality to Maximum (drag up to 10), and change resolution to High (300 ppi).

