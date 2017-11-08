# GeoPAT 2.0

## Overview

GeoPAT 2.0 (Geospatial Pattern Analysis Toolbox) is a standalone suite of modules written in C and dedicated to analysis of large Earth Science datasets in their entirety using spatial and/or temporal patterns. 
Global scale, high resolution spatial datasets are available but are mostly used in small pieces for local studies. 
GeoPAT enables studying them in their entirety.
GeoPAT’s core idea is to tessellate global spatial data into grid of square blocks of original cells (pixels).
This transforms data from its original form (huge number of cells each having simple content) to a new form (much smaller number of supercells/blocks with complex content).
Complex cell contains a pattern of original variable.
GeoPAT provides means for succinct description of such patterns and for calculation of similarity between patterns.
This enables spatial analysis such as search, change detection, segmentation, and clustering to be performed on the grid of complex cells (local patterns).

![](https://github.com/Nowosad/geopat2_manual/raw/master/figs/logo.png)

The GeoPAT 2.0 software is available at http://sil.uc.edu/cms/index.php?id=geopat2.

The GeoPAT 2.0 manual is at https://rawgit.com/Nowosad/geopat2_manual/master/output/GeoPAT2_Manual.pdf.

## GeoPAT related papers

List of the papers related to the GeoPAT software. The preprints can be found at http://sil.uc.edu/cms/index.php?id=journal-papers.

- Niesterowicz, J. and Stepinski, T.F., 2017. Pattern-based, multi-scale segmentation and regionalization of EOSD land cover. International Journal of Applied Earth Observation and Geoinformation, 62, pp.192-200.
- Niesterowicz, J., Stepinski, T.F. and Jasiewicz, J., 2016. Unsupervised regionalization of the United States into landscape pattern types. International Journal of Geographical Information Science, 30(7), pp.1450-1468.
- Netzel, P. and Stepinski, T.F., 2017. World Climate Search and Classification Using a Dynamic Time Warping Similarity Function. In Advances in Geocomputation (pp. 181-195). Springer
- Netzel, P. and Stepinski, T., 2016. On using a clustering approach for global climate classification. Journal of Climate, 29(9), pp.3387-3401.
- Niesterowicz, J., Stepinski, T. and Jasiewicz, J., 2016, January. Unsupervised Delineation of Urban Structure Types Using High Resolution RGB Imagery. In International Conference on GIScience Short Paper Proceedings (Vol. 1, No. 1).
- Jasiewicz, J., Niesterowicz, J. and Stepinski, T., 2016, January. Multi-resolution, pattern-based segmentation of very large raster datasets. In International Conference on GIScience Short Paper Proceedings (Vol. 1, No. 1).
- Netzel, P., Jasiewicz, J. and Stepinski, T., 2016, January. TerraEx–a GeoWeb app for world-wide content-based search and distribution of elevation and landforms data. In International Conference on GIScience Short Paper Proceedings (Vol. 1, No. 1).
- Netzel, P. and Stepinski, T.F., 2015. Pattern-Based Assessment of Land Cover Change on Continental Scale With Application to NLCD 2001–2006. IEEE Transactions on Geoscience and Remote Sensing, 53(4), pp.1773-1781.
- Jasiewicz, J., Netzel, P. and Stepinski, T., 2015. GeoPAT: A toolbox for pattern-based information retrieval from large geospatial databases. Computers & Geosciences, 80, pp.62-73.
- Stepinski, T.F., Niesterowicz, J. and Jasiewicz, J., 2015. Pattern-based regionalization of large geospatial datasets using complex object-based image analysis. Procedia Computer Science, 51, pp.2168-2177.
- Jasiewicz, J., Netzel, P. and Stepinski, T.F., 2014. Landscape similarity, retrieval, and machine mapping of physiographic units. Geomorphology, 221, pp.104-112.
- Jasiewicz, J., Netzel, P. and Stepinski, T.F., 2014, July. Retrieval of pattern-based information from giga-cells categorical rasters—Concept and new software. In Geoscience and Remote Sensing Symposium (IGARSS), 2014 IEEE International (pp. 1785-1788). IEEE.
- Netzel, P. and Stepinski, T.F., 2014, July. Pattern-based assessment of 2001/2006 land cover change over the entire United States. In Geoscience and Remote Sensing Symposium (IGARSS), 2014 IEEE International (pp. 4188-4191). IEEE.
- Stepinski, T.F., Netzel, P. and Jasiewicz, J., 2014. LandEx—a GeoWeb tool for query and retrieval of spatial patterns in land cover datasets. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 7(1), pp.257-266.
- Jasiewicz, J. and Stepinski, T.F., 2013. Example-based retrieval of alike land-cover scenes from NLCD2006 database. IEEE Geoscience and Remote Sensing Letters, 10(1), pp.155-159.

# Acknowledgements

This work was supported by the University of Cincinnati Space Exploration Institute and by the grant NNX15AJ47G from the National Aeronautics and Space Administration.