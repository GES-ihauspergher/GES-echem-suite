# User guide

The `GES-echem-suite` library is articulated in two submodules: `echemsuite.cellcycling`, for the analysis of cell-cycling experiments, and `echemsuite.cyclicvoltammetry`, for the analysis of cyclic voltammetry experiments.

This guide will walk the user through the basic operations required to load an experimental file, access the data within, and compute the main derived quantities. The guide is organized as follows:

* [Structure of the `echemsuite.cellcycling` module](CellCyclingModule)
  * [Loading a cycling experimental file](CellCycling_Loading)
  * [Acessing the experimental data and derived quantities](CellCycling_AccessingData)
  * [Analyzing complex experiments](CellCycling_AnalyzingExperiment)

* [Structure of the `echemsuite.cyclicvoltammetry` module](CyclicVoltammetryModule)

The library also provides a submodule (`echemsuite.graphicaltools`) containing useful graphical tools to be used in the generation of plots and graphs:
* [A small introduction to the `echemsuite.graphicaltools` module](GraphicalModule).

If you are looking for pre-made scripts ready to be used for data-anlysis tasks please visit the [example page](Examples-main).