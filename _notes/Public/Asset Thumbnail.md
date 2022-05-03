---
title : Asset Thumbnail
notetype : feed
date : 22-02-2022
---
### Asset Thumbnail

When importing and creating a Package, a thumbnail representing the package contents is needed to be set manualy by selecting the image in the square or setting a droped file as Thumbnail.

Thumbnails will show correctly only when set to square format. So keeping yout thumbs square in any res is a good rule of thumb. 

Clayman can read many image types trough OpenImageIO library.
That means that Clayman should be able to read all supported format in OpenImageIO v2.

In the processing part, the image colors are extracted into 3 dominant colors which are then written into the package data. Lower resolution version of the thumbnail is written as a cache thumbnail (512px).

If there is no thumbnail selected, then the extension type of the droped files is taken as thumbnail.

If no thumbnail data is present or not valid, the data type icon is shown.

In the Asset view, clicked items are shown the same way.

You can change the thumbnail at any time by right clicking on the asset and selecting Update Asset Thumbnail.

Learn more about Clayman!

[[Clayman Interface]] | 
[[Importing Assets]] | 
[[Work with Tags]] | 
[[Clayman User Folder]] | 
[[Environment Variables]]


Learn more about Packages:

[[Create - Import a Package]] | 
[[Delete a Package]] | 
[[Import - Export Package]] | 
[[Importing Assets]] | 
[[Work with Tags]] | 
[[Rebuild Package]] | 
[[Edit Asset Package]] 