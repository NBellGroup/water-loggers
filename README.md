# water-loggers

This repository contains water logger data from undrained, drain-blocked and drained regions of blanket bogs in Forsinard Flows, Moor House, and Migneint. It also contains Python code to process and visualise the water logger data.

The ```CSV``` folder contains raw data files from the loggers. 

The ```EXPORT``` folder contains processed datafiles from all the loggers. It also contains a merged dataframe with all the important logger and metadata in one file. This is probably the most useful file to get started with. 

Two Python 3 jupyter notebooks are included. The [processing notebook](https://nbviewer.org/github/NBellGroup/water-loggers/blob/main/processing.ipynb) includes the code to process the raw csv files and merge them into a single dataframe using the pandas library. The [visualisation notebook](https://nbviewer.org/github/NBellGroup/water-loggers/blob/main/visualisation.ipynb) presents some useful visualisation of the data using the seaborn library.  

Finally, the ```INFO``` folder contains GPS coordinates and satellite images of where the loggers were placed. It also includes a method for how the loggers were installed. 

[Changelog](./CHANGELOG.md)

If you use the data for publication please provide a link to this GitHub repository. 

Any issues contact: ezra.kitson@ed.ac.uk