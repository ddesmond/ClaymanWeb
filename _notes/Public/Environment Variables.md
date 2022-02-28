---
title: Environment Variables
notetype : feed
date : 22-02-2022
---
### Environment Variables

Clayman uses environment variables to automaticaly drive the Library or user data loading.


Default [[Clayman User Folder]] is always created at the user home folder, ex. `C:/Users/Des/Clayman` or `/home/des/Clayman`.

Setting `CLAYMAN_USER_FOLDER` will load the [[Clayman User Folder]] from there. Be sure to copy the whole folder Clayman creates so it can properly load all files.

```
CLAYMAN_USER_FOLDER = /path/to/Clayman_user_folder
```

Setting `CLAYMAN_LIBRARY_REPOSITORY` to a location on the available disks will load this library on app startup.

Be sure that the folder is a valid Clayman Library folder.

```
CLAYMAN_LIBRARY_REPOSITORY = /path/to/library_to_load
```



Learn more about Clayman!

[[Clayman Interface]] | 
[[Importing assets]] | 
[[Work with Tags]] | 
[[Clayman User Folder]]
[[Environment Variables]] |


Learn more about Packages:

[[Create - Import a Package]] | 
[[Delete a Package]] | 
[[Import - Export Package]] | 
[[Importing assets]] | 
[[Work with Tags]] | 
[[Rebuild Package]] | 
[[Edit Asset Package]] | 