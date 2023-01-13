## Fields in datafile galalertobj_detail.csv
### File source
The `galalertobj_detail.csv` file is created from a filtered list of alerts obtained by exectuting a cone search at the position of the host galaxies obtain precviously, to a radius as calculated to encompass the extend of the host galaxy, again as determined previously. The input to this process is thus `HLGalaxies_filtered_wReBmag.csv`. A complete file of alerts is extracted from LCO MARS, rejecting those with a real-bogus rating < 0.5. Further filtering as described is then applied to sanitise the data extract and give this data, viz.

### Field description
The first three columns of this datafile correlate with the host galaxy data extracted from the Hyperleda database and the the effective radius as determined from SDSS analysis. All other data, are obtained from alert analysis of the LCO MARS broker stream, and follow the ZTF AVRO Schema format as described in https://zwickytransientfacility.github.io/ztf-avro-alert/schema.html

For reference a list of the columns are included below:
