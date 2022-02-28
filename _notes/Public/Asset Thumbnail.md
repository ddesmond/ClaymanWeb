---
title : Asset Thumbnail
notetype : feed
date : 22-02-2022
---
### Asset Thumbnail

When importing and creating a Package, a thumbnail representing the package contents is needed to be set manualy by selecting the image in the square or setting a droped file as Thumbnail.

Thumbnails will show correctly only when set to square format. So keeping yout thumbs square in any res is a good rule of thumb. 

Currently (Alpha/Beta builds) only Jpg and Png file formats are accepted as valid files wich will be processed as thumbnails. Png transparency is supported.

In the processing the image colors are extracted into 3 dominant colors which are then written into the package data. Lower resolution version of the thumbnail is written as a cache thumbnail (512px).

If there is no thumbnail selected, then the extension type of the fird droped files is taken as thumbnail.

If no thumbnail data is present or not valid, the data type icon is shown.

In the Asset view, clicked items are shown the same way.
If image can be loaded it will be shown (Alpha / Beta: only png, jpg, gif data is shown, mp4 for video, no sequence support)

You can change the thumbnail at any time by right clicking on the asset and selecting Update Asset Thumbnail.

Learn more about Clayman!

[[Clayman Interface]] | 
[[Importing assets]] | 
[[Work with Tags]] | 
[[Clayman User Folder]]
[[Environment Variables]]


Learn more about Packages:

[[Create - Import a Package]] | 
[[Delete a Package]] | 
[[Import - Export Package]] | 
[[Importing assets]] | 
[[Work with Tags]] | 
[[Rebuild Package]] | 
[[Edit Asset Package]] 