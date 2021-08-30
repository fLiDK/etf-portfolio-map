# ETF portfolio visualization

![test](https://github.com/fLiDK/etf-portfolio-map/blob/master/demo/demo.gif "Demo gif")

An interactive choropleth map created with GeoPandas and Bokeh. The weight by country of (currently) 4 individually weighted ETFs (Exchange Traded Fund) is displayed on a map.

The total weight is calculated based on given weightings of all individual positions. Due to rounding errors and (possible) different up-to-dateness, slight deviations compared to other sources or the distribution by country given on the product pages may occur.

[Natural Earth Vector data](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-admin-0-countries/) is used for the map.

Sources of the ETF data are the corresponding product pages from Xtrackers respectively iShares.

#### Usage
Use the sliders to change the weight of an individual ETF. When changing weights, the map is only updated if all weights sum up to 100 %.
The colour scheme can be changed using the colour dropdown menu.

Try the notebook with Binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fLiDK/etf-portfolio-map/HEAD)

#### Planned improvements
* dropdown menu to choose different ETFs
* directly retrieve most current data instead of loading sample data/previously prepared data
* create web app using Flask

#### Links
* https://dmnfarrell.github.io/bioinformatics/bokeh-maps (guide with some more information on creating a choropleth map with GeoPandas and Bokeh)
