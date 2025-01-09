# README: Soil Dataset for Watershed Analysis

## Overview
This dataset contains pre-processed soil data corresponding to the soils within the watershed of interest. The data is provided in two formats: 
- **CSV (Comma-Separated Values):** Standard format for maximum compatibility across platforms.
- **XLSX (Excel Workbook):** Pre-imported and formatted version for ease of use in Excel.

Both files contain identical information and include 730 rows corresponding to the 730 soil IDs within the Vuissens watershed area.

---

## File Contents
1. **Soil_Data.csv**
   - Standard CSV file with UTF-8 encoding.
   - Columns are delimited by commas (`,`).
   - Includes all attributes related to soil properties.
   - **Note:** Some columns (e.g., soil IDs) are formatted as text to prevent issues with misinterpretation as dates by spreadsheet software.

2. **Soil_Data.xlsx**
   - Excel workbook version of the dataset.
   - Pre-formatted to avoid any misinterpretation of data types (e.g., soil IDs remain as text).

---

## How to Use
### CSV File:
1. Open the file in a text editor such as Excel.
2. For Excel users:
   - Use **Data > Get Data > From Text/CSV** to import the file.
   - Set the delimiter to a comma (`,`).
   - Ensure sensitive columns (e.g., soil IDs) are imported as **Text** during the import wizard.

### XLSX File:
1. Open directly in Excel or compatible software.
2. No additional import steps are required; all columns are preformatted.

---

## Notes
- Ensure the files are placed in the same directory as any scripts, models, or tools that reference them.
- The provided data is verified and does not require further processing.
- The dataset is compatible with QGIS-based SWAT+ plugin QSWAT+.
---

