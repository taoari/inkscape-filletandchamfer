# Inkscape Fillet and Chamfer Extension

This repo implements the Fillet and Chamfer function for inkscape described as <http://launchpadlibrarian.net/12692602/rcp.svg>. `svgpathtools` library is required.

Setup
-----

```
pip install svgpathtools --user
cp filletchamfer.inx ~/.config/inkscape/extensions/
cp filletchamfer.py ~/.config/inkscape/extensions/
```

The extension can be accessed form `Extensions` -> `Generate from Path` -> `Fillet and Chamfer`.

Samples
-------

![Alt text](images/sample.svg)