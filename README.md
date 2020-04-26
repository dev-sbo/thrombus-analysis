# Thrombus analysis

In this work, we aims at charaterizing thrombus via a various set experiments. To do so, we want to collect the results of each experiment and cross analyze them.

This repository offers scripts to perform analysis to:
  - Collect results from experiments,
  - Cross analyze these results

### Current Features
  - `analysis_DAPI`: Image processing to measure the number of cell for DAPI Analysis. It returns a csv with the cells and the mask of the cells detected

### Tech
* [ImageJ](https://imagej.nih.gov/ij/index.html) - Image processing and editor interface

### Installation

**Thrombus analysis** requires [imageJ](https://imagej.nih.gov/ij/index.html) or [Fiji](https://imagej.net/Fiji) to be installed. Afterwards, scripts can be installed and run via `Plugin > Macro > Run` and select file with extension '.ijm'
> Note: If you want to add definitely the processing to ImageJ/Fiji menu, follow the procedure [here](https://imagej.net/Scripting#Supported_languages) in section *Adding scripts to the Plugins menu*


License
----

MIT
**Free Software :)**
