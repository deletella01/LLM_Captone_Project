# EFFECTS OF SOCIO-ECONOMIC FACTORS ON MALNUTRITION AMONG CHILDREN IN AFRICA
## LLM Captone Project
### Introduction
#### Child Malnutrition in Africa: Using Diet Analysis to Predict and Prevent Child Malnutrition
Malnutrition is a significant obstacle to sustainable development, affecting individuals and nations. It encompasses under-nutrition (stunting, wasting, underweight, and micronutrient deficiencies) and over-nutrition (obesity). Malnourished individuals are prone to diseases and low productivity, making combating malnutrition crucial for national productivity.
Child malnutrition remains a significant challenge in Africa, with at least 216 million children affected. Malnutrition is the second leading cause of child mortality in sub-Saharan Africa, after malaria. Various organizations have taken steps to address malnutrition, including the Sustainable Development Goal 2, the World Health Organization's strategic plan, and the African Development Bank's initiatives.
Our dataset was gotten from UNICEF data API: https://sdmx.data.unicef.org/databrowser/index.html?q=UNICEF:NUTRITION(1.0)

#### Research Objective
This research aims to investigate the effect of socio-economic factors like poverty and education on child malnutrition in Africa. The study uses the UNICEF dataset to analyze and predict malnutrition in children by leveraging machine learning and time series forecasting techniques.

### Technical Development
#### Methodology
The research involves data collection from the UNICEF data warehouse, data cleaning and processing, and data exploration. The study focuses on African countries, exploring the variation of malnutrition markers across factors like maternal education level and income level.

##### Modelling and Evaluation
Two models were implemented: Seasonal Autoregressive Integrated Moving Average (SARIMA) and Facebook Prophet. Facebook Prophet was chosen as the final model due to its flexibility and ability to capture granular details.

##### Results and Discussion
The Facebook Prophet model forecasted a general decrease in stunting cases across regions, with some spikes expected in 2025 and 2029. The burden of wasting among children appears to fluctuate, with a drastic decrease in 2021 and a likelihood of spiking up again in 2025 and 2029.

### Conclusion
The research investigates the effect of socio-economic factors on child malnutrition in Africa. The analysis shows that higher cases of stunting, wasting, and underweight are recorded among mothers with no education. The study observes regional variations in malnutrition, with Northern Africa having fewer cases compared to other regions. Time series forecasting indicates a general decrease in malnutrition indicators, with some spikes expected in the future.
