---
title: Intro to CAM with Fusion 360
description: Getting started with Fusion 360 CAM
src: https://docs.google.com/document/d/1EK63A9zoJkVzYDzSKFMsQuw_GsHjY60yi7C2bry6HIY
---

This is a brief introduction/refresher for creating GCODE via Fusion 360 CAM. This guide assumes CAM is targeted at the Velox using Mach3 as the GCODE sender.

1. Download a STEP file of the part from Onshape {{< expand "Show Me..." >}}
{{< columns >}}
<img src="onshape-export.png">
<---> <!-- separator between columns -->
<img src="onshape-export-type.png">
{{< /columns >}}
{{< /expand >}}

2. Open the file in Fusion 360 {{< expand "Show Me..." >}}
- [How to import or open a file in Autodesk Fusion 360](https://knowledge.autodesk.com/support/fusion-360/learn-explore/caas/sfdcarticles/sfdcarticles/How-to-import-or-open-a-file-in-Autodesk-Fusion-360.html)
{{< /expand >}}
3. Be sure the part is laying down with the correct face up. For some parts it will not matter which face is up.
4. Change to the Manufacturing workspace {{< expand "Show Me..." >}}![](fusion-manufacture.png){{< /expand >}}

5. Create a Setup which defines what your stock material shape and size are. test
    1. Tab 1: Set the zero axis to the bottom left corner of the stock so the red and green arrows point into the stock. It is critically important that the point selected is used as the zero poing when setting up the machine. {{<expand "Show Me..." >}}
{{< columns >}}
![](fusion-setup-oigin-axes.png?height=180px)
<--->
![](fusion-setup-tab1-origin.png?height=280px)
{{< /columns >}}
   {{< /expand >}}
    2.  Measure the actual z height of your stock using calipers. (Incorrect z will cut into the table.) {{<expand "Show Me..." >}}![](measure-stock-thickness.jpg?height=180px){{< /expand >}}
    3. Tab 2: Make sure the top of the part is aligned with the top of the stock in the setup. (This is especially important if your model is a different thickness than your stock.) {{<expand "Show Me..." >}}![](fusion-setup-tab2-stock-size.png?height=280px){{< /expand >}}
    4. Tab 3: If machining tubes set the WCS (work coordinate system) to 6 to indicate the vises that are setup on our Velox. (WCS6 is pre-configured in the Mach3 software on the PC connected to the Velox.) {{<expand "Show Me..." >}}![](fusion-setup-tab3.png?height=180px){{< /expand >}}
    
6. Now that the setup is done, you can create operations to make your part.
    - Do the most tricky operations first. That way if something goes wrong, you won't have invested as much time in your new piece of scrap.
    - Do small holes first, using a 2D bore using an ⅛ or ³/¹⁶ endmill.
    - Next do any larger holes or lightening with a ¼ endmill. These will require two operations, first an adaptive clear to quickly rough out the hole, then a 2d contour to cleanup
    - Finally use a 2d countour to cut out your part. This requires a much slower cut. We often find creating a "virtual moat" and using an adaptive clear is a faster operation.



