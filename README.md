# Karamoja Food Security Monitoring Project

## Overview

The Karamoja Food Security Monitoring Project was conducted to develop a comprehensive food security monitoring tool for the Karamoja region of Uganda. This project focused on analyzing crop yield data for sorghum and maize, utilizing satellite imagery from the 2017 crop season. The primary goal was to support decision-making for NGOs operating in the region by providing detailed insights into crop productivity and population distribution.

## Objectives

The main objectives of this project were to:
- Measure and visualize the yield of sorghum and maize in the Karamoja region.
- Calculate and analyze population density in relation to crop areas.
- Develop an interactive Tableau dashboard to facilitate informed decision-making.

## Data Description

The analysis was based on datasets specific to the Karamoja region, which included:

### Shapefiles
- **Boundaries of Uganda Subcounties:** Geospatial data defining subcounty boundaries.
- **Boundaries of Uganda Districts:** Geospatial data defining district boundaries.
- **Crop Type Map for Sorghum:** Spatial representation of sorghum fields.
- **Crop Type Map for Maize:** Spatial representation of maize fields.

### Tables
- **Yield and Population per Subcounty:**
  - `POP`: Total population for each subcounty.
  - `S_Yield_Ha`: Average sorghum yield (Kg/Ha).
  - `M_Yield_Ha`: Average maize yield (Kg/Ha).
  - `Crop_Area_Ha`: Total crop area for each subcounty (Ha).
  - `S_Area_Ha`: Total sorghum crop area (Ha).
  - `M_Area_Ha`: Total maize crop area (Ha).
  - `S_Prod_Tot`: Total productivity for sorghum (Kg).
  - `M_Prod_Tot`: Total productivity for maize (Kg).

- **Yield and Population per District:**
  - Similar columns as the subcounty dataset, aggregated at the district level.

## Data Preparation

### Data Import
The initial step involved importing and reading the data from CSV files into the analysis environment.

### Data Cleaning
- **Missing Values:** The datasets were examined for missing values, which were addressed based on the context and significance of the data.
- **Duplicate Records:** Duplicate records were identified and removed to ensure the accuracy of the analysis.

### Data Merging
The sub-county and district datasets were merged to create a unified dataset, enabling a comprehensive analysis across both administrative levels.

### Data Calculations
Population density and other relevant metrics were calculated to support the analysis and visualization efforts.

## Visualization

### Tableau Dashboard

The primary outcome of this project is the interactive Tableau dashboard, which provides a comprehensive visual analysis of crop yields and population density in the Karamoja region. This dashboard is a critical tool for NGOs and other stakeholders, enabling them to explore and analyze key data trends through an interactive interface.

![Tableau Dashboard](screenshots/dashboard.png)

*The Tableau dashboard, as shown above,  provides  an expansive view of the data.*

### Exporting Data
The cleaned and merged dataset was exported as a CSV file, making it available for further analysis or for use in additional tools such as Tableau.

## Future Work

Potential future developments for the project include:
- **Predictive Analysis:** Utilizing historical data to forecast future crop yields and improve long-term planning.
- **Geospatial Analysis:** Conducting more advanced spatial analysis to identify critical areas requiring intervention.
- **Data Enrichment:** Integrating additional datasets, such as climate data and socioeconomic indicators, to enhance the comprehensiveness of the analysis.

## Contributing

Contributions to this project are welcome. If you wish to contribute, please fork the repository, make your changes, and submit a pull request. Ensure that all changes are well-documented and thoroughly tested before submission.

---

## Contact

For any questions, suggestions, or collaboration opportunities, please feel free to reach out. I am open to partnerships, research collaborations, and other opportunities that can enhance the impact of the Karamoja Food Security Monitoring Project.


- **Name:** Morebu Flociah Bina
- [**Email**](mailto:flociahbina@gmail.com)
- [**GitHub**](https://github.com/Flociah) 

---

Thank you for checking out the Karamoja Food Security Monitoring Project!

