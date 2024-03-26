![Awesome Hyperspectral](media/awesome_hyperspectral.jpg)

# Awesome Hyperspectral [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of awesome projects, papers, and tools for hyperspectral imagery

Some more awesome GIS/Machine Learning/Hyperspectral lists to take a look at:
- [satellite-image-deep-learning](https://github.com/satellite-image-deep-learning/techniques)
- [awesome-hyperspectral-deep-learning](https://github.com/IRCAD/awesome-hyperspectral-deep-learning)
- [awesome-geospatial](https://github.com/sacridini/Awesome-Geospatial)
- [awesome-spectral-indices](https://github.com/awesome-spectral-indices/awesome-spectral-indices)

## Contents

- [Software](#software)
- [Papers](#papers)
- [Data Sources](#data_sources)
- [Resources](#resources)
- [Contributing](#contribute)


## Software

Software, libraries, and code related to building awesome stuff with hyperspectral imagery!

### Software
Standalone applications or plugins for applications.

- [QGIS](https://qgis.org/en/site/) - A free and open source geographic information system capable of processing hyperspectral imagery.
- [EnMAP-Box](https://enmap-box.readthedocs.io/en/latest/) - Python plugin for QGIS designed to process and visualize hyperspectral remote sensing data.
- [AVHYAS](https://sites.google.com/view/avhyas-sac-isro/home) - A free & open source QGIS plugin for advanced hyperspectral image analysis
- [Google Earth Engine](https://earthengine.google.com/) - Cloud computing platform for geospatial data processing and analysis (can also process hyperspectral data!).
- [Planetary Computer](https://planetarycomputer.microsoft.com/) - Multi-petabyte catalog of geospatial data combined with cloud processing tools in Python and R.

### Libraries
Libraries for software development in various programming languages.

#### Python
- [rasterio](https://rasterio.readthedocs.io/en/latest/index.html) - GDAL-based Python library capable of reading hyperspectral data cubes.
- [Xarray](https://docs.xarray.dev/en/stable/) - Xarray makes working with labelled multi-dimensional arrays in Python simple, efficient, and fun!
- [Xarray-spatial](https://xarray-spatial.org/index.html) - Omplements common raster analysis functions using Numba and provides an easy-to-install, easy-to-extend codebase for raster analysis.
- [Spectral Python (SPY)](https://www.spectralpython.net/) - Pure Python module for processing hyperspectral image data.
- [PySptools](https://pysptools.sourceforge.io/index.html) - Tools for hyperspectral imaging
- [rastervision](https://rastervision.io/) - An open-source library for geospatial machine learning projects.  Many deep learning models are capable of using hyperspectral imagery.
- [torchgeo](https://github.com/microsoft/torchgeo) - An open-source library for training machine learning models using PyTorch on geospatial data.
- [EarthPy](https://earthpy.readthedocs.io/en/latest/index.html) - A Python package that makes it easier to plot and work with spatial raster and vector data using open source tools.
- [spyndex](https://github.com/awesome-spectral-indices/spyndex) - Allows use of awesome-spectral-indices formulae in Python.


#### R
- [hsdar](https://rdrr.io/cran/hsdar/) - Manage, analyse, and simulate hyperspectral data.

## Papers

### Spectral Indices
- **Optical Remote Sensing Indexes of Soil Moisture: Evaluation and Improvement Based on Aircraft Experiment Observations** (2021), Sun et al. [[PDF]](https://www.researchgate.net/publication/356348833_Optical_Remote_Sensing_Indexes_of_Soil_Moisture_Evaluation_and_Improvement_Based_on_Aircraft_Experiment_Observations)
- **Red edge spectral measurements from sugar maple leaves** (1993), Vogelmann, Jim & Rock, Barrett & Moss, D.M.. [[PDF]](https://www.researchgate.net/profile/Jim-Vogelmann/publication/4715958_Red_edge_spectral_measurements_from_sugar_maple_leaves/links/0046352c6f67c7264d000000/Red-edge-spectral-measurements-from-sugar-maple-leaves.pdf?_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIn19)
- **Comparative analysis of hyperspectral vegetation indices for remote estimation of leaf chlorophyll content and plant status** (2019), Velichkova, Kalinka & Krezhova, Dora. [[PDF]](https://www.rad-journal.org/helper/download.php?file=../papers/RadJ.2018.03.034.pdf)

### Machine Learning
- **A survey: Deep learning for hyperspectral image classification with few labeled samples** (2021), Jia et al. [[PDF]](https://www.sciencedirect.com/science/article/pii/S0925231221004033)
- **Machine learning based hyperspectral image analysis: A survey** (2019), Gewali et al. [[PDF]](https://arxiv.org/abs/1802.08701)
- **Hyperspectral Image Classification using Machine Learning Approaches** (2020), Dasi et al. [[HTML]](https://ieeexplore.ieee.org/document/9120945)
- **Hyperspectral Image Classification and Dimensionality Reduction: An Orthogonal Subspace Projection Approach** (1994), Harsanyi et al. [[PDF]](https://www2.umbc.edu/rssipl/pdf/TGRS/tgrs.7_94.pdf)
- **Dimensionality reduction of hyperspectral images of vegetation and crops based on self-organized maps** (2019), Hidalgo et al. [[HTML]](https://www.sciencedirect.com/science/article/pii/S221431732030189X)

## Data Sources
### Imagery
- [AVIRIS](https://aviris.jpl.nasa.gov/) - Airbone Visible/Infrared Imaging Spectrometer by NASA, in servce since the early 2000s
- [PRISMA](https://www.eoportal.org/satellite-missions/prisma-hyperspectral) - Medium-resolution (30m) hyperspectral satellite launched in 2019 by the Italian Space Agency
- [EnMAP](https://www.enmap.org/) - Medium-resolution (30m) hyperspectral satellite launched in 2022 by the Earth Observation Center of the German Aerospace Center
- [Wyvern](https://wyvern.space/) - Canadian space company developing high-resolution hyperspectral satellites with deployable optics.
- [Pixxel](https://www.pixxel.space/) - Space data company building a constellation of hyperspectral satellites.
- [Orbital Sidekick](https://www.orbitalsidekick.com/) - Persistent monitoring service with constellation of hyperspectral satellites
- [Planet](https://www.planet.com/products/hyperspectral/) - Mature space data company developing a constellation of 30m GSD hyperspectral satellites

### Hyperspectral Signatures
- [USGS Spectral Library](https://crustal.usgs.gov/speclab/QueryAll07a.php) - Thousands of materials compiled into an easy to search & download library.
- [Urban Surfaces Spectral Library](https://micromet.reading.ac.uk/spectral-library/) - Library of spectral signatures focused on urban materials. Developed by the University of Reading's London Urban Meteorological Observitory.
- [ECOSTRESS Spectral Library](https://speclib.jpl.nasa.gov/) - Library containing over 3400 natural and man made material spectra, and includes data from three other spectral libraries (Johns Hopkins, JPL, and USGS).

## Resources
Additional sources for information related to hyperspectral data processing

- [Wyvern Knowledge Base](https://knowledge.wyvern.space/) - The go-to guide for all things hyperspectral! Now with sample data!
- [L3Harris Documentation](https://www.l3harrisgeospatial.com/docs/BackgroundVegetationIndices.html) - L3Harris' software is paid and closed source, however their documentation provides an excellent source of indices and tutorials for processing hyperspectral imagery.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
