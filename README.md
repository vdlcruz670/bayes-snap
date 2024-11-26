# The relationships between snap participation and other socioeconomic variables at the census tract level
 <img src="https://raw.githubusercontent.com/aemmadi/aemmadi/master/wave.gif" width="30">

[![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge)](https://www.r-project.org/)

<br/>

<details>
  <summary><b>Links for each members Github profiles</b></summary>
<br/>
  
[Victoria Dela Cruz](https://github.com/vdlcruz670) <br/>
[Olyann Ta'ase](https://github.com/otaase) <br/>
[Cade Garcia](https://github.com/CadeGarcia) <br/>
[Upumoni Logologo](https://github.com/UpumoniLogologo) <br/>
[Alii Napoleon](https://github.com/napoa26)
</details>
<br/>

## Description
Using data from R's Tidycensus package, we created visuals to explore the relationships between SNAP participation and other socioeconomic variables at the census tract level. We utilized a linear regression model to analyze the correlation between SNAP % and our chosen predictors.

## Data
The dataset for this project includes:

Geography: Census tracts in Hawaii (state FIPS code 15).

Variables:
SNAP Rate: Households receiving SNAP.
Total Households.
Median Income.
Employment Rate.
Poverty Rate: Families below the poverty level.
Education Rate: High school graduates and above.

Data is collected using the tidycensus R package.

## Code
The project relies on the following R libraries:

Data Manipulation and Cleaning: tidyverse, dplyr, janitor, naniar.

Bayesian Modeling: brms, rstanarm, bayesrules, bayesplot.

Visualization: ggplot2, plotly, ggiraph.

Code snippets include fetching ACS data, processing it, and building Bayesian models to analyze SNAP participation rates.


## Plot Previews
<img src= "Figure_images/Dotplot.png" width="350"> <img src= "Figure_images/Top10CensusTracts.png" width="300">  <img src= "Figure_images/Snap_map.png" width="350"> <br/>
<img src= "Figure_images/Posterior_distribution_1.png" width="300"> &nbsp;&nbsp;&nbsp;&nbsp; <img src= "Figure_images/Model_coefficients.png" width="300"> <img src= "Figure_images/Model_vs_data.png" width="300"> <br/>
<img src= "Figure_images/Posterior_distribution_2.png" width="300">


