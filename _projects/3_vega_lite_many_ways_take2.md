---
name: BigFoot Data Set
tools: [Python, HTML, vega-lite, Jekyll]
image: assets/pngs/bigfoot.jpeg
description: Data Visualization using the BigFoot sightings data set
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Big Foot Dashboard



<vegachart schema-url="{{ site.baseurl }}/assets/json/dashboard_bf_from_dict.json" style="width: 100%"></vegachart>




<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>
