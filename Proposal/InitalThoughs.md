# AgriEmission
The emissions from the agri-food sector are significant when studying climate change. The dataset has 7k rows and 31 columns. The dataset used for the study on CO2 emissions and temperature change for each country from 1990 to 2020 was compiled using data from the FAO (Food and Agriculture Organization of the United Nations) and IPCC (Intergovernmental Panel on Climate Change). All the emission were recorde in kilotones (kt): 1kt = 1000 kg.

# Question of Interest

Global food systems account for roughly one-third of anthropogenic greenhouse gas emissions, yet mitigation policies often struggle to pinpoint where interventions yield the highest environmental return. We are mainly interested in two broad questions:

1. Which specific stages of the food supply chain are most strongly linked to observed surface temperature warming? Do different farming practices have a significant impact on the surface temperature?

2. How does a nation's structural makeup (demographic profile, land dynamics, population breakdown, etc) affect its total emission? 

To avoid algebraic redundancy and severe multicollinearity, we separate our predictors into two distinct regression frameworks corresponding to our two response variables. Question 1 response variable is Average Temperature and Question 2's will be total_emission. Some relevant predicts for question 1 will be Pesticides Manufacturing, Fertilizers Manufacturing, Food Processing, Manure Management, etc. And for question 2 we will focus more on rural vs urban population, forest fires, tropical forests, net forest conservation, rice cultivation etc. 
