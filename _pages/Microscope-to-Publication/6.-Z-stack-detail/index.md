---
title: "Z-stack detail"
type: pages
layout: single
classes: wide
toc: true
toc_label: "Microscope to Publication"
sidebar:
  - title: "Z-stack detail"
    image: assets/images/m2p/Zstack_thumb.png
    #text: "Some text here."
    nav: microscope-to-publication
---

{% include video id="nqNjkKHurFY" provider="youtube" %}

## Create slices in Fiji
* Connect to OMERO in Fiji
* Open image
* Create lines on image and add to ROI manager

![](media/draw_a_line.png)

* Reslice the stack for each line (`Image > Stacks > Reslice [/]...`)
* Rename the images

![](media/create_slices.png)

* Upload to OMERO from Fiji

![](media/import_images.png)

## In OMERO
* Open all three image in figure

* Correct B&C

![](media/correct_BC.png)

* in Overview, add ROIS

* Setup labels

![](media/add_labels.png)
