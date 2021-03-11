# Spider Chart Mod

*This is an example demonstrating how a GitHub repository can be structured to contain a Modathon submission.*

*The source code is copied from https://github.com/TIBCOSoftware/spotfire-mods/tree/master/examples/ts-spiderchart-d3*

## Overview

The spider chart mod enables the visualization of multivariate data in the form of a two-dimensional chart with an arbitrary number of quantitative variables represented on axes starting from the same point. It is useful to compare multiple categories or groups of values over common variables in a single diagram to reveal distinct correlations, trade-offs, and a multitude of other comparative measures.

<p align="center">
  <img width="500" alt="Spider chart example" src="SpiderChartModExample.png?raw=true">
</p>

Spider charts (also called radar charts, web charts, start chart, star plot, cobweb charts) have many use cases in different sectors like marketing, analysis, sales, research, education, and more.

## Files

- SpiderChartMod.dxp
- SpiderChartMod.mp4
- All source code files for the mod example can be found in the `src` and `static` folders.

## Build instructions

- Open a terminal at the location of this example.
- Run `npm install`. This will install necessary tools. Run this command only the first time you are building the mod and skip this step for any subsequent builds.
- Run `npm run build`. This will bundle the JavaScript and place it in the `dist` folder. It also copies the contents of `static` into `dist`. This task will not watch for changes in code.

