# BA780 Team Project: Analyzing the Mortality Trends in the US

 **Contributors:** Ali Saadeddine, Jenil Shah, Rishabh Anand, Yu-Fang(Unice) Liao, Shivakumar Vinod, Rishita Chakraborty

## **Abstract**
This comprehensive study is an exploratory journey of the landscape of mortality in the United States from 2020 to 2023, with a keen focus on uncovering patterns, trends, and anomalies. Utilizing a robust dataset encompassing various causes of death, the research employs data cleaning, statistical analyses, and compelling visualizations. Key visualizations include an insightful portrayal of missing data, a time series analysis of mortality due to all causes contrasted with significant COVID-19 events, and a comparative study of deaths attributable to leading diseases. The study unveils surprising trends and correlations, particularly highlighting the profound impact of the COVID-19 pandemic and its various stages on mortality. Furthermore, it delves into the comparative deadliness of diseases over time, offering crucial insights that could guide public health policies, crisis preparedness, and medical research.

## **Introduction**
The realm of public health has been challenged in recent years, with the advent of the COVID-19 pandemic fundamentally altering the dynamics of diseases and mortality. In light of these developments, our study aims to dissect mortality trends in the United States from 2020 to 2023, probing into the various causes of death and their evolution over time. Through a rigorous process of data cleaning and validation, we confront the challenges posed by missing and incomplete data, ensuring the integrity of our analysis. Our approach utilizes the power of visual analytics to illustrate trends and patterns, drawing deep connections between significant pandemic milestones and national mortality rates. By contrasting the lethality of different diseases throughout the study period, we seek to unravel the broader implications of these mortality trends for public health and safety.

## **Data Information**
***A brief summary of the dataset used are as follows:***

| Dataframe Name     | Brief Description |
| ----------- | ----------- |
| `data_as_of` | Date of recorded deaths       |
| `juris_occur`   | State of occurrence  |
| `mmwr_yr` | Morbidity and Mortality Weekly Report Year Information|
| `mmwr_week` | Morbidity and Mortality Weekly Report Week Information | |
` all_cause` | Includes Death Count due to All Causes |
| `NC` | Includes Death Count due to Natural Causes | |
| `MN` | Includes Death Count due to Malignant neoplasms   | |
| `diabetes` | Includes Death Count due to Diabetes mellitus  | |
| `AD` | Includes Death Count due to Alzheimer disease  | |
| `CLRD` | Includes Death Count due to Chronic lower respiratory diseases | |
| `heart` | Includes Death Count due to Diseases of heart  | |
| `CD` | Includes Death Count due to Cerebrovascular diseases | |
| `covid19_multi` | Includes Death Count due to COVID-19 (Multiple Cause of Death)  | |
| `covid19_underly` | Includes Death Count due to COVID-19 (Underlying Cause of Death)   | |


## **Demo**
***Interactive choropleth map showcasing mortality trends over different dates, jurisdictions, and causes.***


https://github.com/Unice-CS/BA780TeamProject/assets/74975816/600bc70e-782a-4d68-838f-aedf3fa59a43


## **Conclusion**
Our exploration into the mortality trends in the United States from 2020 to 2023 reveals critical insights into the health impacts of the COVID-19 pandemic alongside other leading causes of death. The visual analytics employed vividly illustrate the surge in deaths corresponding with key events of the pandemic, showing the huge impact of COVID-19. Moreover, the comparative analysis of various causes of death highlights the persistent threat posed by conditions such as heart disease and malignant neoplasms, reminding us that these chronic conditions continue to claim lives amidst the global focus on COVID-19. The findings of this study serve as a call for sustained, deliberate efforts in healthcare, emphasizing the need for ongoing care, resource allocation, and research across all fronts of disease management and prevention.

## **Challenges**
The execution of this study was not without its challenges. The initial dataset presented substantial gaps, evidenced by a significant proportion of missing values across various disease categories. The task of data cleaning and imputation was not only necessary but also delicate. Furthermore, the unprecedented nature of the COVID-19 pandemic introduced variability and unpredictability into mortality trends, necessitating a flexible yet robust analytical approach. The rapidly evolving landscape of public health during this period, marked by the emergence of new COVID-19 variants and vaccination efforts, added layers of complexity to the data interpretation.


## **Limitations**
While the study provides valuable insights, it is bound by certain limitations. The presence of missing or incomplete data, despite rigorous cleaning, suggests potential biases or underrepresentations in the findings. The reliance on officially reported data also carries the risk of underestimation due to unreported or misclassified cases, particularly in the context of COVID-19 deaths. Additionally, the study's scope, confined to a specific timeframe, does not include an analysis of longer-term trends or the consideration of seasonal variations and their impact on disease and mortality.

