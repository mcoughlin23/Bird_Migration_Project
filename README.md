# Bird_Migration_Project

## Overview: 
  In this data set, our team analyzes the differing flight paths between three birds. These birds are Eric, Nico, and Sanne. More specifically, our team wanted to uncover the different migration routes each bird flew south. In addition to this, our team took note of each country the birds stayed in the winter months and then migrated back towards in the spring. Through this analysis, our team also discovered the average distance and speed of each bird.

## How to get started: 
  This data set includes visuals used from plotly. Although our .ipynb file does not show these visuals, we uploaded both .html and .pdf files to display these visuals. In order to have these visuals load in your own notebook, be sure to import the following libraries.
  
  In addition, be sure to download the included .csv file in order to do your own analysis. The .csv file is uploaded under the name "bird_tracking.csv"
  
## Importing libraries
import pandas as pd  

import matplotlib.pyplot as plt 

from plotly import tools

import chart_studio.plotly

from plotly.offline import init_notebook_mode, iplot

init_notebook_mode(connected=True)

import plotly.graph_objs as go

import plotly.figure_factory as ff

from IPython.display import HTML, Image

import plotly.express as px

px.set_mapbox_access_token(open(".mapbox_token").read())

from geopy.geocoders import Nominatim

import ipywidgets as widgets

from ipywidgets import interact, interact_manual

import haversine as hs
