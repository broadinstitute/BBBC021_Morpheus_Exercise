# BBBC021_Morpheus_Exercise

Files and instructions for exploring per-well mean profile data from the [BBBC021 public data set](https://bbbc.broadinstitute.org/BBBC021); see this site for information on how the data set was created, other works using this data set, etc.

Per-well mean data, image metadata, and MOA data were pulled from the [cytominer_gallery](https://github.com/cytomining/cytominergallery/tree/master/inst/extdata) repository. See that repository for vignettes on how to explore this data set with R.

The CSVs and GCT files were made using pandas (1.2.5) and pycytominer (commit b8fb8659cba85f885b48113886772f92406b6817) in Jupyter notebook (6.4.0) in Python 3.8.11. Graphs were made with seaborn 0.11.1.

Cell images are sourced from the [Reactome Libray of icons for Enhanced High Level Diagrams](https://reactome.org/icon-lib)