## **Next Steps**
The current study, while comprehensive, opens several avenues for further research, essential for a more nuanced understanding of mortality trends and the factors influencing them. Below are proposed next steps and considerations for subsequent studies:

1. Longitudinal Analysis: Extend the scope beyond the 2020-2023 timeframe to include pre-pandemic years, offering a more contrasted view of mortality trends. A longer timeline would allow for the investigation of whether observed trends are anomalies induced by the pandemic or part of broader, more systemic patterns in public health.

2. Demographic and Socioeconomic Data Integration: Incorporate demographic (age, gender, race, etc.) and socioeconomic (income level, education, occupation, etc.) data to explore disparities in mortality rates. Understanding how mortality is influenced by these factors is crucial for targeted public health interventions and resource allocation.

3. Geospatial Analysis: Conduct a more detailed geospatial analysis to identify if there are location-specific trends or anomalies in mortality. This could involve examining urban versus rural areas or analyzing trends at the state or community level.

4. Healthcare System Data: Integrate data on healthcare system characteristics (e.g., hospital capacity, access to care, treatment types available) to study their correlation with mortality trends. This can reveal critical insights into how healthcare system strengths or vulnerabilities impact outcomes.

5. Disease-Specific Studies: Undertake more granular, disease-specific studies to understand the underlying factors contributing to mortality from different causes. For instance, exploring the correlation between chronic disease management programs and mortality trends could offer insights into effective strategies for reducing deaths from these conditions.

6. Pandemic Response Analysis: Analyze data related to COVID-19 response strategies, including lockdowns, public health campaigns, and vaccination rates, to assess their effectiveness and impact on mortality. This could also involve a comparative study with other countries to glean best practices and lessons learned.

7. Data Quality Improvement: Efforts to enhance data collection and reporting standards are necessary to reduce the number of missing or misclassified data points. Collaboration with healthcare providers, medical examiners, and public health agencies can improve the completeness and accuracy of mortality data.

By pursuing these next steps, future research can build on the findings of the current study to provide more holistic, actionable insights that inform public health policies, pandemic response strategies, and healthcare improvements. The integration of diverse data types and multidisciplinary approaches will be paramount in these endeavors.


## **Citations**
"Bar" Bar Charts in Python Plotly.com/python/bar-charts/.Accessed 15 Oct 2023.

Plot "Correlation Matrix" in Python javatpoint.com/plot-correlation-matrix-in-python/. Accesed 14 Oct 2023.

Timothy L and co authors published it online on 8 March 2023.[Seasonal trends in COVID-19 cases, hospitalizations, and mortality in the United States and Europe.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9994397/).

Reference: https://www.cdc.gov/museum/timeline/covid19.html


Centers for Disease Control and Prevention (CDC). (n.d.). COVID-19 Pandemic Timeline - Monthly Total Deaths (All Cause) from 2020 to 2023. Retrieved from [(https://www.cdc.gov/museum/timeline/covid19.html)]


Plotly. (n.d.). Plotly Express Choropleth Documentation. Retrieved from [(https://plotly.github.io/plotly.py-docs/generated/plotly.express.choropleth.html)]


Plotly. (n.d.). Plotly Choropleth Maps Documentation. Retrieved from [https://plotly.com/python/choropleth-maps/]


Samuel H. Preston, Yana C. Vierboom  (2021). "[Excess mortality in the United States in the 21st century](https://www.pnas.org/doi/10.1073/pnas.2024850118)": A Public Health Study.

"Gen AI" Used Generative AI , Chat-GPT  in https://chat.openai.com/. Accessed 12 Oct 2023.


## **Use of GenAI**
We have utilized Gen AI (Chat GPT) to assist with rectifying errors, converting code, and enhancing the efficiency of code. Additionally, leveraging Gen AI for improving geo maps is a commendable approach.



* We fixed the logic for the bar graph with the help of GenAI to show all the mortality rates in the top 5 states from the year 2020-2023 in a single graph.

* We have used GenAI to fix few of our codes when we were encountering errors. The geo-spatial map had issues with the format of the dates and the datatypes. Furthermore, we were trying to add all the other diseases columns to this map, therefore, we used GenAI to find a solution. However, we were only able to fix the datatype and date issue but couldn’t fix the code to show all the individual diseases.



