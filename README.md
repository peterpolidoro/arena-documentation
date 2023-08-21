- [About](#org3daa40a)
- [Images](#org430ea78)
- [Schematic](#org1256d36)
- [PCB](#orgb697424)
- [Bill of Materials](#orge0eae26)
- [Development](#orgf494e78)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org3daa40a"></a>

# About

```markdown
- Project Name: panels-documentation
- Description: Tools and files to help document the Reiser lab Modular LED Display panels.
- Version: 1.0
- Kicad Version: 7.0.7
- Release Date: 2023-08-21
- Creation Date: 2023-10-21
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/panels-documentation
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2023 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
```


<a id="org430ea78"></a>

# Images


<a id="org1256d36"></a>

# Schematic


<a id="orgb697424"></a>

# PCB


<a id="orge0eae26"></a>

# Bill of Materials


## Board

|    |
|--- |
|  |


## Supplemental

| Item | Description | Manufacturer Part Number | Manufacturer | Quantity |
|---- |----------- |------------------------ |------------ |-------- |


<a id="orgf494e78"></a>

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