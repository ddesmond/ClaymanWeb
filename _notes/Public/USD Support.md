---
title : USD Support
notetype : feed
date : 22-02-2022
---
### USD Support
Feature not yet public, WIP

Current version is 22.03

Build full USD:

```bash
Mac 10.14 +, Python 3.7 (conda)
python USD/build_scripts/build_usd.py  --prefer-speed-over-safety --build-args USD,"-DPXR_PY_UNDEFINED_DYNAMIC_LOOKUP=ON" --alembic --hdf5 --openvdb --openimageio --opencolorio --no-tests BUILD
```



Add both PYTHONPATH and PATH Environment variables so the libraries are accesible.



Bring your own USD :)
Just drop-in your own usd libraries, means, Clayman in DCC will use any oiioo / ocio / usd libraries you provide.

You need PySide2 available (5.12 +) so USD compiles correctly for Clayman.




Learn more about Clayman!

[[Clayman Interface]] | 
[[Importing Assets]] | 
[[Work with Tags]] | 
[[Clayman User Folder]]
[[Environment Variables]]


Learn more about Packages:

[[Create - Import a Package]] | 
[[Delete a Package]] | 
[[Import - Export Package]] | 
[[Importing Assets]] | 
[[Work with Tags]] | 
[[Rebuild Package]] | 
[[Edit Asset Package]] 