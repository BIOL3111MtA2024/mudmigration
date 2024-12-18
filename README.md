# Project Title

## Summary


Diatom vertical migration is a worldwide phenomenon that affects tracking of diatom blooms from satellites. Understanding when the diatoms emerge from the sediment during the tidal cycle will improve tracking of diatom blooms. 
Temperature could affect the rate of photosynthesis and degradation of diatoms. In different light conditions, there might be less vertical migration occurring.
Sediment from the Bay of Fundy was incubated at 15°C, 20°C, and 23°C under medium, dim, and full light conditions and analyzed in several different ways. 
To determine if temperature and light influenced vertical migration, lens paper was added onto the surface of the sediment of all conditions and removed after a 6.5-hour period. The lens paper then underwent chlorophyll extraction and analysis.
The data was analysed for potential correlations between chl in different light and temperature conditions and found no statistical significance. 
Hourly samples of the full light condition were taken and found no significant results.
Sampling of the surface community diatom composition found a significant result of temperature on layer and morphosize.

## Highly Qualified Personnel

- Name, Institution, email, ORCID 0000-0000-0000-0000

## Principle Investigators

- Douglas A. Campbell, Mount Allison University, dcampbel@mta.ca, ORCID 0000-0001-8996-5463
- Sarah R. Postuma, Mount Allison University, spostuma@mta.ca 
- Gabriela Feres Chiappetta, Mount Allison University, gfereschiappetta@mta.ca
- Paige I. B. Stuart, Mount Allison University, pistuart@mta.ca
- Lisa Kamtchatnova, Mount Allison University, ekamtchatnova@mta.ca

## Primary Contact  

- Douglas A. Campbell, Mount Allison University, dcampbel@mta.ca, ORCID 0000-0001-8996-5463

## Data sources

- CampbellSOP28ChlorophyllaTurner.pdf used for chlorophyll calculations

## Funding sources

- No funding sources in this project.

## Keywords

- Diatoms, vertical migration, Bay of Fundy, Tides

## Additional information and support

- Sensitive Data Flag - Human Participants:  NO
- Sensitive Data Flag - Indigenous Partnerships: NO
- Sensitive Data Flag - Government Partnerships: NO
- Sensitive Data Flag - Industry Partnerships: NO
- Access Restrictions

## Software  

The software (and version) used to create the dataset.  
R studio and R version 4.3.3 and GoogleSheets (2024) 

## Repo content information

### MetaDataCatalog

Chlorophyll analysis:
https://docs.google.com/spreadsheets/d/16DxWZhYw69ZgACGu82szN9tpgpYYPWIxPXOcSLM2Bo0/edit?usp=sharing

Community composition:
https://docs.google.com/spreadsheets/d/1Ga0qnVxOVR9NwSNI5RM1iz1L2MoCAyF0O4x3D6mCePw/edit?gid=0#gid=0

### Data Dictionary

Chlorophyll analysis:
https://docs.google.com/spreadsheets/d/16DxWZhYw69ZgACGu82szN9tpgpYYPWIxPXOcSLM2Bo0/edit?usp=sharing

Community composition:
https://docs.google.com/spreadsheets/d/1Ga0qnVxOVR9NwSNI5RM1iz1L2MoCAyF0O4x3D6mCePw/edit?gid=1060891329#gid=1060891329


### Data/RawData
Chlorophyll analysis:
vert_migration.csv - Chlorophyll analysis data.

Community composition:
https://docs.google.com/spreadsheets/d/1Ga0qnVxOVR9NwSNI5RM1iz1L2MoCAyF0O4x3D6mCePw/edit?gid=405129858#gid=405129858

### Data/CleanData

vert_migration.rds - Clean and filtered data from chlorphyll analysis.

### Data/ProcessedData

### Code

FileImportFunctions.Rmd - Import functions used for creating other analysis.

light_dark.Rmd - Analyzing the vertical migration in different light and temperature conditions. 

ChlorImport.Rmd - Imports  data from an interactive googlesheet; converts RFU from the Turner Fluorometer to ug Chl cm^-2^; converts a numeric YYYYMMDDHHMM code to Time of Day, and elapsed time; and saves the tidied data as a .Rds for general use.

ChlorLine.Rmd - Analyzes vertical migration per hour in different temperature conditions.

mud_comp.Rmd - Cleaning raw data and calculating cell size. Visualizing cell count, top-bottom ratio, and morphotype with maximum dimension. 

### Docs

CampbellSOP28ChlorophyllaTurner.pdf - instructions on the chlorophyll analysis procedure and calculations. 

### Output

ChlorLine.html - Vertical migration per hour in different temperature conditions
  Figure 1: Chlorophyll concentration at hight tide in the Bay of Fundy at 15°C, 20°C, and 23°C.
  Figure 2: Ratio of Top Chl_ugcm2 to Bottom Chl_ugcm2, Chlorophyll concentration top to bottom ratios at temperatures 15°C, 20°C, and 23°C.

light_dark.html - Light and temperature analysis
  Figure 1: The chlorophyll Chl_ugcm2 of is plotted across 15°C, 20°C, and 23°C and different light conditions and separated into top and bottom sheet
  Figure 2: The Top/Bottom ratio is plotted with the variables of 15°C, 20°C, and 23°C and the different light conditions

mud_comp.html - Community composition analysis document 
  Figure 1: Cell count per maximum dimension and condition
  Figure 2: Cell count per condition
  Figure 3: Top-bottom ratio graph per patch and condition
  Figure 4: Top-bottom ratio per condition, sorted by cell morphotype and size category


