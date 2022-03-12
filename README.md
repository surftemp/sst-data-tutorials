# sst-data-tutorials

This repository contains tutorials and documentation for using the C3S/CCI sea surface temperature dataset hosted by AWS opendata.

You can click on the button below to run the tutorials. If you want to run them locally, look below for installing the environment locally.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cgentemann/sst-data-tutorials/HEAD)


Please visit https://surftemp.github.io/sst-data-tutorials/ for more details.

A brief summary of this dataset is:

> Global daily-mean sea surface temperatures, presented on a 0.05° latitude-longitude grid, with gaps between available daily observations filled by statistical means, spanning late 1981 to recent time.
>
> Synthesised from multiple Earth orbiting satellites carrying infrared imagers from thousands of billions of individual measurements. Underlying observation resolution ranges from 1 to 20 km, and after gap filling the typical feature resolution is ~20 km. Suitable for large-scale oceanographic meteorological and climatological applications, such as evaluating or constraining environmental models or case-studies of marine heat wave events.
>
> Adhering to community data standards and names. Includes temperature uncertainty information and auxiliary information about land-sea fraction and sea-ice coverage. To understand the data for your application, read the paper [1] using <a href="www.nature.com/articles/s41597-019-0236-x">www.nature.com/articles/s41597-019-0236-x</a> to cite in any published usage.
>
> The v2.1 record is known to have biases associated with desert dust aerosol and erratic calibration of early-record sensors [1]. Adjustments to reduce these biases and include additional uncertainty in these effects have been developed, as described in [2] and are applied to this data. These adjustments operate on monthly and >5 degree time-space scales.
> 
> [1] Merchant, C.J., Embury, O., Bulgin, C.E., Block, T., Corlett, G.K., Fiedler, E., Good, S.A., Mittaz, J., Rayner, N.A., Berry, D., Eastwood, S., Taylor, M., Tsushima, Y., Waterfall, A., Wilson, R. and Donlon, C. (2019), Satellite-based time-series of sea-surface temperature since 1981 for climate applications. Scientific Data 6, 223, doi:10.1038/s41597-019-0236-x
>
> [2] Merchant, C.J. and Embury, O. (2020) Adjusting for desert-dust-related biases in a climate data record of sea surface temperature. Remote Sensing, 12 (16). 2554. ISSN 2072-4292 doi:10.3390/rs12162554

Although the entire datset is over 300Gb in size, a subset of the data can be downloaded selectively to inspect particular areas, locations or time periods.  This tutorial will provide some basic examples of how to do this using the [xarray library]( http://xarray.pydata.org/en/stable/)

# Install locally Instructions
1. If you don't have conda (either with Miniconda or the full AnacondaDistribution) already installed we recommend installing miniconda for latest Python 3.
1. Then clone this repository and, at the root directory, you will find the environment.yml file. That files is basically the list of packages we are going to install.
1. Now create the environment with conda env create --file environment.yml
1. activate the environment with: conda activate OHW
1. call jupyter-lab to get started! Happy hacking!!

