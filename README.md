# CMPS451 - Data Mining, Big Data, and Data Analytics

## Patient Survival Prediction for Hospital Admissions

### Team Members:
- Yasmin Hashem Niazy 4200014
- Sohad Hossam ELdin 1190019
- Bassant Hisham 1190018
- Yasmin Zaki Bassiouny 1190352

## Table Of Contents:
1. [Idea](#idea)
2. [Business Value](#business-value)
3. [Technical Part](#technical-part)
   - [Data Preprocessing](#data-preprocessing)
   - [EDA and Data Visualization](#eda-and-data-visualization)
   - [Model Building and Predictions](#model-building-and-predictions)

## Idea:
We aim to develop and validate a prediction model for all-cause in-hospital mortality among admitted patients. Utilizing machine learning techniques, we will analyze a dataset containing various factors associated with hospitalizations to predict whether a patient will survive or not upon their admission.

## Business Value:
1. **Enhanced Patient Care:** Accurate prediction of patient survival upon admission allows for timely interventions, improving patient outcomes and satisfaction.
2. **Resource Efficiency:** Predictive models optimize resource allocation, including staffing and equipment, leading to cost savings and better resource utilization.
3. **Cost Reduction:** Early identification of high-risk patients reduces healthcare costs by preventing adverse events and shortening hospital stays.
4. **Data-Driven Decisions:** Machine learning enables data-driven decision-making, tailoring treatment plans based on individual patient risk profiles.
5. **Research and Innovation:** The project fosters research and innovation in healthcare analytics, advancing predictive modeling for improved patient outcomes.
6. **Competitive Advantage:** Organizations using predictive analytics gain a competitive edge by offering high-quality, data-driven healthcare services.

## Technical Part

### Data Preprocessing:
#### Data Cleaning:
- **Removing Missing Data:** Identification and removal of instances with missing values and unexpected data points.
- **Dealing with Outliers:** Addressing outliers to prevent them from skewing the analysis.
- **Data Normalization/Standardization:** Pending implementation.
- **Transforming Features to Categorical:** Converting categorical features for compatibility with machine learning algorithms.
- **Visualizing the Data:** Utilizing various plots to gain insights into the distribution and relationships within the dataset.

#### Implementation:
- Implemented using PySpark for big data processing.
- Utilized parallel processing for efficient processing on large datasets.
- Custom functions `my_map` and `my_reduce` facilitated the map-reduce approach.

### EDA and Data Visualization
#### Introduction to Data Visualization:
- Data visualization plays a crucial role in uncovering insights and patterns within datasets.
- Transforming raw data into visual representations aids in understanding the underlying structure and relationships within the data.
#### Boxplots and Histograms:
- Powerful tools for visualizing the distribution of numerical variables.
- Histograms display the frequency distribution of data, while boxplots help observe outliers and analyze the range of values.
#### Pie Charts:
- Provide insights into the contents of the dataset and the distribution of data types.

### Model Building and Predictions:
#### my_map Function:
- Applies a given function to each element in an iterable in parallel using threads.
#### map_func Function:
- Represents the mapping step of parallel processing, preprocessing data, training classifiers, and evaluating performance.
#### my_reduce Function:
- Aggregates results obtained from the mapping step, combining results from different threads.
#### reduce_func Function:
- Represents the reduction step of parallel processing, combining results obtained from individual threads.
#### Classifiers and Dataset Partitioning:
- Defined several classifiers along with their configurations.
- Partitioned the dataset into chunks for parallel processing.
#### Evaluation and Visualization:
- Calculated performance metrics for each classifier.
- Visualized performance metrics using confusion matrices and bar charts for comparison.

## Difference in Resulted Metrics:
- Visualized the difference in accuracy, recall, and F1 score from all six ML models.

