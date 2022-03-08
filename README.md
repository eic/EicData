# EicData

Makes use of [gif-lfs](https://git-lfs.github.com/) to such more
smartly store data such as gdml geometries, field maps, etc. Also
makes this substantial chunk optional for
[eAST](https://eic.github.io/east/) users. 

Added files with extension `.gdml`, `.mat`, and `.Bmap` will be
tracked by git-lfs automatically; if you want to add a new type, use
something like
```
git lfs track "*root"
```

Note: This repository was created with eAST in mind, but the contents
are completely independent of eAST.

The sub-directories also contain the macros used to create (or update)
this data, with instructions hosted
[here](https://eic.github.io/east/content/examples.html).
