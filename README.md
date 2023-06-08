# *Data Analysis of the California Real Estate Market*

This study aims to serve the interests of the general public, specifically those interested in purchasing domestic real estate in California. By providing a comprehensive analysis of various datasets and incorporating macroeconomic factors, our report assists readers in making informed decisions regarding the timing and value of their real estate purchases. Traditionally, demographic and property-related parameters have been the primary considerations when purchasing real estate. However, our report goes beyond these conventional factors by examining and relating macroeconomic aspects to the real estate market. By analyzing trends in the sector, we empower readers to develop a data-backed intuition about the market and make wise decisions. The report utilizes multiple datasets, including the Federal Bureau of Investigation (FBI), Federal Reserve Economic Data (FRED), United States Census Bureau, CUBIT planning, Zillow, California Association of Realtors (CAR), and Kaggle. We leverage these datasets to explore various metrics such as Consumer Price Index (CPI), Federal Debt to GDP, Gross Domestic Product (GDP), House Price Index, Interest Rates, Unemployment, historic prices, and numerous demographic features. By analyzing the California real estate market from multiple angles, our report presents a holistic picture of the trends that impact property prices. By providing detailed visualizations and insights, we enable readers to gain a thorough understanding of the market dynamics and make well-informed decisions when considering real estate purchases in California. 

## *Table of content*
- Introduction
- Datasets
- Tools and Softwares used
- Analysis
- Usage
- Contributors

## *Introduction*

The California real estate market is a dynamic and ever-changing landscape that holds significant opportunities for individuals interested in purchasing residential properties. However, navigating this market can be a daunting task, especially when trying to determine the optimal timing and value of a real estate investment. To address these challenges and serve the interests of the general public, we present this comprehensive report on the "Data Analysis of the California Real Estate Market."
The goal of this report is to provide potential homebuyers in California with a data-driven and insightful resource that assists them in making informed decisions about their real estate purchases. We recognize the importance of considering various factors beyond traditional demographics and property-related parameters when evaluating the market. Therefore, we take a holistic approach by integrating macroeconomic indicators, historical trends, and demographic features into our analysis.
One crucial aspect that individuals often overlook is the timing of their real estate investments. By examining trends and patterns in the market, we can identify favorable periods for purchasing property and gain insights into potential future fluctuations. Our report aims to bridge this gap and equip readers with the tools to make well-timed decisions that align with their financial goals.
In order to construct a comprehensive analysis, we utilize a wide range of reputable datasets. These include the Federal Bureau of Investigation (FBI), Federal Reserve Economic Data (FRED), United States Census Bureau, CUBIT planning, Zillow, California Association of Realtors (CAR), and Kaggle. By drawing upon these diverse sources, we ensure that our report captures the most relevant and up-to-date information to support our analysis.
## *Datasets*
To conduct the analysis, we utilized the following datasets:
- Federal Bureau of Investigation (FBI): Uniform Crime Reporting (UCR) Program dataset, providing crime data reported by law enforcement agencies across the United States.
- Federal Reserve Economic Data (FRED): Economic indicators dataset, including GDP, interest rates, inflation, and other macroeconomic factors.
- United States Census Bureau: Demographic data capturing population trends, household characteristics, and socio-economic factors.
- CUBIT planning (Census & Demographic Data Provider): Detailed demographic and census data specific to California.
- Zillow: Real estate marketplace dataset offering information on property listings, sales, rental prices, and housing market trends.
- California Association of Realtors (CAR): Real estate market statistics dataset, including median home prices, inventory levels, days on market, and sales volume.
- Kaggle: Diverse collection of real estate datasets contributed by the data science community.





## *Tools and Softwares used*
- Python
- SQL
- Tableau
- JupyterNotebook
- Seaborn
- Matplotlib


## *Analysis*

The analysis of the California real estate market aims to provide comprehensive insights into the factors influencing property prices and market trends. By examining a combination of economic indicators, demographic data, and crime statistics, we offer valuable information for potential homebuyers and investors.

### Economic Indicators
The analysis encompasses a range of economic indicators, including GDP, interest rates, inflation, and other macroeconomic factors. By analyzing historical trends and identifying correlations between economic indicators and housing prices, we uncover patterns that help predict future market conditions.

### Demographic Factors
Demographic data plays a crucial role in understanding population composition and its impact on the real estate market. We examine data from the United States Census Bureau and CUBIT planning, focusing on population trends, household characteristics, income levels, and other socio-economic factors. By identifying demographic shifts, we provide insights into emerging market opportunities.

### Crime Statistics
Crime rates significantly impact property values and buyer decisions. We leverage the FBI's Uniform Crime Reporting (UCR) Program dataset to analyze crime trends and patterns. By calculating the "impact of crime" composite attribute, we quantify the overall effect of crime in different areas. This allows us to identify regions with varying crime rates and their potential implications for real estate investments.

### Data Integration and Pre-processing
To ensure a comprehensive analysis, we merge and pre-process datasets from various sources. The "Macroeconomic Data Acquisition.ipynb" notebook consolidates macroeconomic factor datasets, while "Crime data.ipynb" and "Crime_california.ipynb" handle cleaning, transformation, and preprocessing of crime-related data. These steps ensure reliable and accurate analysis.
### Statistical Analysis
We employ statistical analysis techniques to uncover patterns, relationships, and correlations within the data. Exploratory data analysis, descriptive statistics, and data visualization provide meaningful insights into the California real estate market. 

### Visualization
To enhance understanding and interpretation, we provide visualizations and interactive dashboards. Created using tools such as matplotlib, seaborn, and Tableau, these visuals enable users to explore the data, identify trends, and gain actionable insights. Visualizations communicate complex information intuitively.

By combining these analytical approaches, we present a comprehensive and data-driven analysis of the California real estate market. Our goal is to empower readers with knowledge and insights for informed real estate decisions.




## *Usage*
To explore the analysis and findings, please refer to the Jupyter Notebook files provided in this repository. Each notebook corresponds to a specific aspect of the analysis, and they are named accordingly for easy navigation. Please ensure you have the necessary dependencies installed before running the code. Refer to the requirements.txt file for a list of required libraries and their versions.

### Data Acquisition
In our analysis, we utilize multiple datasets to analyze real estate prices. If you wish to add your own datasets, please modify the "Macroeconomic Data Acquisition.ipynb" file according to your requirements after downloading this repository. This file focuses on merging all the datasets that influence macroeconomics.

### Data Pre-processing
The data pre-processing for the analysis is handled by the "Crime data.ipynb" and "Crime_california.ipynb" files. These notebooks handle the necessary steps to clean, transform, and preprocess the crime-related data.

### Visualization
To visualize the data and gain insights, you can utilize the "realestate tableau" file. This file provides interactive visualizations and dashboards to explore the findings of the analysis. You can use Tableau software to open and interact with the visualizations.

Please refer to the respective notebooks and files mentioned above for a step-by-step guide and detailed instructions on how to use the code and resources for the analysis.


### Contributors
- Sai Vasavi Harshavardhan Gupta Somisetty
- Naga Venkata Surya Sai Tanmai Raavi
- Sri Teja Kumar Reddy Tetali
- Akhil Songa
