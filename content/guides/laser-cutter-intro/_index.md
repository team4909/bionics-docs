---
title: Laser Cutter Intro
description: How to use the laser cutter to make parts for prototypes
weight: 40
---

We often design prototypes, in OnShape, that can quickly be cut out of 1/4" plywood on the laser cutters.

Our laser cutters have a maximum working area of 24" by 18"

## Design and Export
1. Design the prototype in OnShape
2. Create a drawing without a border nor titleblock
    1. Right click on any part in the parts list, choose **Create Drawing** ![](onshape-create-drawing.png)
    2. Choose Custom Template ![](onshape-drawing-custom-template.png)
    3. Choose "Do not include" for both **Border** and **Titleblock**, click **Ok** ![](onshape-drawing-do-not-include.png)
    4. In the Insert view dialog make sure the **View scale is 1:1**
    5. You may need to change the View orientation to see the side of the part for cutting ![](onshape-insert-view-orientation.png)
    6. Click to place the part anywhere on the drawing sheet (we can move it later)
    7. OnShape assumes we want to have projected views. We do not need to place projected views, press escape to cancel the projected view.
3. We need to make sure our drawing size matches our stock size.
    1. Open the Sheets pane ![](onshape-sheets-pane.png)
    2. Right click the sheet (probably **Sheet1**) and choose **Properties**
    3. In the Sheet properties dialog, change the Size to custom
    4. Set the width to **24 in** and the height to **18 in**
4. Additional parts can be added to the sheet with the **Insert View** tool
    1. Click the **Insert View** tool ![](onshape-insert-view.png)
    2. In the Insert view dialog click the Insert button
    3. Choose another part
    4. Be sure the View scale is **1:1**
    5. You may need to change the view orientation
    6. Click to place
    7. OnShape assumes we want to have projected views. We do not need to place projected views, press escape to cancel the projected view.
    8. Repeat these steps for each unique part
5. If you need more space, additional sheets can be created.
    1. From the sheets pane, click the add sheet button.
6. By this point you should have all the parts on various sheets. Export each sheet to SVG.
    1. Change to the first sheet
    2. Right click on the drawing tab at the bottom, choose **Export...** ![](onshape-drawing-export.png)
    3. Set the format to **SVG**, Click Export ![](onshape-export-svg.png)
    4. Repeat for each sheet

## Configure Cutting and Engraving

TODO


Based on the fantastic inkscape tutorial from the Tulane makerspace
http://makerspace.tulane.edu/Uploads/InkscapeTutorial.pdf