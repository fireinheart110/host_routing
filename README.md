# The complementary optimization of opportunistic maintenance strategy and route design drives the operation and maintenance of offshore wind power

This folder contains all the data and code used in:



**Please use the reference above if you use parts of the code or data**

All the parts of the analysis performed in the paper have been concatenated into a single python notebook: <code>host_routing_code.ipynb</code>
To execute the cells in this notebook, all the data and code must be downloaded and saved in the same folder.

- <code>host_routing_code.ipynb</code>:
	Contains all the code necessery for the analysis of the paper, from data importing, processing and result analysis.

- <code>{HOST, BESN, PBOS, TBS, CMS}_?wt.xlsx</code>:
	Excel files that contain precalculated metrics for 30 weather scenarios used in the analysis in the paper.

- <code>method_of_bins.csv</code>:
	A csv file containing data used for the binning method and the construction of the power curve.

- <code>da_hrl_lmps_ZONE2014.csv</code>:
	A csv file containing raw hourly electricity price data used in Case Study II, downloaded from PJM data miner 2.

- <code>wind_wave_data.csv</code>:
	A csv file containing pre-processed hourly wind speed and wave height data, downloaded from NYSERDA.

- <code>wind_wave_data11.csv</code>:
	A csv file containing pre-processed min10 wind speed and wave height data, downloaded from NYSERDA.

**Attention: Because the simulation data JSON file is too large, it is not stored in this repository, and readers should pay attention to the file path when executing the cells in this notebook**
