# US States #

## States-only Datasets ##

### Introduction ###
This is a simple CSV file containing data for the U.S. States, with state abbreviations and populations.  It is designed for a quick setup of dataframes or Python dictionaries used in conjunction with other data for state-based research.  All files in this set contain only information for the 50 U.S. States and District of Columbia, and do not include U.S. Territories or Commonwealths.

The edgelist is designed for use with NetworkX and has all of the states with shared land borders.  Maritime borders are not included in this list.


### Sources ###
The populations for this are taken directly from the U.S. Census data, and uses the 2019 population estimate.  
https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/state/detail/SCPRC-EST2019-18+POP-RES.csv


### Methodologies ###
The intent for this CSV data is for use in Python primarily, and the styles are chosen accordingly.  State names are in lowercase assuming use in Pandas dataframes or as keys for dictionaries, and so are lowercase to make ease of uniform querying and manipulation.  Across datasets, it's been found that capitalization is inconsistent, for example 'District of Columbia' sometimes occurs with a capital 'O' in 'of' which will lead to key errors in Python.  The simplest method to handle this was using all lowercase.  It is trivial to capitalize as desired for display purposes.

State abbreviations are virtually always in all caps, and so it was decided to use that format.  

The order of columns will never change, and columns will not be removed in future versions.  Population will be updated as new U.S. Census data is released.
