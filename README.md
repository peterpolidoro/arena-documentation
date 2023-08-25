- [About](#org1cec653)
- [Images](#org0fdcfe3)
- [Schematic](#org49ec279)
- [PCB](#org3485fe9)
- [Bill of Materials](#orgf452027)
- [Development](#org853af77)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org1cec653"></a>

# About

```markdown
- Project Name: panels-documentation
- Description: Tools and files to help document the Reiser lab Modular LED Display panels.
- Version: 1.0
- Kicad Version: 7.0.7
- Release Date: 2023-08-25
- Creation Date: 2023-10-21
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/panels-documentation
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2023 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
```


<a id="org0fdcfe3"></a>

# Images


<a id="org49ec279"></a>

# Schematic


<a id="org3485fe9"></a>

# PCB


<a id="orgf452027"></a>

# Bill of Materials


## Board

|    |
|--- |
|  |


## Supplemental

| Item | Description | Manufacturer Part Number | Manufacturer | Quantity |
|---- |----------- |------------------------ |------------ |-------- |


<a id="org853af77"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Edit metadata.org

    make -f .metadata/Makefile metadata-edits


## Tangle metadata.org

    make -f .metadata/Makefile metadata


## Edit project

    make -f .metadata/Makefile kicad-edits
    exit

    make -f .metadata/Makefile freecad-edits
    exit