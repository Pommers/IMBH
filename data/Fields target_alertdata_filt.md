## Fields in datafile HLGalaxies_filtered.csv
### File source
The `HLGalaxies_filtered.csv` file is created at the end of the `Hyperleda_load.ipynb` Jupyter notebook. It includes data extracted from the **Hyperleda database** based in the filtering criteria discussed in the text. Additional calculated fields are included to predominantly determine the total, visible and percentage count of the GCs hosted around the galaxies through the GCLF. 

### Field description
The columns in the `HLGalaxies_filtered.csv` file include all those in the `HLG2.csv` with additional calculated data. The data column with descriptions in this file (with the exception of the first three columns) follow the ZTF AVRO Schema format and are described in https://zwickytransientfacility.github.io/ztf-avro-alert/schema.html

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
