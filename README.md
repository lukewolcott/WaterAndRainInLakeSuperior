##WaterAndRainInLakeSuperior

We look at monthly precipitation levels of Lake Superior, and water level measurements at Marquette, MI.  These out-of-phase oscillations result in a phase diagram with a one-dimensional circle.  We use a topological data analysis package, TDA, to compute the persistent homology and barcode for this data, and detect the circle.

Our purpose is to use real data to give an example of topological data analysis, specifically persistent homology.  By looking at the relationships between points of a data set on a range of scales, topological data analysis allows us to find the "shape of the data".  In the simple example of a two-dimensional cloud of points, we have two tests: the zeroth homology H0 counts the number of components, and the first homology H1 counts the number of circles.

Our example aims to be as simple as possible, and to illustrate reproducibly the pipeline from data to insight.  We will find a circle in the data of rainfall and water level of Lake Superior.

#### Relevant Contents

- water_and_rain.md: Markdown file of complete analysis, viewable in Github.
- water_and_rain.html: HTML version.
- water_and_rain.pdf: PDF version.
- water_and_rain.Rmd: source R Markdown version.


- waterlevel.csv: raw data file used in analysis
- precip_ls.csv: raw data file used in analysis