# P0: Analyze Bay Area Bike Share Data

The source data of this project can be found for public use [here](http://www.bayareabikeshare.com/open-data).

This folder contains the following files:

* **Bay\_Area\_Bike\_Share\_Analysis.ipynb** - Main project file.

* **babs\_datacheck.py; babs\_visualizations.py** - Supplemental scripts for checking
data wrangling, reporting of basic statistics, and creation of exploratory bar
charts and histograms.



Data is split among twelve other files, organized into three sets of four files
each. Prefixing each set is one of three datestamps, showing the end month for
each data collection period (201402, 201408, 201508). Suffixes for each file
indicate contents:

* **\*\_README.txt** - Information about contents of data files.

* **\*\_station\_data.csv** - Basic information about station locations and
capacities.

* **\*\_trip\_data.csv** - Information about each trip taken using the bike share
system.

* **\*\_weather\_data.csv** - Weather information by day for one station in each
city in the bike share program.

## Conda environment
In order to run the software in the same environment as I did, run the following
commands with conda:  
 `conda env export > environment.yml`  
`conda env create -f environment.yml -p /home/user/anaconda3/envs/env_name`  
replacing `/home/user/anaconda3/envs/env_name` to your conda path.
