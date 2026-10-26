# EDS 223 - Assignment 2 - Exploring patterns of environmental justice
This repository houses the analysis for an Environmental Justice spatial project exploring the legacy of redlining in Los Angeles County. Historical HOLC residential security grades (A-D) are joined to present-day census block groups to explore whether the 1930s grades line up with current environmental, socioeconomic, and safety outcomes. Part 1 compares the percentile for Particulate Matter 2.5, the percentile for low life expectancy, and the share of low-income households across grades. Part 2 looks at how bike and pedestrian crashes and fatalities from 2020-2025 are distributed across the same grades.
 
## Repository Structure
```
EDS223-HWK2
├── .gitignore
├── HW2.qmd
├── HW2.pdf
├── LICENSE
├── README.md
└── data
    ├── ejscreen
    │   ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
    │   ├── EJSCREEN_2023_BG_Columns.xlsx
    │   └── ejscreen-tech-doc-version-2-2.pdf
    ├── mapping-inequality
    │   └── mapping-inequality-los-angeles.json
    └── SWITRS_LA
        └── Crashes.csv
 
```
Note: the data folder was not uploaded to this repo due to its size, but is housed locally.
 
## Data Access
Three datasets were used in this analysis.
 
**EJScreen.** Block group level environmental and socioeconomic indicators from the United States Environmental Protection Agency's Environmental Justice Screening and Mapping Tool, 2023 release with state percentiles. The tool has since been decommissioned and is no longer available from the EPA: https://www.epa.gov/ejscreen/download-ejscreen-data
 
**HOLC redlining grades.** Digitized 1930s Home Owners' Loan Corporation residential security maps for Los Angeles, from the Mapping Inequality project at the University of Richmond's Digital Scholarship Lab: https://dsl.richmond.edu/panorama/redlining/
 
**Bike and pedestrian crash records.** Statewide Integrated Traffic Records System (SWITRS), 2020-2025, hosted on the Transportation Injury Mapping System (TIMS) developed by UC Berkeley SafeTREC: https://tims.berkeley.edu/.
 
## Authors and Contributors
- [Ashwin Chockkalingam](https://github.com/ashrcho)
## References/Acknowledgements
- EDS 223 Instructor: Annie Adams
- Assignment Authors: Ruth Oliver & Annie Adams
- Data:
  - U.S. Environmental Protection Agency (EPA). 2023. EJScreen: Environmental Justice Screening and Mapping Tool, Version 2.2.
  - Nelson, Robert K., LaDale Winling, Richard Marciano, Nathan Connolly, et al. "Mapping Inequality," American Panorama, ed. Robert K. Nelson and Edward L. Ayers. Digital Scholarship Lab, University of Richmond. 
  - California Highway Patrol. Statewide Integrated Traffic Records System (SWITRS), 2020-2025. Accessed via the Transportation Injury Mapping System (TIMS), Safe Transportation Research and Education Center, University of California, Berkeley.
