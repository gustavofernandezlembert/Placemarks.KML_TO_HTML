
# KML to HTML Table Converter

This project aims to simplify the process of converting KML files containing Google Earth placemarks into HTML tables. It eliminates the need for manual extraction and copying of pole coordinates from Google Earth. By uploading a KML file, the app generates an HTML table displaying the placemark names and their corresponding coordinates. Rather than manually copying the placemark coordinates one by one, the proposed workflow involves organizing all placemarks within a folder in Google Earth, exporting the folder as a .kml file, and uploading it to the app. The resulting table can then be easily copied and pasted directly into any report. This tool is especially useful for professionals who frequently use Google Earth and need to include multiple placemark coordinates in their reports.

## Instructions

1. Install the required libraries by running the following command:
   
pip install -r requirements.txt

2. Open the Jupyter notebook `KML_to_HTML.ipynb` to access the code and execute the cells.

3. Follow the instructions within the notebook to upload your KML file, run the conversion, and obtain the HTML table output.

## Requirements

- Python 3.7 or above
- pandas
- xml.etree.ElementTree
- flask


Note:                                                                                                                                                      The script has been developed into a web app and can be accessed through the following link:  https://project-392521.uw.r.appspot.com/                
