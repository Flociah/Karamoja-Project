# Karamoja Food Security Monitoring Project

## Overview

The Karamoja Food Security Monitoring Project aims to develop a comprehensive food security monitoring tool for the Karamoja region of Uganda. This project focuses on analyzing crop yield data for sorghum and maize, based on satellite images for the 2017 crop season. The goal is to support decision-making for NGOs working in the region by providing insights into crop productivity and population distribution.

## Objectives

- **Analyze Crop Yield:** Measure and visualize the yield of sorghum and maize in Karamoja.
- **Population Density:** Calculate and analyze population density in relation to crop areas.
- **Interactive Visualization:** Create interactive visualizations using Tableau to support decision-making.

## Data Description

The project uses the following datasets:

1. **Shapefiles:**
   - Boundaries of Uganda Subcounties
   - Boundaries of Uganda Districts
   - Crop Type Map for Sorghum
   - Crop Type Map for Maize

2. **Tables:**
   - **Yield and Population per Subcounty:**
     - `POP`: Total population for the subcounty
     - `S_Yield_Ha`: Average yield for sorghum (Kg/Ha)
     - `M_Yield_Ha`: Average yield for maize (Kg/Ha)
     - `Crop_Area_Ha`: Total crop area for the subcounty (Ha)
     - `S_Area_Ha`: Total sorghum crop area (Ha)
     - `M_Area_Ha`: Total maize crop area (Ha)
     - `S_Prod_Tot`: Total productivity for sorghum (Kg)
     - `M_Prod_Tot`: Total productivity for maize (Kg)

   - **Yield and Population per District:**
     - Same columns as the subcounty dataset but aggregated at the district level.

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Flociah/Karamoja-Project.git
   cd Karamoja-Project
   ```

2. **Install Required Libraries:**

   Ensure you have Python 3.x installed. Install the necessary libraries using pip:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. **Data Files:**

   Place your data files (`Uganda_Karamoja_District_Crop_Yield_Population.csv` and `Uganda_Karamoja_Subcounty_Crop_Yield_Population.csv`) in the `/data` directory.

4. **Run the Analysis:**

   Execute the Jupyter Notebook to perform data cleaning, merging, and calculations:

   ```bash
   jupyter notebook Karamoja-Project.ipynb
   ```

## Data Preparation

1. **Data Import:**
   - Import and read data from CSV files.

2. **Data Cleaning:**
   - Check for missing values and handle them.
   - Remove duplicates if any.

3. **Data Merging:**
   - Merge district and sub-county datasets for comprehensive analysis.

4. **Data Calculations:**
   - Calculate population density and other relevant metrics.

## Visualization

1. **Interactive Dashboard:**
   - Create visualizations in Tableau, including maps and charts.
   - Export dashboards and integrate them into PowerPoint presentations if needed.

2. **Export Data:**
   - Save cleaned and merged data to a CSV file for further analysis or visualization in Tableau.

## Future Work

- **Predictive Analysis:** Forecast future crop yields based on historical data.
- **Geospatial Analysis:** Advanced spatial mapping to identify critical areas.
- **Data Enrichment:** Incorporate additional data sources for a more comprehensive analysis.

## Contributing

If you want to contribute to this project, please fork the repository, make changes, and submit a pull request. Please make sure that your changes are well-documented and tested.


## Contact

For any questions or suggestions, please contact:

- **Name:** Morebu Flociah Bina
- [**Email**](mailto:flociahbina@gmail.com)
- [**GitHub**](https://github.com/Flociah) 

---

Thank you for checking out the Karamoja Food Security Monitoring Project!

