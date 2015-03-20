## Overview

In this chapter we describe our Matlab framework for computing the output of operations in the **Operations** table of the *mySQL* database on time series in the **TimeSeries** table of the database.
The procedure involves three main steps:

1.  Retrieve a set of time series and operations from (the **Results** table) of the database to a local Matlab file, `HCTSA_loc` (use `TSQ_prepared`).

2.  Compute the operations on the retrieved time series in Matlab and storing the results locally (use `TSQ_brawn`).

3.  Write the results back to the **Results** table of the database (use `TSQ_agglomerate`).

The process is represented schematically below.

![**Computation workflow schematic.**The three steps involved in computing time-series analysis operations on a set of time series are labeled: **1**. `TSQ_prepared` (retrieve data, including missing entries, from the database), **2**. `TSQ_brawn` (compute missing time series/operation pairs in HCTSA_loc.mat), **3**. `TSQ_agglomerate` (store the new results back in the database).](ComputationSchematic.png)

A sample script to iterate over these steps is the `sample_runscript` in the **Calculation** directory of the repository.
Additional details of the steps involved are provided below.