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


<vegachart schema-url="{{ site.baseurl }}/assets/json/dashboard_ufo_jekyll_from_dict.json" style="width: 100%"></vegachart>

<img src="/assets/pngs/world_map_aliens.png">

<img src="/assets/pngs/us_ufo_shapes.png">

<img src="/assets/pngs/gb_ufo_shapes.png">

<img src="/assets/pngs/de_ufo_shapes.png">

<img src="/assets/pngs/canda_ufo_shapes.png">

<img src="/assets/pngs/au_ufo_shapes.png">

<img src="/assets/pngs/ufo_shape_per.png">

<img src="/assets/pngs/us_ufo_shapes.png">


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

