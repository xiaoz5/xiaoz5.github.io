---
name: IS 445 Data Visualization Hw.8
tools: [Python, HTML, vega-lite]
image: assets/pngs/side_by_side_building_inventory.png
description: IS 445 Data Visualization Hw.8!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Building Inventory Side-by-side Interactive Visualization

This interactive data visualization, created using Altair and Pandas, offers a dynamic exploration of building inventory data:

<vegachart schema-url="{{ xiaoz5/github.io }}/assets/json/side_by_side_building_inventory.json" style="width: 100%"></vegachart>


By employing interactive elements like <span style="color: #C84113;font-weight: bold;">Brush Selection</span> and <span style="color: #C84113; font-weight: bold;">Dropdown Menus</span>, users can gain valuable insights into factors such as <span style="color: #C84113;font-weight: bold;">Square Footage, Year of Acquisition, Total Floors, and Building Status</span>. The visualizations include a heatmap displaying building counts based on total floors and acquisition years, and a scatter plot that focuses on square footage and acquisition years. Feel free to filter and select specific building statuses to customize their data exploration.

### Side by side with 'from_dirc' Function

<vegachart schema-url="{{ xiaoz5/github.io }}/assets/json/side_by_side_from_dict.json" style="width: 100%"></vegachart>

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

