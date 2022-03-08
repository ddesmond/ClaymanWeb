---
title : USD Support
notetype : feed
date : 22-02-2022
---
### USD Support

Current version is 22.08

Build full USD:

```bash
Mac 10.14 +, Python 3.7 (conda)
python USD/build_scripts/build_usd.py  --prefer-speed-over-safety --build-args USD,"-DPXR_PY_UNDEFINED_DYNAMIC_LOOKUP=ON" --alembic --hdf5 --openvdb --openimageio --opencolorio --no-tests BUILD
```



Add both PYTHONPATH and PATH Environment variables so the libraries are accesible.



Bring your own USD :)
Just drop 