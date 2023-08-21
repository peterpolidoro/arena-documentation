- [About](#org186fb7a)
- [Images](#orge4deb4d)
- [Schematic](#org0154050)
- [PCB](#org6e9285b)
- [Bill of Materials](#org6fc81f7)
- [Development](#orgd53c327)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org186fb7a"></a>

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


<a id="orge4deb4d"></a>

# Images


<a id="org0154050"></a>

# Schematic


<a id="org6e9285b"></a>

# PCB


<a id="org6fc81f7"></a>

# Bill of Materials


## Board

|    |
|--- |
|  |


## Supplemental

| Item | Description | Manufacturer Part Number | Manufacturer | Quantity |
|---- |----------- |------------------------ |------------ |-------- |


<a id="orgd53c327"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Edit metadata.org

    make -f .metadata/Makefile metadata-edits


## Tangle metadata.org

    make -f .metadata/Makefile metadata


## Edit project

    make -f .metadata/Makefile project-edits
    exit