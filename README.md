# Land Surface Temperature
The files relevant for the TIL Python Programming project are:
- Latest Data Extraction.ipynb (Exports the available satellite data from Landsat-2 into GeoTIFF format)
- Ground DF.xlsx
- Working Notebook New.ipynb (Only section 2.1 for Landsat-2 data. Data from other sections or other satellites do not need to be used for now.)

The goal of the files is to obtain LST (Land Surface Temperature) data for each of the latitude and longitude coordinates specified in Ground DF.xlsx

Note: Currently, the median values (across all available dates) are saved to the GeoTIFF file in Latest Data Extraction.ipynb. For the purpose of this project, we may need to capture LST changing over time at each particular latitude and longitude. Based on the purpose, the export of the GeoTIFF file in Latest Data Extraction.ipynb can be modified.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/nlpguy2022/osdaic2025.git
2. Create Virtual Environment:
   ```sh
   python -m venv venv
3. Install Dependencies:
  ```sh
   pip install -r requirements.txt
