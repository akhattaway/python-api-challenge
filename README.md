# python-api-challenge
module 6 UT Python API challenge

# Title
Part 1: Weathermaps
Part 2: Vacation Party Time

# Description:
This UT Module 6 python-api-challenge is a two part challenge evaluating weather in part 1 and planning a vacation in part 2.

# Analysis
In part 1 we use a function to randomly get latitude and longitude coordinates and find the nearest city to the coordinates returned. The reason for this is to to determine weather differences in Southern and Northern Hemispheres with an element of randomness. 

You can see results of the analysis in the Resource images. Our dependent variable is Latitude, and our idependent variables are Max Temp, Humidity, Cloudiness, Wind Speed. We  run a regression analysis and plot this for all results and then with filtered results specific to the hemisphere. The findings support the claim that

Part 2 is a little more playful, finding cities with certain features you would want to travel to and the nearest cities. Similar to how I imagine map apps we use every day such as Google Maps or Apple Maps might work.

# Installation
Must have following: 
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
import requests
import time
from scipy.stats import linregress
OpenWeatherMap API key can be obtained <https://openweathermap.org/api>
Geoapify API key can be obtained <https://myprojects.geoapify.com/login>
from citipy import citipy

# Authors and acknowledgment
Contributors to project include: UT Xpert Learning Assistant, ChatGPT, UT Data Analytics Class Material and support for hvplot map from UT Student Ryan Macfarlane.

# Project status
Complete.