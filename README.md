[![BCH compliance](https://bettercodehub.com/edge/badge/Rechenmann-Data-EIRL/BSLPy?branch=master)](https://bettercodehub.com/)

BSLPy
==========

BSLPy is a tool to visualize and pre-process data of the Brain Sound Lab. It is separated in two different parts accessible with a launcher.

![Launcher](res/Documentation/convert_data_gui.png "Launcher")


Data conversion
===============

In order to visualize and pre-process the data, they need to be aggregated into one file per block (or run). This aggregation is made by loading the excel notebook that summarize the experiment. Once loaded, the launcher will evaluate if it has all information to compact the data into NWB format.
The architecture of the files must be such as:


The data is then converted to Neurodata without border format:

![NWB format](https://www.nwb.org/wp-content/uploads/2020/02/nwb_datatypes_overview-1024x491.png "Neurodata without border explanation")

The converted data will be saved in the folder ```EXPERIMENTID\NWB\EXPERIMENTID_Block-N.nwb```


Thanks
======
Thank you to all members of BSL

