---
title: idsr
output: html_document
---

*idsr* is an **R** package for reading data from data bases stored in the IDS format (Alter and Manemakers, 2014) and create data in a form suitable for statistical analysis (in **R**).

## Installation

Use Hadley Wickham's *devtools*:

```
> install.packages("devtools")
> devtools::install_github("goranbrostrom/idsr")
```

and then

```
> library(idsr)
> episodes <- efc(indi, varset)
```
and read the documentation.

# Reference

Alter, George & Kees Mandemakers, 'The Intermediate Data Structure (IDS) for Longitudinal Historical Microdata, version 4', *Historical Life Course Studies* 1 (2014), 1-26.
