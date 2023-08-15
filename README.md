# water-loggers

This repository contains water logger data from undrained, drain-blocked and drained regions of blanket bogs in Forsinard Flows, Moor House, and Migneint. It also contains Python code to process and visualise the water logger data.

The ```CSV``` folder contains raw data files from the loggers. These were originally .txt and had inconsistent delimiters so I manually converted them to .csv. 

The ```EXPORT``` folder contains processed datafiles from all the loggers with WTD(mm) values. It also contains a merged dataframe with all the importand logger data and their  metadata in one file. This is probably the most useful file to get started with. 

Two Python 3 jupyter notebooks are included. The processing.ipynb notebook includes the code to process the raw csv files and merge them into a single dataframe using the pandas library. The visualisation.ipynb presents some useful visualisation of the data using the seaborn library.  

Finally, the ```INFO`` folder contains GPS coordinates and satellite images of where the loggers were placed. It also includes a method for how the loggers were installed. 

This repository will be updated soon to include data from blanket bogs in Langwell. 

If you use the data for publication please provide a link to this GitHub repository. 

Any issues contact: ezra.kitson@ed.ac.uk