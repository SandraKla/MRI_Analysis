# Software tool for the Analysis and Visualization of MRI images of the brain

[![License](https://img.shields.io/github/license/SandraKla/MRI_Analysis.svg)]()

<img src="www/example.png" align="center"/>


## Installation 

Download the Zip-File from this Shiny App and set your working direction to this path and run:

```bash
# Test if shiny is installed:
if("shiny" %in% rownames(installed.packages())){
  library(shiny)} else{
  install.packages("shiny")}
```

```bash
library(shiny)
runApp("app.R")
```
Or use the function ```runGitHub()``` from the package *shiny*:

```bash
library(shiny)
runGitHub("MRI_Analysis", "SandraKla")
```

All required packages must be downloaded before starting this app. 


## Versions 

* [R](https://www.r-project.org): Version 3.6.1 (_Action of the Toes_)
* [shiny](https://cran.r-project.org/web/packages/shiny/index.html): Version 1.4.0 | 1.4.0.2
* colourpicker: Version 1.1.0
* cowplot: Version 1.1.0
* dplyr: Version 0.8.3
* ggplot2: Version 3.2.1
* ggpubr: Version 0.4.0 (Error: package or namespace load failed for ‘ggpubr’ in loadNamespace(j <- i[[1L]], c(lib.loc, .libPaths()), versionCheck = vI[[j]]): es gibt kein Paket namens ‘car’)
* glmnet: Version 4.0-2
* gridExtra: Version 2.3
* gplots: Version 3.1.0
* plotly: Version 4.9.2
* plyr: Version 1.8.5
* processx: Version 3.4.1
* readxl: Version 1.3.1
* reshape2: Version 1.4.3
* randomcoloR: Version 1.1.0
* Rmisc: Version 1.5
* scales: Version 1.1.0
* shinyWidgets: Version 0.5.3
* shinydashboard: Version 0.7.1
* tidyr: Version 1.0.0
* tidyverse: Version 1.3.0
* XLConnect: Version 1.0.1