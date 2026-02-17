---
title: "Data visualization"
excerpt: "Easy to use universal graphing tool 1<br/><img src='/images/bokeh_image_300x500.png'>"
collection: portfolio
---

In the course of R&D development I often find myself in the position of trying to take quick looks at CSV files coming out of prototypes and lab instruments to see if they are behaving as expected. Ingesting and plotting each of these became cumbersome, especially for situations where formal analysis was not yet needed, so I wrote a little wrapper for Bokeh to plot arbitrary CSV columns with hover tools, on/off toggles and other nice features. This allows for easy in situ checks of the data with very low overhead in setting up the graph settings. The plots are also saved as html files for easy archiving/retrieval without needing to re-run the tool.

![Image of Bokeh graph](images/bokeh_image.png)

[code]({% link files/build_bokeh_plot_v8.py %})

[example plot from a prototype and external lab equipment temperature sensor]({% link files/sample_4-20-50_1316.html %})
