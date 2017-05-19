# Globular_Clusters
This repository includes python notebooks for data wrangling globular cluster chemical abundance information.

combine_and_plot_m31.ipynb: 
Collects final, averaged abundance information for globular clusters from many files (one for each globular cluster) and creates a combined, reindexed pandas data frame.  The dataframe is used to make figures of abundance behavior on an element by element basis (e.g. Ca, Si, Ni).

make_pub_table_m31.ipynb: 
Collects individual wavelength measurements of abundances. Measurements had been stored as one file for each element, for each cluster.  For example, for 31 clusters and 20 elements there will be 31x20 flat files. Each file is a table where rows correspond to individual wavelenghts and the second column holds the measurement. The publication table needs to be in the format of individual wavelength in rows, and the measurements for each cluster in columns. Another table holding atomic information for each wavelength is joined to include in the final table as additional columns. 
