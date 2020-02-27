**Investigating Climate Change Through Buoy Data**

*A science fair project by Jason Fischer*

*Copyright 2019*

   In the media, there is a lot of discussion about global warming but not as much information on how it's computed. I was interested in this so I decided to do a science experiment to explore how to calculate climate change. NASA’s Earth Observatory concludes that there is an average global rise in temperature of between .15-0.20℃ per decade after studying data from as far back as 1880. 

  The National Oceanic and Atmospheric Administration (NOAA) has buoys out at sea that monitor air temperature (will be referred to as ATMP) and water temperature (will be referred to as WTMP) and other values but these are the important ones. These buoys are spread across the world and their data has been published from as far back as 1979. The data from these buoys are freely available on the web as text files. Using the data from NOAA, I can use code to determine the average, min, max, etc. over time for each buoy. I have selected four different buoys off the coast of the continental United States to analyze. One is off the coast of California, one is off the coast of Louisiana, one is off the coast of Maine, and one is off the coast of Virginia.

Installation
------------
To set this up as a data workspace in its own [Conda](https://conda.io/en/latest/) environment, run:
```
pip install dataworkspaces
dws clone git@github.com:data-workspaces/buoy-data-analysis.git
cd buoy-data-analysis
conda env create -f environment.yml
conda activate buoy-data-analysis
```
