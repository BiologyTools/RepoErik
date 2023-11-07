# Welcome to the BiologyTools github page. 
## Download the version of Bio library/program that fits your needs. 
- BioGTK is a cross-platform version of Bio library providing a ImageView widget for whole slide and image stacks.
- BioCore is a Winforms based windows only library with ImageView control for pyramidal, wholeslide images as well as stacks. 
- BioLib is the cross-platform version of the library without a GUI.
- BioImager is a microscopy imaging application which supports various microscopes by using imported libraries & GUI automation. Supported libraries include Zeiss® & all devices supported by python-microscope.
## Both BioGTK & BioCore come as a library and a program.
- [BioGTK](https://github.com/BiologyTools/BioGTK/releases)
![Nuget](https://img.shields.io/nuget/dt/BioGTK) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8122239.svg)](https://doi.org/10.5281/zenodo.8122239)
- [BioCore](https://github.com/BiologyTools/BioCore/releases)
![Nuget](https://img.shields.io/nuget/dt/BioCore) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8207863.svg)](https://doi.org/10.5281/zenodo.8207863)
- [BioLib](https://github.com/BiologyTools/BioLib) ![Nuget](https://img.shields.io/nuget/dt/BioLib) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8127022.svg)](https://doi.org/10.5281/zenodo.8127022)
- [BioImager](https://github.com/BiologyTools/BioImager) ![Nuget](https://img.shields.io/nuget/dt/BioImager) [![DOI](https://zenodo.org/badge/535162891.svg)](https://zenodo.org/badge/latestdoi/535162891)

All programs & libraries share the ability to save images in ImageJ tiff format with additional metadata which can be opened using any Bio library based program. Bio includes ability to easily create tool scripts, functions, which includes ImageJ macro functions. Bio currently integrates with ImageJ/Fiji through the macro language as well importing & exporting ImageJ ROIs. Check out [library usage](https://github.com/BiologyTools/Bio/wiki/Library-Usage). Scripting with ImageJ & C# can be a powerful tool especially when image acquistion can be controlled programmatically as well. This is what [BioImager](https://github.com/BiologyTools/BioImager) specializes in with the Microscope class that can control Zeiss, & Prior as well as any microscope supported by [Python-Microscope](https://github.com/python-microscope/microscope). 
