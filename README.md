# Applied_Statistics
This repository documents the coursework and project completed as part of the Applied Statistical Methods for Biomedical Informatics course. The course involved in-depth exploration of statistical methods and their applications in the field of biomedical informatics.
Below, we outline the key aspects and achievements of the course and the specific project conducted.

# Table of Contents
Course Overview
Project Overview
Key Learnings
Project Details
Usage
Contributing

# Course Overview
The Applied Statistical Methods for Biomedical Informatics course focused on advanced statistical techniques applied to healthcare and biomedical data. Key topics covered during the course include:

Handling Missing Data: Strategies to identify and interpret health data with missing values, ensuring robust analysis and decision-making.

Inferential Statistics: Techniques for inferring and justifying inferences from health data, with a specific focus on diseases and healthcare-related variables.

Phenotypic and Genotypic Data: Methods to correlate and analyze large sets of phenotypic and genotypic data, enabling insights into genetic factors associated with diseases.

Population Modeling: Understanding population dynamics, sampling strategies, and hypothesis testing tailored to specific diseases.

Data from Hospitals and Insurance: Designing and formulating sampling and hypothesis testing methodologies for hospital and insurance data, addressing the complexities of healthcare systems.

Statistical Analysis for Precision Medicine: Selecting and generating regression analysis and other statistical methods for precision medicine applications, providing personalized healthcare insights.

Project Presentation and Communication: Techniques for outlining and formulating paper presentations, ensuring effective communication of statistical findings.

Data Analytics in R: Developing and revising programs to perform data analytics on large, complex datasets using the R programming language.

# Project Overview
As a significant part of the course, a project titled "Predicting the RFFT Score from the PREVED dataset" was conducted. This project involved the following key steps:

Data Exploration: Initial data exploration and visualization in R Studio using ggplot and Plotly libraries. Techniques such as scatterplots and boxplots were employed to identify correlations and patterns within the dataset.

Regression Modeling: Building a multiple linear regression model to predict RFFT (Rey Auditory Verbal Learning Test) scores based on various independent variables, including Age, Education, Smoking, Statins, BMI, and FRS (Framingham Risk Score).

The project aimed to demonstrate proficiency in statistical analysis, data preprocessing, modeling, and interpretation of results within the context of biomedical informatics.

# Key Learnings
Throughout the course and the project, the following key learnings and skills were acquired:

Advanced Statistical Techniques: Gained a deep understanding of statistical methods tailored to healthcare and biomedical data.

Data Visualization: Developed skills in data visualization using R, enabling effective communication of findings.

Regression Analysis: Mastered regression analysis techniques for predicting outcomes based on multiple variables.

Data Preprocessing: Learned strategies for handling missing data and data cleaning to ensure accurate analysis.

Statistical Inference: Gained the ability to make informed inferences from health data, particularly related to diseases.

Communication: Enhanced skills in presenting and communicating statistical findings to a diverse audience.

# Project Details
Data Loading and Initial Exploration
The project began by loading the dataset, which was stored as a CSV file, into R using the read.csv function. Several R packages were installed and loaded to facilitate data analysis and visualization, including Hmisc, colorspace, tidyr, dplyr, ggpubr, ltm, and plotly.
The initial exploration of the data was performed using the describe function from the Hmisc package, which provided summary statistics and information about the dataset's variables.

Handling Missing Data
To address missing values in the dataset, various strategies were applied. The following key steps were taken:

Checking for missing values using the is.na function.
Calculating the total number and mean of missing values in the dataset.
Determining the number of missing values in each column.
Replacing null values in specific columns (Income, WaistCirc, BMI) with median values.
Inferential Statistics
Inferential statistics were employed to gain insights from the data. The following steps were taken:

Rows with missing values were removed from the dataset.
Pseudo-random sampling was conducted to create a representative sample from the complete data.
Data Visualization
Data visualization was an integral part of the analysis. Various plots and graphs were created using the ggplot2 package to visualize the distribution of data and identify potential patterns. Histograms, density plots, and QQ plots were used to assess the normality of continuous variables like Age and Income.

Non-Parametric Tests
Due to the non-normal distribution of the data, non-parametric tests were used for statistical analysis. The Kruskal-Wallis test was performed to assess the relationship between categorical variables (e.g., Age, Sex, Income, Marital status, Race) and the presence of metabolic syndrome.

Logistic Regression
Logistic regression models were constructed to predict the likelihood of metabolic syndrome based on individual variables (Age, Sex, Income, Marital status, Race). Accuracy, sensitivity, and precision metrics were used to evaluate the performance of each logistic regression model.

Correlation Analysis
Point biserial correlation tests were conducted to analyze the relationship between continuous variables (e.g., Age, Income) and the presence of metabolic syndrome.

Cross-Tabulation
Cross-tabulations were performed to examine the relationships between categorical variables (e.g., Sex, Marital status) and the presence of metabolic syndrome.

Conclusion
The project "Predicting the RFFT Score from the PREVED Dataset" showcased a comprehensive analysis of a biomedical dataset related to metabolic syndrome. Through the use of statistical techniques, data visualization, non-parametric tests, logistic regression, and correlation analysis, valuable insights were gained regarding the factors associated with metabolic syndrome.

This project demonstrates the application of advanced statistical methods to biomedical informatics, emphasizing the importance of data preprocessing, inferential statistics, and visualization in deriving meaningful conclusions from complex healthcare datasets.

# Contributing
Contributions to this repository are welcome. If you have improvements, additional analyses, or insights related to the course topics or project, please feel free to contribute by creating a pull request.
