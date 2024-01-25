# EDA-Terremotos-1900-2023

Analisis exploratorio de datos, Bootcamp 11.23
Jesxamir Garcia 

import requests
import zipfile
import pandas as pd
import numpy as np
import folium
import geocoder
import altair
import os
import re
import matplotlib.pyplot as plt
plt.style.use('seaborn-v0_8-whitegrid')
import plotly.express as px
import seaborn as sns

from geopy.geocoders import Nominatim
from folium import plugins
from matplotlib.animation import FuncAnimation

## Importar CVS


