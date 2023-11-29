## readme
Data files are contained within this subfolder. Each datafile, as described below also has an associated markdown file detailing the columns and their meaning.

| Filename                              | Type | Purpose | Description                                                                                       |
|---------------------------------------|------|---------|---------------------------------------------------------------------------------------------------|
| Fields HLG2.md                        | MD   | Info    | Description of columns in HLG2.csv                                                                |
| Fields HLGalaxies_filtered.md         | MD   | Info    | Description of columns in HLGalaxies_filtered.csv                                                 |
| Fields HLGalaxies_filtered_wReBmag.md | MD   | Info    | Description of columns in HLGalaxies_filtered_wReBmag.csv                                         |
| target_alertdata_filt.md              | MD   | Info    | Description of columns in target_alertdata_filt.csv                                               |
| galalertobj_detail.md                 | MD   | Info    | Description of columns in galalertobj_detail.csv                                                  |
| HLG2.csv                              | CSV  | Data    | Raw extract from Hyperleda database based on filter criteria discussed.                           |
| HLGalaxies_filtered.csv               | CSV  | Data    | Augmented galaxy data, with estimated counts of hosted GCs.                                       |
| HLGalaxies_filtered_wReBmag.csv       | CSV  | Data    | Augmented galaxy and GC data, with estimated sizes (effective radius) of host galaxies.           |
| target_alertdata_filt.csv             | CSV  | Data    | List of (filtered) ZTF alerts within 10 Re of host galaxy coordinates (65053 unique alerts) - file split into 2 parts due to size restrictions  |
| galalertobj_detail.csv                | CSV  | Data    | Detailed list of ZTF objects associated with host galaxy alerts, with catalogue cross-correlation (6913) |
| readme.md                             | MD   | Info    | This file                                                                                         |
