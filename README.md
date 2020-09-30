# Software tool for the Analysis and Visualization of MRI images of the brain

[![License](https://img.shields.io/github/license/SandraKla/MRI_Analysis.svg)]()
Example:
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

###All required packages are downloaded when starting this app or imported if they already exist. For more information about the required packages use the Wiki.###