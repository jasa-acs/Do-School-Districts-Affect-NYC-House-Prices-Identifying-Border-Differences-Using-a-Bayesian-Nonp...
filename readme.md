# Do School Districts Affect NYC House Prices? Identifying Border Differences Using a Bayesian Nonparametric Approach to Geographic Regression Discontinuity Designs

# Author Contributions Checklist Form

## Data

### Abstract

The data used in our paper is a record of property sales in the city of New York for the 2015 year. The files include the sale price, square footage, address, tax and building class of each sold property.  We downloaded this data on February 2, 2020.

### Availability

There are no restrictions on the data. It is freely and publicly available from the City of New York.

### Description

The data used in our paper is a record of property sales in the city of New York. The data are published on an annualized basis at https://www1.nyc.gov/site/finance/taxes/property-annualized-sales-update.page.  The files include the sale price, square footage, address, tax and building class of each sold property.  They are available either in PDF or Microsoft Excel format. In thepaper we used the 2015 data in Excel format. 

## Code

### Abstract

Julia code and jupyter notebooks are available on github.

### Description

The code is provided as a julia package, freely available at https://github.com/maximerischard/GeoRDD.jl. The package contains source files in julia, and jupyter notebooks.

### Optional Information

The sofware requirements are:
- the julia programming language, version 1, available from julialang.org ;
- various julia packages as listed in the Project.toml file of the code repository.

The exact package versions used in the analysis are listed in the Manifest.toml, and will automatically be downloaded and installed when executing the first cell of every notebook available in the github repository

## Instructions for use

### Reproducibility

The code for every figure in the manuscript and supplementary materials is available in a jupyternotebook in the github repository. The README file contains a list of figures and which notebook creates it. Table 2, S-4 and S-5 are reproduced in the “NYC_analysis” notebook, TableS-2 is reproduced in the “Wiggly Boundaries” notebook, and Table S-3 is reproduced in the “Mississippi_sharp_null_sims” notebook.

### Replication

The README file and the SimulatedExample notebook provide a short example using simulated data of how to use the software.
