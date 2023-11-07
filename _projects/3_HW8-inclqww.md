---
name: Example in Class
tools: [Python, HTML, vega-lite]
image: assets/pngs/interactive_legend.png
description: Ongoing example!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Example including vega-lite

Example that came with the template:

<vegachart schema-url="{{ site.baseurl }}/assets/json/cars.json" style="width: 100%"></vegachart>

## From the vega-editor

Simple barplot secification: 

<vegachart schema-url="{{ site.baseurl }}/assets/json/firstViz_take2.json" style="width: 100%"></vegachart>

Something more complex with interactivity.

<vegachart schema-url="{{ site.baseurl }}/assets/json/interactive_legend.json" style="width: 100%"></vegachart>


## From a dictionary in Altair in Python

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart1.json" style="width: 100%"></vegachart>


### Side by side Static Mobility Dashboard in Python

<vegachart schema-url="{{ site.baseurl }}/assets/json/static_mobility_dashboard.json" style="width: 100%"></vegachart>



### Side by side with 'from_dirc' Function

<vegachart schema-url="{{ site.baseurl }}/assets/json/side_by_side_from_dict.json" style="width: 100%"></vegachart>


## Quick aside into Altair-only plots

<vegachart schema-url="{{ site.baseurl }}/assets/json/population_scatter.json" style="width: 100%"></vegachart>


## Side-by-side, interactive using Altair syntax

<vegachart schema-url="{{ site.baseurl }}/assets/json/side_by_side_mobility_url.json" style="width: 100%"></vegachart>


## Side-by-side, interactive using Alair syntax, local data

<vegachart schema-url="{{ site.baseurl }}/assets/json/side_by_side_with_localdata.json" style="width: 100%"></vegachart>


## Side-by-side, ineractive using Altair syntax, with dropdown 'State'

<vegachart schema-url="{{ site.baseurl }}/assets/json/side_by_side_with_dropdown.json" style="width: 100%"></vegachart>


<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

