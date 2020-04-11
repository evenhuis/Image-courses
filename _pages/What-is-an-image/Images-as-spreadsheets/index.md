---
title: "Images as spreadsheets"
type: pages
layout: single
toc: true
toc_label: "My Table of Contents"
sidebar:
  - title: "What is an image?"
    image: icon.jpg
    text: "Some text here."
    nav: what-is-an-image
---

Images are stored on the computer as an array of numbers which can thought of as a spreadsheet. 
To make this connection we will open an image in Fiji, save it as table of numbers and open in Excel. 



## Open the image

1. Open the image. In the Fiji menu `File > Open` and find the file  `cell.tif`
2. Increase the zoom level until you can see the pixels (`+`)
3. When the mouse is moved over the coordinates and value of the pixel under the pointer is displayed in th Fiji toolbar.
![](mouse_over.png)

## Export the image as numbers

### Export from Fiji:
1. Go to `File > Save As > Image Sequence...`
2. Select a location for the file, `cell.txt`

### Open In Excel:
1. Go to `File > Open` as select the file `cell.txt` that you just made
2. This will open the Text Wizard.
   * Choose `Delimited`
   * Choose `Tab`
   * Press `Finish`

You will now see a table of numbers in Excel. 


Zoom,
pan
mouse location and pixel value
increase zoom level until pixels
show on mouse over the coordinates and the values
