# U.S. States Information #
Data on U.S. states, intended for use in other projects

### Quick Links ### 

[U.S. States, abbreviations and population](https://raw.githubusercontent.com/crinexus/US-States/master/states-only/us-states.csv)  
[U.S. States (non-maritime) borders edgelist](https://github.com/crinexus/US-States/raw/master/states-only/us-states.edgelist)

### Versions ###

Several flavors of this data are, or will be, available.  The current release is for U.S. States only, without the addition of commonweaths or U.S. territories.  Future releases will be available that includes these areas.  

More granular county and city level versions planned for future releases.


### Prep Code ###

The files in the prep directory and subdirectories are not intended for direct use.  These files contain human-readable setup files to be parsed into program-usable formats.  The initial design for this was centered around the counties, where many states have counties with the exact same names.  FIPS numbers identify these counties uniquely, but are difficult to work with and debug for a person.  The conversion utility converts all counties into FIPS identifiers with county names only as labels for use in practice.

### Notice ###

This is very much a rough-draft repository.  It's recommended that if using any of the data files in this, to not link directly to the raw files as they will most likely have locations in the directory structure moved as more data is added to this set.


### Usage Restrictions ###

Absolutely none.  Please feel free to use these in any way, including redistribution and resale (if that's even possible).  No credit or linking required.  This work is in the public domain and for any and all to use.  Enjoy.
