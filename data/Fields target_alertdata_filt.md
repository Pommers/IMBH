## Fields in datafile HLGalaxies_filtered.csv
### File source
The `target_alertdata_filt.csv` file is created from a filtered list of alerts obtained by exectuting a cone search at the position of the host galaxies obtain precviously, to a radius as calculated to encompass the extend of the host galaxy, again as determined previously. The input to this process is thus `HLGalaxies_filtered_wReBmag.csv`. A complete file of alerts is extracted from LCO MARS, rejecting those with a real-bogus rating < 0.5. Further filtering as described is then applied to sanitise the data extract and give this data, viz.

`
  (ndethist' > 3) AND (0 > ssdistnr > 2) AND (0 > distpsnr1 > 2) AND (0 > neargaia > 2) AND (0 > neargaiabright > 2)
`

### Field description
The first three columns of this datafile correlate with the host galaxy data extracted from the Hyperleda database and the the effective radius as determined from SDSS analysis. All other data, are obtained from alert analysis of the LCO MARS broker stream, and follow the ZTF AVRO Schema format as described in https://zwickytransientfacility.github.io/ztf-avro-alert/schema.html

For reference a list of the columns are included below:

| name            | units           | description        | source |
|-----------------|-----------------|--------------------|--------|
| galRA           | degrees decimal | Host J2000 RA      | HL     |
| galDEC          | degrees decimal | Host J2000 DEC     | HL     |
| radius          | arcsec          | host galaxy 10 Re  | calc   |
| objID           |                 | Alert object ID    | ZTF    |
| candID          |                 | Alert candidate ID | ZTF    |
| aimage          |                 |                    |        |
| aimagerat       |                 |                    |        |
| b               |                 |                    |        |
| bimage          |                 |                    |        |
| bimagerat       |                 |                    |        |
| candid_dup      |                 | Alert candidate ID |        |
| chinr           |                 |                    |        |
| chipsf          |                 |                    |        |
| classtar        |                 |                    |        |
| clrcoeff        |                 |                    |        |
| clrcounc        |                 |                    |        |
| clrmed          |                 |                    |        |
| clrrms          |                 |                    |        |
| dec             |                 |                    |        |
| decnr           |                 |                    |        |
| deltamaglatest  |                 |                    |        |
| deltamagref     |                 |                    |        |
| diffmaglim      |                 |                    |        |
| distnr          |                 |                    |        |
| distpsnr1       |                 |                    |        |
| distpsnr2       |                 |                    |        |
| distpsnr3       |                 |                    |        |
| drb             |                 |                    |        |
| drbversion      |                 |                    |        |
| dsdiff          |                 |                    |        |
| dsnrms          |                 |                    |        |
| elong           |                 |                    |        |
| exptime         |                 |                    |        |
| fid             |                 |                    |        |
| field           |                 |                    |        |
| filter          |                 |                    |        |
| fwhm            |                 |                    |        |
| isdiffpos       |                 |                    |        |
| jd              |                 |                    |        |
| jdendhist       |                 |                    |        |
| jdendref        |                 |                    |        |
| jdstarthist     |                 |                    |        |
| jdstartref      |                 |                    |        |
| l               |                 |                    |        |
| magap           |                 |                    |        |
| magapbig        |                 |                    |        |
| magdiff         |                 |                    |        |
| magfromlim      |                 |                    |        |
| maggaia         |                 |                    |        |
| maggaiabright   |                 |                    |        |
| magnr           |                 |                    |        |
| magpsf          |                 |                    |        |
| magzpsci        |                 |                    |        |
| magzpscirms     |                 |                    |        |
| magzpsciunc     |                 |                    |        |
| mindtoedge      |                 |                    |        |
| nbad            |                 |                    |        |
| ncovhist        |                 |                    |        |
| ndethist        |                 |                    |        |
| neargaia        |                 |                    |        |
| neargaiabright  |                 |                    |        |
| nframesref      |                 |                    |        |
| nid             |                 |                    |        |
| nmatches        |                 |                    |        |
| nmtchps         |                 |                    |        |
| nneg            |                 |                    |        |
| objectidps1     |                 |                    |        |
| objectidps2     |                 |                    |        |
| objectidps3     |                 |                    |        |
| pdiffimfilename |                 |                    |        |
| pid             |                 |                    |        |
| programid       |                 |                    |        |
| programpi       |                 |                    |        |
| ra              |                 |                    |        |
| ranr            |                 |                    |        |
| rb              |                 |                    |        |
| rbversion       |                 |                    |        |
| rcid            |                 |                    |        |
| rfid            |                 |                    |        |
| scorr           |                 |                    |        |
| seeratio        |                 |                    |        |
| sgmag1          |                 |                    |        |
| sgmag2          |                 |                    |        |
| sgmag3          |                 |                    |        |
| sgscore1        |                 |                    |        |
| sgscore2        |                 |                    |        |
| sgscore3        |                 |                    |        |
| sharpnr         |                 |                    |        |
| sigmagap        |                 |                    |        |
| sigmagapbig     |                 |                    |        |
| sigmagnr        |                 |                    |        |
| sigmapsf        |                 |                    |        |
| simag1          |                 |                    |        |
| simag2          |                 |                    |        |
| simag3          |                 |                    |        |
| sky             |                 |                    |        |
| srmag1          |                 |                    |        |
| srmag2          |                 |                    |        |
| srmag3          |                 |                    |        |
| ssdistnr        |                 |                    |        |
| ssmagnr         |                 |                    |        |
| ssnamenr        |                 |                    |        |
| ssnrms          |                 |                    |        |
| sumrat          |                 |                    |        |
| szmag1          |                 |                    |        |
| szmag2          |                 |                    |        |
| szmag3          |                 |                    |        |
| tblid           |                 |                    |        |
| tooflag         |                 |                    |        |
| wall_time       |                 |                    |        |
| xpos            |                 |                    |        |
| ypos            |                 |                    |        |
| zpclrcov        |                 |                    |        |
| zpmed           |                 |                    |        |
