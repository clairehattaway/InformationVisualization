# Mapping the Leaf
Interactive, animated visualization of word forms of tea and influence of trade routes.

## Getting Started
All of the code needed to recreate the visualization is located in the MappingTea.ipynb notebook! The only additional step is verifying the upload path of the TeaDerivation+WordForms_All.csv file to ensure it's read by Pandas correctly. Afterwards, the visualization should generate properly if cells are ran sequentially.

The resulting MappingTea (2).html file is also included in the file. You can download the file, and the map should populate without an issue!

### Dependencies
All specially downloaded libraries are listed in the notebook cells for ease of use! The installations and imports are listed below for reference as well:
'''bash
!pip install arcgis
!pip install folium
!pip install searoute

import folium
import pandas as pd
from folium.plugins import TimestampedGeoJson
from branca.element import Element
import folium.plugins as plugins
from IPython.display import HTML, display
import requests
'''
