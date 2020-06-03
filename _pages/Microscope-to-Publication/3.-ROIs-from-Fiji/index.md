---
title: "Importing ROIs from Fiji"
type: pages
layout: single
classes: wide
toc: true
toc_label: "Microscope to Publication"
sidebar:
  - title: "Importing ROIs from Fiji"
    image: assets/images/m2p/fiji_roi_thumb.png
    #text: "Some text here."
    nav: microscope-to-publication
---

{% include video id="2goZmZANWVc" provider="youtube" %}


## Create the ROI in FIJI
1. Open Fiji (Windows only at the moment)
2. Connect to OMERO
3. Open image
![](media/open_image_in_FIJI.png)

4. duplicate channel 3
5. Threshold
6. Analyse particles

![](media/threshold_make_ROIS.png)

7. `OMERO > Save ROIS to OMERO`

![](media/save_rois_to_OMERO.png)



## Open the image in OMERO.figure
1. Open image
2. Click on ROIs, Load ROIs
3. Add the first one make it Yellow
![](media/add_roi.png)

## Create the figure

1. Copy the image 3 times
2. Scale down for detail
3. resize
4. Channel set or each
5. Add scale bars

![](media/create_channel_split.png)



