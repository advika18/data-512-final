# Investigating Systemic Bias in the Police Force 
## DATA 512 Final Project

#### Contributor(s): Advika Battini

## Abstract
The analysis aims to explore the presence (or absence) of systemic racism in the police force using traffic stop data for two cites, San Francisco and Hartford. Traffic stop data between 2013-2016 is used to unearth any biases that may be present. The study builds on the [Stanford Open Policing Project](https://openpolicing.stanford.edu/)

## Data Sources
The data is procured from the [Stanford Open Policing Project](https://openpolicing.stanford.edu/). The data (>200 million records) contains separate csv files for numerous cities and towns across the US. Each row contains data about a police stop, such as the date,purpose of stop, outcome, subject related attributes, vehicle type and optionally (only some of the files) location coordinates. The columns are:

| Date | Time  | Location  | Race | Sex  | Age  | Search Conducted  | Contraband found  | Reason for Stop  | Arrest Made  |
|  :-: |  :-:  |    :-:    |  :-: | :-:  | :-:  |         :-:       |         :-:       |        :-:       |      :-:     |
|  str | str   |    str    |  str | str  | int  |         bool      |         bool      |        str       |      bool    |

The data is publicly available for download [here](https://openpolicing.stanford.edu/data/) under the [Open Data Commons Attribution License](https://opendatacommons.org/licenses/by/summary/)

## Methods

## Conclusion

## Directory Structure
```
hcds
 ┣ data
 ┃ ┣ ct_hartford_shapefiles
 ┃ ┃ ┣ Hartford_Neighborhoods.shp
 ┃ ┃ ┣ ....
 ┃ ┣ ca_san_francisco_2020_04_01.csv
 ┃ ┣ ct_hartford_2020_04_01.csv
 ┃ ┣ hartford_2015_demo.csv
 ┃ ┗ san_francisco_2015_demo.csv
 ┣ images
 ┣ LICENSE
 ┣ README.md
 ┗ final_project.ipynb
```

## License
The repository is available under the [MIT License](LICENSE)
