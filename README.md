# Digital Divide, Health Inequalities: the Ripple Effect on Well-being Indicators

***

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Data to Analyze](#data-to-analyze)
4. [Analysis](#analysis)
5. [Machine Learning](#machine-learning)
6. [Technologies and tools](#technologies-and-tools)
7. [Conclusion](#conclusion)
8. [Contributors](#contributors)

## Project Overview
In this project, the focus is on exploring the impact of the digital divide and health literacy on well-being indicators among adults aged 50-79 in Spain. The primary goal is to unravel the complex relationships between digital usage, health literacy, and individual well-being, using a dataset obtained from telephone surveys conducted in 2022.

## Screenshot
![Screenshot](IMAGETOADD.png)

## Data Sources
The dataset used for this project was created through telephone surveys, sampling 2,000 adults aged 50-79 years old residing in Spain. It includes demographic information, socio-economic status, digital usage, health literacy, and indicators of individual well-being.

- [Main Data: DDHealth, a cross-sectional sociodemographic health, health literacy and digital divide survey in 2,000 adults aged 50-79 living in Spain in 2022](https://dataverse.csuc.cat/dataset.xhtml?persistentId=doi:10.34810/data765)
- Additional Webscraping Data

## Data to Analyze
- Demographic information and socio-economic status.
- Digital usage indicators, including frequency and types of devices used.
- Health literacy measures.
- Well-being indicators such as happiness, loneliness, and satisfaction.

## Analysis
- Exploratory Data Analysis:
Explore the relationships between demographic factors, digital usage, health literacy, and well-being indicators.
Identify patterns and trends within the dataset.

## Machine Learning
Develop a predictive model to assess general satisfaction based on the gathered data:

## Technologies and tools 

Jupyter notebook for data analysis and model building.

### Python Libraries Used
- pandas, numpy for data manipulation.numpy
- seaborn, matplotlib for data visualization.

### Machine Learning Models: 
- RandomForestClassifier
- GradientBoostingClassifier 
- LogisticRegression
- SVC (Support Vector Classifier)
- KNeighborsClassifier
- DecisionTreeClassifier

### Data Preprocessing: 
- MinMaxScaler
- OneHotEncoder

### Feature Selection: 
- VarianceThreshold
- SelectKBest
- chi2 (Chi-squared statistical test)

### Metrics and Evaluation:
- accuracy_score
- classification_report
- confusion_matrix
- plot_confusion_matrix

### Web scraping for additional data.

## Conclusion
This project sheds light on the interconnectedness of the digital divide, health inequalities, and their impact on individual well-being. The findings underscore the importance of addressing disparities in digital access and health literacy to promote overall satisfaction and happiness. The call to action is to advocate for comprehensive social policies that empower individuals, irrespective of their socio-economic standing, to navigate the complexities of the digital age.

## Contributors
- [Laia Gómez Messía](https://github.com/laiagomezmessia)

