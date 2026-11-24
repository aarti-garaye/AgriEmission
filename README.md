# Dataset
We are using the [Agri-food CO2 Emission Dataset](https://www.kaggle.com/datasets/alessandrolobello/agri-food-co2-emission-dataset-forecasting-ml/data) Forecasting ML curated by Alessandro Lo Bello on Kaggle. The dataset has been constructed by merging and reprocessing approximately a dozen individual datasets from the Food and Agriculture Organization (FAO) and data from IPCC. These datasets were, cleaned, preprocessed and merged together to create a comprehensive and cohesive dataset for analysis and forecasting purposes. The dataset describes CO2 emmissions related to agri-food, which amount to approximately 62% of the global annual emissions.

Indeed, the emissions from the agri-food sector are significant when studying climate change. As the dataset shows, these emissions contribute to a substantial portion of the global annual emissions. Understanding and addressing the environmental impact of the agri-food industry is crucial for mitigating climate change and developing sustainable practices within this sector.

## Data Description and Summary

The dataset has 7k rows and 31 columns. The dataset used for the study on CO2 emissions and temperature change for each country from 1990 to 2020 was compiled using data from the FAO (Food and Agriculture Organization of the United Nations) and IPCC (Intergovernmental Panel on Climate Change). All the emission were recorde in kilotones (kt): 1kt = 1000 kg.

# Question of Interest
Global food systems account for roughly one-third of anthropogenic greenhouse gas emissions, yet mitigation policies often struggle to pinpoint where interventions yield the highest environmental return. We are mainly interested in two broad questions:

1. Which specific stages of the food supply chain are most strongly linked to observed surface temperature warming? Do different farming practices have a significant impact on the surface temperature?

2. How does a nation's structural makeup (demographic profile, land dynamics, population breakdown, etc) affect its total emission? 

# Analysis Plan

We will investigate both questions by using regression techniques learned in class.
