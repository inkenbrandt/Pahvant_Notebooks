* `GEE Summary-Pahvant By Hydro Div.ipynb` takes output from [Pahvant/Zonal_Summary Google Earth Engine code](https://code.earthengine.google.com/17c7cf17d4bbcf97f29ea50bf63d2859) and summarizes it into units of acre-feet/year and acre-feet per water year
* `Water Budget Remote Sensing Calculations.ipynb` - reads in summary data produced by `GEE Summary-Pahvant By Hydro Div.ipynb` and does volumetric calculations on various watersheds in the region.
* `Spring Analysis.ipynb` compiles and analyzes data from Clear Lake Spring. Fits stage data to flow values. Determines trends of spring data.  Compares spring data to groundwater pumping.
* `Well_Water_Use.ipynb` Pulls water use data from Water Rights website. Examines and fits statistical distributions to pumping and duration data. Generates Monte Carlo estimates of water pumpage.
* `Aquifer_Properties_Estimates.ipynb` Uses probable distributions of aquifer storativity and measured groundwater level changes to estimate storage change. Combines storage change to earlier calculations of discharge from `Well_Water_Use.ipynb` and `Spring Analysis.ipynb`
* `Agricultural Production.ipynb` plots agricultural production data.
* `Zonal_ET` rapid zonal statistics using complex polygons and multiple rasters downloaded from GEE and OpenET.
* `Pavahnt Regional GW Levels and Pumping Saq.ipynb` estimation of Storativity using Ryan Smith approach
