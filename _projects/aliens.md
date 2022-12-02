---
name: Alien Sighting Data Set 
tools: [Python, HTML, vega-lite, Jekyll]
image: assets/pngs/aliens.jpeg
description: Data visualizations using the Alien Sighting data set
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


<center> <h1>Where Aliens Have Landed</h1></center>



<center>By Anushka Gami, Ashwini Sarvepalli, and Angela Watters</center> 

<img src="/assets/pngs/aliens.jpeg" width="600">
<center><h5>They're out there!</h5></center>

## Introduction
This is the introduction 
## 1. Interactive Chart
<vegachart schema-url="{{ site.baseurl }}/assets/json/dashboard_ufo5_from_dict.json" style="width: 100%"></vegachart>

## 2. Alien Sightings Throughout the World 

<img src="/assets/pngs/world_map_aliens.png">

## 3. Shape by Country 

<img src="/assets/pngs/us_ufo_shapes.png">

<img src="/assets/pngs/gb_ufo_shapes.png">

<img src="/assets/pngs/de_ufo_shapes.png">

<img src="/assets/pngs/canda_ufo_shapes.png">

<img src="/assets/pngs/au_ufo_shapes.png">

## 4. Thoughts on Shape

<img src="/assets/pngs/ufo_shape_per.png">

<img src="/assets/pngs/us_ufo_shapes.png">

## 5. Length  of Encounters World Wide 

<img src="/assets/pngs/max_min_encounter.png">

<img src="/assets/pngs/average_encounter.png">

## Sources

National UFO Reporting Center 
https://nuforc.org/about-us/

World of UFO Sightings 
https://www.kaggle.com/code/moosecat/world-ufo-sightings

USA UFO sightings (Python 3 version) 
https://notebook.community/valter-lisboa/ufo-notebooks/Python3/.ipynb_checkpoints/ufo-sample-python3-checkpoint

Naiman, Jill. Prep-Notebook. Week 3. Finishing up: Visualizing Datatypes - Tabular data with Pandas 
https://uiuc-ischool-dataviz.github.io/is445_oauoag_fall2022/nbv.html?notebook_name=%2Fis445_oauoag_fall2022%2Fweek03%2Fprep_notebook_week03.ipynb

Naiman, Jill. Prep-Notebook. Week 4 
https://uiuc-ischool-dataviz.github.io/is445_oauoag_fall2022/nbv.html?notebook_name=%2Fis445_oauoag_fall2022%2Fweek04%2Fprep_notebook_week04.ipynb

## Search The Data & Methods

Below is where we can put some links to both the data and the analysis code as buttons:


<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/angwatters/angwatters.github.io/main/python_notebooks/ufo_sighting_data.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/angwatters/angwatters.github.io/blob/main/python_notebooks/Sarvepalli_Gami_Watters_Final_Project_3.ipynb" text="The Analysis" %}
</div>

