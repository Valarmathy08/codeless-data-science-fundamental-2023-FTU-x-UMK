# Air Pollution Index in Pahang,Malaysia
# Abstract
Air quality is one aspect that affects human health and daily life. In Pahang, Malaysia, rapid urbanization, and development have raised concerns about the health implications of air pollution. The Air Pollution Index (API), which measures air quality and alerts the public to any possible health dangers, is a useful tool. This study intends to evaluate the trends in API in Pahang, offering information on the area's air quality and creating prediction model that will use past data to predict changes in API level in future.
# Introduction
The Centre for study on Energy and Clean Air (CREA) and Greenpeace Malaysia recently conducted study, and they found that air pollution is to blame for 32,000 preventable deaths in Malaysia each year. Human health is more negatively impacted by ongoing exposure to poor air quality than was previously believed. The urgent need for predictions of the future year's air quality as measured by the Air Pollution Index (API) is addressed in this study. 

This study explores the Air Pollution Index (API) in Pahang, Malaysia. As the air quality continues to get worse every year, there is an increasing demand for predicting the changes in the API. The objective is to predict the API in upcoming years. The API is an important tool for measuring air quality, guiding public health measures, and making decisions about the development of cities.

The source of the dataset is from the Department of Statistics Malaysia. The variables in this dataset are the year, 5 stations, and the air quality status (good, moderate, unhealthy, and very unhealthy). The aim of using this data is to develop a prediction of the changes in API levels for the upcoming year. 

# Methodology
### Data Preprocessing
Data preprocessing is the concept of changing the raw data into a clean data set before it is analyzed or used for modeling in a data analysis or machine learning project. The dataset is preprocessed in order to check missing values, noisy data, and other inconsistencies before executing it to the algorithm. Data preprocessing involves several task, including data cleaning, data reduction, data splitting and more. Data preprocessing is an important step in the data analysis because it helps improve the quality of the data, reduces risk of modeling error, and enhances performances of machine learning models.
### Exploratory Data Analysis EDA
Exploratory Data Analysis (EDA) is an approach to analyzing nad visualizing data sets to summarize their main characteristics with the help of statistical graph and data visualization techniques and tools. For instance descriptive statistics, histogram and scatter plot. EDA often leads to valuable insights and hypotheses that can guide more in-depth analyses.
### Data Visualization
Data visualization is the graphical representation of data to help people understand the patterns, trends, and insight contained within the data more effectively. It involves the use of charts, graph, maps and other visual formats.It is also a powerful tool for simplifying complex data, making it easier to interpret, analyze, and communicate.
### Reporting
Reporting is the process of creating and generating reports that communicate the results, findings, and insight of the data analysis or machime learning workflows. It allows to present analysis, visualizations and key metrics in a structured and easily digestible format.
### Predictive Modeling
Predictive modeling refers to the process of building and evaluating machine learning models and to make predictions or classifications based on historical data. It allows to build, evaluate, and deploy machine learning models foe a wide range of applications, including classification, regression, clustering and more.

## Steps
## 
### 1.Import data
**Excel reader:** Imports data from an Excel file into KNIME workflow.

![excel reader](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/8d86818d-79d8-4c12-b0bf-6e54070442e9)

### 2. Data cleaning and filtering
**Column filter:** Select specific columns of interest from imported data, potentially excluding irrelevant or redundant columns.

![column filter](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/f297fc42-d142-4ea3-a574-1e5d3143d086)

### 3. Data exploration and visualization
**Statistic:** Compute summary statistics and explore the distribution of data to gain initial insights.

![statistic](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/96caa9d0-6e01-4ce2-a37b-bf402c2461b5)

**Color Manager:** Manage colors for visualizations in workflow (used for visualization customization).

![color manager](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/3bf7bd19-67ee-4c3a-b783-0096c0d9aff3)

**Pie/Donut Chart:** Create pie or donut charts to visualize categorical data, allows to explore the distribution of categories within a specific column.

![pie chart](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/3a5a20ed-54b7-4aee-9c21-cafb97867041)

### 4. Data splitting for model training and evaluation
**Partitioning:** Split the data into training and testing sets, preparing it for model training and evaluation. This step ensures that user have separate data subsets for model building and validation.

![partitioning](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/c6108159-f256-4879-87f6-947bc9bed993)

### 5. Model training
**Decision Tree Learner:** Train a decision tree model on the training data. Decision tree models are commonly used for classification or regression tasks.

![decision tree learner](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/e598217d-ab26-4fc1-bb42-b695ab3361c1)

### 6. Model evaluation
**Decision Tree Predictor:** Use the trained decision tree model to make predictions on the testing data.

![decision tree predictor](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/847032b9-4322-4acc-b3e1-2dfc28488439)

**Scorer:** Evaluate and score the performance of the decision tree model using various metrics to assess how well it has learned from the data.

![scorer](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/b3a9863d-f096-465c-b8a6-da8b50e1fe30)

### 7. Data visualization
**Scatter Plot:** Visualize relationships between variables in the data using scatter plots. This step can help to gain insights into how the model's predictions relate to the original data.

![scatter plot (local)](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/52ff49d3-cd4d-46f6-959f-f57ef53b2183)


# Tools of use
![68747470733a2f2f7777772e6b6e696d652e636f6d2f7468656d65732f637573746f6d2f626f6f7473747261705f6b6e696d652f6c6f676f5f626c61636b2e737667](https://github.com/Valarmathy08/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93848560/e504d2c4-3204-417d-8ef9-9f2268ac1288)

# Result 
