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


# Where Aliens Have Landed

Because they're out there!

By Anushka Gami, Ashwini Sarvepalli, Angela Watters

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

## Search The Data & Methods

Below is where we can put some links to both the data and the analysis code as buttons:

```
<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://blog.4dcu.be/programming/2021/05/03/Interactive-Visualizations.html" text="The Analysis" %}
</div>
```

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/angwatters/angwatters.github.io/main/python_notebooks/ufo_sighting_data.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