## Columns Description (first few)
| Column Name  | Description                        |
|--------------|------------------------------------|
| OBJECTID     | Unique identifier for each soil   |
| MUID         | Map unit ID                       |
| SNAM         | Soil name                         |
| SS5ID        | Subsoil ID                        |
| SOL_ZMX      | Maximum rooting depth (cm)        |
| ANION_EX     | Fraction of anions excluded (%)   |
| SOL_CRK      | Crack volume potential (%)        |
| TEXTURE      | Soil texture classification       |
| SOL_Z1       | Layer depth (cm)                  |
| SOL_BD1      | Bulk density (g/cm³)              |
| SOL_AWC1     | Available water capacity (cm/cm)  |
| SOL_K1       | Soil erodibility factor for the first soil layer, used in erosion calculations. |
| SOL_CBN1     | Soil organic carbon content for the first soil layer (%). |
| CLAY1        | Clay content for the first soil layer (%).         |
| SILT1        | Silt content for the first soil layer (%).         |
| SAND1        | Sand content for the first soil layer (%).         |
| ROCK1        | Rock fragment content for the first soil layer (%). |
| SOL_ALB1     | Soil albedo for the first soil layer, indicating the soil's reflectivity. |
| USLE_K1      | Universal Soil Loss Equation (USLE) K factor for the first soil layer, representing soil erodibility. |
| SOL_EC1      | Electrical conductivity for the first soil layer, representing salinity levels (dS/m). |
| SOL_Z2       | Depth of the second soil layer (mm).            |
| SOL_BD2      | Bulk density of the second soil layer (g/cm³). |
| SOL_AWC2     | Available water capacity for the second soil layer (cm/cm). |
| SOL_K2       | Soil erodibility factor for the second soil layer.       |
| SOL_CBN2     | Soil organic carbon content for the second soil layer (%). |
| CLAY2        | Clay content for the second soil layer (%).        |
| SILT2        | Silt content for the second soil layer (%).        |
| SAND2        | Sand content for the second soil layer (%).        |
| ROCK2        | Rock fragment content for the second soil layer (%). |
| SOL_ALB2     | Soil albedo for the second soil layer.                   |
| USLE_K2      | USLE K factor for the second soil layer.                 |
| SOL_EC2      | Electrical conductivity for the second soil layer (dS/m).       |
| SOL_Z3       | Depth of the third soil layer (mm).             |
| SOL_BD3      | Bulk density of the third soil layer (g/cm³). |
| SOL_AWC3     | Available water capacity for the third soil layer (cm/cm). |
| SOL_K3       | Soil erodibility factor for the third soil layer.        |
| SOL_CBN3     | Soil organic carbon content for the third soil layer (percent). |
| CLAY3        | Clay content for the third soil layer (%).         |
| SILT3        | Silt content for the third soil layer (%).         |
| SAND3        | Sand content for the third soil layer (%).         |
| ROCK3        | Rock fragment content for the third soil layer (%). |
| SOL_ALB3     | Soil albedo for the third soil layer.                    |
| USLE_K3      | USLE K factor for the third soil layer.                  |
| SOL_EC3      | Electrical conductivity for the third soil layer (dS/m).        |
| SOL_Z4       | Depth of the fourth soil layer (mm).            |
| SOL_BD4      | Bulk density of the fourth soil layer (g/cm³). |
| SOL_AWC4     | Available water capacity for the fourth soil layer (cm/cm). |
| SOL_K4       | Soil erodibility factor for the fourth soil layer.       |
| SOL_CBN4     | Soil organic carbon content for the fourth soil layer (%). |
| CLAY4        | Clay content for the fourth soil layer (%).        |
| SILT4        | Silt content for the fourth soil layer (%).        |
| SAND4        | Sand content for the fourth soil layer (%).        |
| ROCK4        | Rock fragment content for the fourth soil layer (%). |
| SOL_ALB4     | Soil albedo for the fourth soil layer.                   |
| USLE_K4      | USLE K factor for the fourth soil layer.                 |
| SOL_EC4      | Electrical conductivity for the fourth soil layer (dS/m).       |
| SOL_Z5       | Depth of the fifth soil layer (mm).             |
| SOL_BD5      | Bulk density of the fifth soil layer (g/cm³). |
| SOL_AWC5     | Available water capacity for the fifth soil layer (cm/cm). |
| SOL_K5       | Soil erodibility factor for the fifth soil layer.        |
| SOL_CBN5     | Soil organic carbon content for the fifth soil layer (%). |
| CLAY5        | Clay content for the fifth soil layer (%).         |
| SILT5        | Silt content for the fifth soil layer (%).         |
| SAND5        | Sand content for the fifth soil layer (%).         |
| ROCK5        | Rock fragment content for the fifth soil layer (%). |
| SOL_ALB5     | Soil albedo for the fifth soil layer.                    |
| USLE_K5      | USLE K factor for the fifth soil layer.                  |
| SOL_EC5      | Electrical conductivity for the fifth soil layer (dS/m).        |
| SOL_Z6       | Depth of the sixth soil layer (mm).             |
| SOL_BD6      | Bulk density of the sixth soil layer (g/cm³). |
| SOL_AWC6     | Available water capacity for the sixth soil layer (cm/cm). |
| SOL_K6       | Soil erodibility factor for the sixth soil layer.        |
| SOL_CBN6     | Soil organic carbon content for the sixth soil layer (%). |
| CLAY6        | Clay content for the sixth soil layer (%).         |
| SILT6        | Silt content for the sixth soil layer (%).         |
| SAND6        | Sand content for the sixth soil layer (%).         |
| ROCK6        | Rock fragment content for the sixth soil layer (%). |
| SOL_ALB6     | Soil albedo for the sixth soil layer.                    |
| USLE_K6      | USLE K factor for the sixth soil layer.                  |
| SOL_EC6      | Electrical conductivity for the sixth soil layer (dS/m).        |
| SOL_Z7       | Depth of the seventh soil layer (mm).           |
| SOL_BD7      | Bulk density of the seventh soil layer (g/cm³). |
| SOL_AWC7     | Available water capacity for the seventh soil layer (cm/cm). |
| SOL_K7       | Soil erodibility factor for the seventh soil layer.      |
| SOL_CBN7     | Soil organic carbon content for the seventh soil layer (%). |
| CLAY7        | Clay content for the seventh soil layer (%).       |
| SILT7        | Silt content for the seventh soil layer (%).       |
| SAND7        | Sand content for the seventh soil layer (%).       |
| ROCK7        | Rock fragment content for the seventh soil layer (%). |
| SOL_ALB7     | Soil albedo for the seventh soil layer.                  |
| USLE_K7      | USLE K factor for the seventh soil layer.                |
| SOL_EC7      | Electrical conductivity for the seventh soil layer (dS/m).      |
| SOL_Z8       | Depth of the eighth soil layer (mm).            |
| SOL_BD8      | Bulk density of the eighth soil layer (g/cm³). |
| SOL_AWC8     | Available water capacity for the eighth soil layer (cm/cm). |
| SOL_K8       | Soil erodibility factor for the eighth soil layer.       |
| SOL_CBN8     | Soil organic carbon content for the eighth soil layer (%). |
| CLAY8        | Clay content for the eighth soil layer (%).        |
| SILT8        | Silt content for the eighth soil layer (%).        |
| SAND8        | Sand content for the eighth soil layer (%).        |
| ROCK8        | Rock fragment content for the eighth soil layer (%). |
| SOL_ALB8     | Soil albedo for the eighth soil layer.                   |
| USLE_K8      | USLE K factor for the eighth soil layer.                 |
| SOL_EC8      | Electrical conductivity for the eighth soil layer (dS/m).       |
| SOL_Z9       | Depth of the ninth soil layer (mm).             |
| SOL_BD9      | Bulk density of the ninth soil layer (g/cm³). |
| SOL_AWC9     | Available water capacity for the ninth soil layer (cm/cm). |
| SOL_K9       | Soil erodibility factor for the ninth soil layer.        |
| SOL_CBN9     | Soil organic carbon content for the ninth soil layer (%). |
| CLAY9        | Clay content for the ninth soil layer (%).         |
| SILT9        | Silt content for the ninth soil layer (%).         |
| SAND9        | Sand content for the ninth soil layer (%).         |
| ROCK9        | Rock fragment content for the ninth soil layer (%). |
| SOL_ALB9     | Soil albedo for the ninth soil layer.                    |
| USLE_K9      | USLE K factor for the ninth soil layer.                  |
| SOL_EC9      | Electrical conductivity for the ninth soil layer (dS/m).        |
| SOL_Z10      | Depth of the tenth soil layer (mm).             |
| SOL_BD10     | Bulk density of the tenth soil layer (g/cm³). |
| SOL_AWC10    | Available water capacity for the tenth soil layer (cm/cm). |
| SOL_K10      | Soil erodibility factor for the tenth soil layer.        |
| SOL_CBN10    | Soil organic carbon content for the tenth soil layer (%). |
| CLAY10       | Clay content for the tenth soil layer (%).         |
| SILT10       | Silt content for the tenth soil layer (%).         |
| SAND10       | Sand content for the tenth soil layer (%).         |
| ROCK10       | Rock fragment content for the tenth soil layer (%). |
| SOL_ALB10    | Soil albedo for the tenth soil layer.                    |
| USLE_K10     | USLE K factor for the tenth soil layer.                  |
| SOL_EC10     | Electrical conductivity for the tenth soil layer (dS/m).        |
| SOL_CAL1     | Calcium carbonate content for the first soil layer (%). |
| SOL_CAL2     | Calcium carbonate content for the second soil layer (%). |
| SOL_CAL3     | Calcium carbonate content for the third soil layer (%). |
| SOL_CAL4     | Calcium carbonate content for the fourth soil layer (%). |
| SOL_CAL5     | Calcium carbonate content for the fifth soil layer (%). |
| SOL_CAL6     | Calcium carbonate content for the sixth soil layer (%). |
| SOL_CAL7     | Calcium carbonate content for the seventh soil layer (%). |
| SOL_CAL8     | Calcium carbonate content for the eighth soil layer (%). |
| SOL_CAL9     | Calcium carbonate content for the ninth soil layer (%). |
| SOL_CAL10    | Calcium carbonate content for the tenth soil layer (%). |
| SOL_PH1      | Soil pH for the first soil layer.                        |
| SOL_PH2      | Soil pH for the second soil layer.                       |
| SOL_PH3      | Soil pH for the third soil layer.                        |
| SOL_PH4      | Soil pH for the fourth soil layer.                       |
| SOL_PH5      | Soil pH for the fifth soil layer.                        |
| SOL_PH6      | Soil pH for the sixth soil layer.                        |
| SOL_PH7      | Soil pH for the seventh soil layer.                      |
| SOL_PH8      | Soil pH for the eighth soil layer.                       |
| SOL_PH9      | Soil pH for the ninth soil layer.                        |
| SOL_PH10     | Soil pH for the tenth soil layer.                        |


---

## Contact
For any questions regarding this dataset, feel free to contact:
[Etienne Delaloye]  
[etienne.delaloye@unil.ch]  
[University of Lausanne]

For further, more in-depth questions regarding this dataset, feel free to contact:
[Joana Eichenberger]
[joana.eichenberger@unibe.ch]
[University of Bern]
