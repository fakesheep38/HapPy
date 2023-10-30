# World Map Visualization

This repository contains code and resources for creating a dashboard using Panel, enabling the visualization of the World Happiness Report from 2015 to 2023. This allows for the graphical representation and comparison of various developments in metrics such as country rankings, happiness scores, and explanatory variables. Additionally, the dashboard includes world maps based on different variables, displaying data sorted by year.

## Quick Start Guide: 
All data is located in the "Data" folder. The "data_merge" script combines data from various years into a single file named "data_merged." The "eda" script performs an insightful data analysis. To create the dashboard, use the "dashboard" script. To serve the dashboard locally, use the following command: panel serve dashboard.ipynb


## Data Sources
The data used in this project has been provided by the authors of the World Happiness Report and was accessed via Kaggle.
- Data up to 2022: [World Happiness Report on Kaggle](https://www.kaggle.com/datasets/mathurinache/world-happiness-report)
- Data for 2023: [World Happiness Report 2023 on Kaggle](https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2023)

## Code Attribution

The code in this repository builds upon code and libraries from other repositories. We would like to express our gratitude to the original authors and developers for their work and open-source contributions. Here are the repositories and parts of the code we have used:

- Initial idea: [Towards Data Science](https://towardsdatascience.com/visualizing-worldwide-covid-19-data-using-python-plotly-maps-c0fba09a1b37)
- Initial Dashboard via Panel: [thu-vu92's GitHub Repository](https://github.com/thu-vu92/python-dashboard-panel)
- Interactive World Map: [Medium Article](https://medium.com/@patohara60/interactive-mapping-in-python-with-uk-census-data-using-geoviews-and-panel-fcba3de07778)

### GeoPandas

We use the GeoPandas library to process geospatial data and formats and to display world maps. [GeoPandas Repository](https://github.com/geopandas/geopandas)

### Panel

We use the Panel framework to create interactive widgets and dashboards for the user interface of the world maps. [Panel Repository](https://github.com/holoviz/panel)

### Matplotlib

The Matplotlib library is used to create and visualize the world maps. [Matplotlib Repository](https://github.com/matplotlib/matplotlib)

## License

Please note that the repositories mentioned above each have their own licenses. The use of code provided in this repository is subject to the respective licensing terms of the original repositories.

## Authors

- [Samuel Eleazar Wendt](https://github.com/Weltall-Erde-Mensch)
- [Aniko Bagyi](https://github.com/DAT-Aniko)
- [Laura Jacob](https://github.com/fakesheep38)

## Questions and Support

If you have any questions or need support, feel free to create an issue in this repository or contact us at fakesheep38@gmail.com.

We hope this repository helps you create and explore interesting dashboards. Enjoy using and customizing the code!

If you want to see all the dependencies for this project, please refer to the requirements.txt file.
