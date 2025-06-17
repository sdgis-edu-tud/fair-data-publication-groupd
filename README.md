# Dataset title

## Table of Contents

- [1. GENERAL INFORMATION](#1-general-information)
- [2. METHODOLOGICAL INFORMATION](#2-methodological-information)
  - [2.1 Research questions, methods and envisioned uses](#21-research-questions-methods-and-envisioned-uses)
  - [2.2 Methods for processing the data](#22-methods-for-processing-the-data)
  - [2.3 Instrument- or software-specific information](#23-instrument--or-software-specific-information)
- [3. FILE OVERVIEW](#3-file-overview)
  - [3.1 File List](#31-file-list)
  - [3.2 Relationship between files](#32-relationship-between-files)
  - [3.3 File formats and naming conventions](#33-file-formats-and-naming-conventions)
- [4. DATA-SPECIFIC INFORMATION](#4-data-specific-information)
  - [4.1 Urban Stream Restoration: Bílá Nisa Data](#41urban-stream-restoration-bila-nisa-data)
- [5. SHARING/ACCESS INFORMATION](#5-sharingaccess-information)
  - [5.1 Licenses/restrictions placed on the data](#51-licensesrestrictions-placed-on-the-data)
  - [5.2 Links to other resources](#52-links-to-other-resources)
  - [5.3 Recommended citation for this dataset](#57-recommended-citation-for-this-dataset)


# 1. GENERAL INFORMATION

## 1.1 Title of Dataset
Normalized Data on Biodiversity, Climate Adaptation & Quality of Life Along The Bílá Nisa Stream in Jablonec nad Nisou

## 1.2 Dataset description
This dataset contains qualitative and quantitative data on biodiversity, climate adaptation and quality of life. The data is normalized (values range from 0-1, indicating good-bad, high-low and otherwise specified). The data is selected with a 100 meter radius along the Bílá Nisa stream. This data is then organized on a grid of 100x100 meters, with a more detailed grid of 50x50 meters further overlayed in the inner city borders of Jablonec nad Nisou.

The research project was conducted for a TU Delft Urbanism MSc elective course Applied Spatial Analytics for Sustainable Urban Development (course code ARFW0501). The course is based on the ReBioClim project, funded by the Interreg Central Europe Program, which focuses on revitalizing small urban streams in European cities to enhance biodiversity, mitigate climate change effects, and improve urban living conditions. Running from June 2024 to January 2027, the project addresses the challenges of urban stream restoration in four Central European cities: Dresden, Jablonec nad Nisou, Poznan and Senica. The case study of this dataset is Jablonec nad Nisou.

Additional details about the project can be accessed [here](https://www.ioer.de/en/projects/rebioclim).

## 1.3 Author Information

A. Investigator (Student 1)  
- Name: Finn van Asch
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: f.w.vanasch@student.tudelft.nl

B. Investigator (Student 2)  
- Name: Frederick Auer
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: f.j.auer@student.tudelft.nl

C. Investigator (Student 3)  
- Name: Matthijs Jerez Nova
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: m.r.jereznova@student.tudelft.nl

D. Investigator (Student 4)  
- Name: Ruofan Lin
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: r.lin@student.tudelft.nl

E. Investigator (Student 5)  
- Name: Ula Nina Kunigėlytė
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: u.n.kunigelyte@student.tudelft.nl

F. Associated study personnel (Tutor 1)
- Name: Daniele Cannatella
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: d.cannatella@tudelft.nl

G. Associated study personnel (Tutor 2)
- Name: Claudiu Forgaci
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: c.forgaci@tudelft.nl

H. Associated study personnel (Tutor 3)
- Name: Yehan Wu
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: Y.Wu-13@tudelft.nl

## 1.4 Dates of data collection
The secondary data was collected and treated between May and June, 2025.

## 1.5 Geographic location of data collection
- Jablonec nad Nisou, Czech Republic, Europe

## 1.6 Keywords
Urban Stream, Restoration, ReBioClim, Biodiversity, Climate Adaptation, Quality of Life, Bílá Nisa, Jablonec nad Nisou, Czech Republic

## 1.7 Language
English

## 1.8 Information about funding sources that supported the collection of the data
This research project was supported by the teachers of the course Applied Spatial Analytics for Sustainable Urban Development and non-financial educational resources provided by TU Delft.


# 2. METHODOLOGICAL INFORMATION
## 2.1 Research questions, methods and envisioned uses
Our research question is that how an integrated urban stream restoration project in Jablonec nad Nisou balance diverse stakeholder interests by identifying areas where improvements in biodiversity, flood risk reduction and quality of life can take place. And we mainly use MCDA to classify the data and then apply K means with the normalized QGIS data to construct typology.

### 2.1.1 Research question 1: Where can the ecological quality of the stream area be enhanced?
- Biodiversity value (quan)
- Biodiverse areas at risk (qual)
- Areas providing biodiversity opportunities (qual)

### 2.1.2 Research question 2: Which areas are the most in need for flood protection?
- Flood risk (qual)
- Surface temperature (quan)
- Vegetation health (qual)
- 
### 2.1.3 Research question 3: Where can improvements in quality of life balance stakeholder interests in areas around the stream?
- Public amenities (quan)
- Accessibility of stream (qual)
- Physical comfort level (quan)

### 2.1.3 Envisioned uses of the dataset
- Evaluate the environmental attributes around the stream and distinguish the habitat quality grades
- Support climate-adaptive stream design by identifying high flood-risk areas
- Evaluate the accessibility of each section of the stream, as well as the comfort and convenience for people to use

## 2.2 Methods for processing the data
- MCDA to select the influencing factors according to the research questions and assign weights for them in order to make the final decision
- Fuzzy AHP to determine which data has a higher weight
- K means to construct typology of data

## 2.3 Instrument- or software-specific information
- QGIS version 3.34.12 was used for making maps
- R studio version 4.5.0 was used for editing reports and gathering products


# 3. FILE OVERVIEW
There are two versions of this dataset.

## 3.1 File List

### 3.1.1 Urban Stream Restoration: Bílá Nisa Data
- "Bila_nisa_urban_stream_project.csv" and "Bila_nisa_urban_stream_project.gpgk": Normalized Data on Biodiversity, Climate Adaptation & Quality of Life Along The Bílá Nisa Stream in Jablonec nad Nisou

## 3.2 Relationship between files:
N/A

## 3.3 File formats and naming conventions
### 3.3.1 File formats
Excel file: .CSV dataset
Geopackage file: .GPGK

### 3.3.2 Naming conventions
N/A

# 4. DATA-SPECIFIC INFORMATION

- Missing data code: N/A
- Not Applicable: N/A

## 4.1 Urban Stream Restoration: Bílá Nisa Data

### 4.1.1 UrbanStreamRestoration_Bila_Nisa.csv
1. Number of variables: 18

2. Number of cases/rows: 573

3. Variable List:

"fid"
- Full name: ID number of grid cell
- Description: ID number of grid cell
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_biodiversity_Floodplain_biotope_value"
- Full name: Floodplain Biotope Value
- Description: Data showeing cover areas with biotope value along the Bílá Nisa
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_biodiversity_Unique_natural_habitats"
- Full name: Diversity of Natural Habitats
- Description: Data showing the relative diversity of natural habitats along the Bílá Nisa
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_biodiversity_Proportion_natural_habitat"
- Full name: Proportion of Natural Habitat Area
- Description: Data showing the proportion of natural habitat area per cell along the Bílá Nisa
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_biodiversity_Weighed_road_segment_length"
- Full name: Weighed Road Segment Length
- Description: Road lenght segment weighed for speed limit, showing relative environmental impact of road infrastructure along the Bílá Nisa
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_biodiversity_Built_up_area"
- Full name: Proportion of Built-up Area
- Description: Data showing the proportion of built area along the Bílá Nisa
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_biodiversity_Ecological_corridors"
- Full name: Ecological corridors
- Description: Data showing the proportional area of ecological corridors along the Bílá Nisa
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_biodiversity_Natural_floodplain_restoration_potential"
- Full name: Potential for Natural Floodplain Restoration
- Description: Potential for Natural Floodplain Restoration
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_biodiversity_Zones_of_protected_natural_areas"
- Full name: Zones of Protected Natural Areas
- Description: Area of Zoning of Protected Natural Areas
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high protection zone), where:
    ->  no zoning protection: (0)
    ->  low zoning protection (0.25): Zone IV
    ->  medium-low zoning protection (0.25): Zone IV and Zone III
    ->  moderate zoning protection (0.75): Zone III

"combined_layer_CA_Flood_damage_risk"
- Full name: Flood Impact Zones in Floodplains
- Description: Flood Impact Zones in Floodplains
- Type of variable: qualitative normalized
- Unit of measurement: 0-1 (low to high), where:
    ->  low flood impact (0): natural forest/wetland
    ->  some flood impact (0.5): arable land/grassland
    ->  high flood risk (1): built-up/paved surfaces

"combined_layer_CA_Impervious_surfaces"
- Full name: Impervious Surfaces
- Description: Impervious Surfaces
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_CA_land_surface_temperature_norm"
- Full name: Night Land Surface Temperature
- Description: Night Land Surface Temperature
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_CA_NDVI"
- Full name: Normalized Difference Vegetation Index
- Description: Normalized Difference Vegetation Index indicates how well the vegetion within an area is doing
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (high to low)

"combined_layer_CA_NDVI_inverted"
- Full name: Normalized Difference Vegetation Index
- Description: NDVI inverted value (1-x)
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (high to low)

"combined_layer_QoL_Access to public green space_public_space_access_norm"
- Full name: Access To Public Green Space
- Description: Access To Public Green Space
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_QoL_Access to public facilities_n_public_functions"
- Full name: Acess To Public Amenities
- Description: Acess To Public Amenities
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_QoL_Access to stream_n_integrated_road_network"
- Full name: Access to Stream
- Description: Access to Stream (space syntax analysis)
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_QoL_Access with public transport_n_public_transport_access"
- Full name: Access to Public Transport
- Description: Access to Public Transport
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_QoL_Air_pollution"
- Full name: Air Pollution
- Description: Combined air pollution concentrations (PM10, PM2.5, NO2, BaP, BzN)
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_QoL_PM10_air_quality_PM10_norm_round"
- Full name: Particulate matter 10
- Description: Concentration of particulate matter PM10
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_QoL_PM25_air_quality_PM25_normnew"
- Full name: Particulate matter 2.5
- Description: Concentration of particulate matter PM2.5
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_QoL_NO2_air_quality_NO2_norm_rounded"
- Full name: Nitrogen dioxide pollution levels
- Description: Concentration of nitrogen dioxide NO2
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_QoL_BaP_air_quality_norm"
- Full name: Benzo(a)pyrene pollution levels
- Description: Concentration of benzopyrene Bap pollutant
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_QoL_BzN_final_newgrid_BZN_norm"
- Full name: Benzene pollution levels
- Description: Concentration of benzene Bap pollutant
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

"combined_layer_QoL_Percentage_tree_cover_perc_treecover"
- Full name: Percentage of Tree Cover
- Description: Percentage of Tree Cover
- Type of variable: quantitative normalized
- Unit of measurement: 0-1 (low to high)

4. Specialised formats or other abbreviations used:
N/A

6. Total file size:
315 KB

# 5. SHARING/ACCESS INFORMATION
## 5.1 Licenses/restrictions placed on the data:
CC BY 4.0

## 5.2 Links to other resources:
N/A

### 5.2.1 Links to publications that cite or use the data:
- [Targeted Urban Stream Renewal: The Case of Bílá Nisa in Jablonec nad Nisou](https://github.com/sdgis-edu-tud/report-asa2025-groupd.git)

### 5.2.2 Links to other publicly accessible locations of the data: 
- N/A

### 5.2.3 Links/relationships to ancillary data sets: 
- N/A

### 5.2.4 Links to publicly accessible scripts for analysis of the dataset:
- [Targeted Urban Stream Renewal: The Case of Bílá Nisa in Jablonec nad Nisou](https://github.com/sdgis-edu-tud/report-asa2025-groupd.git)

### 5.2.5 Was data derived from another source?
Yes

## 5.3 Recommended citation for this dataset:
van Asch, F., Auer, F., Nova, M. J., Lin, R. & Kunigėlytė, U. N. (2025). Targeted Urban Stream Renewal: The Case of Bílá Nisa in Jablonec nad Nisou. TU Delft Faculty of Architecture & The Built Environment. Retrieved from https://github.com/sdgis-edu-tud/report-asa2025-groupd.git

This README.md file template was generated on 2022-04-19 by Claudiu Forgaci and Adele Therias according to the 4TU.ResearchData [Guidelines for creating a README file](https://data.4tu.nl/info/en/use/publish-cite/upload-your-data-in-our-data-repository) and the Cornell University template [Guide to writing "readme" style metadata](https://cornell.app.box.com/v/ReadmeTemplate) and is licensed under CC BY 4.0
