# Data science project: British Airways experience (UNFINISHED)
Data science project as part of the British Airways data science virtual programme, where it is required to analyse customer satisfaction and build predictive models.

This is a virtual experience programme that includes differents tasks, such a exploring data sources and finding out new patterns and insights relevant for the business, as well as developing machine learning models.

The main topics covered in this project are:

- Web scraping
- Data visualisation
- Natural Language Processing (NLP)
- Classification machine learning models
- Feature importance


## Context
British Airways requires to analyse customer satisfaction with their flights experience in order to know how they can improve their service. Moreover, it is required to build a machine learning model to predict customer behaviour towards booking flights with them.

<p align="center">
  <img width="480" height="270" src="https://github.com/luis-cj/data-science-british-airways/blob/main/images/airplane-gif.gif">
</p>


## Task 1: Gain customer insights (discovery project)

### 1. Objective
Analyse the customer satisfaction by collecting data from a third-party customer review provider and gain insights to improve service quality.


### 2. Levers (action variables)
Customers book flights with British Airways and after their trip some of them post their review of the airline's service regarding general quality, punctuality, in-flight service, comfort and some other metrics. They also provide a rating number ranging from 0 to 10 (the higher the better).

With that, the lever (variable that affects the business objective, which in this case is customer satisfaction) is the following:

- **Airline reviews**: provides customer satisfaction information from the airline.

There are more types of reviews (e.g. seat reviews, lounge reviews) but for this project only airline reviews are required to be analysed.

### 3. KPIs
- Review: the reviews themselves provide all the information about what can be improved to increase customer satisfaction.
- Rating: value ranging from 0 to 10 indicating the overall satisfaction of the customer.

### 4. Entities and data
The relevant entity we can retrieve data from in order to accomplish our objective is the following:

- Customer review service provider: about 10 years of customer reviews from the [Skytrax](https://www.airlinequality.com/airline-reviews/british-airways) website. 

### 5. Seed questions
These are the first questions we need to start finding relevant insights. Different questions apply to each lever. In this case

About airline reviews:

- What is the mean rating for the airline during the last 3 years?
- Is there any yearly trend in ratings?
- What are the main topics customers complain about?

### 6. Analysis and insights
All the analysis is carried out in the following Jupyter Notebooks (Python):


### 7. Communication
For this project a report was generated in the format of a PowerPoint presentation. It was a requirement to sum up all the insights in a single slide.
The report can be checked in the following file:


### BONUS: Lessons learnt

- **Customer reviews are biased**: customers that post reviews usually do it to complain. This fact leads to biased reviews towards lower customer satisfaction. Ideally, all type of customers (happy and unhappy) should provide reviews in order to avoid that bias, and that's usually not possible in real business environments.

## Task 2: Predicting customer buying behaviour (binary classification machine learning project)

### 1. Objective
Build a predictive model to understand the factors that influence buying behaviour of customers.

### 2. Data collection
Data is provided by British Airways and it contains information about every transaction taking place at their website, where the target variable is the customer booking a flight or not (0 or 1).

The data file is a .csv file.

### 3. Data cleaning
This part involves checking data types and general data quality. The main steps in this phase are cleaning and processing data from missing values and outliers that the original dataset may contain.

Data cleaning can be checked in the following Jupyter Notebook:


### 4. Exploratory Data Analysis (EDA)
A statistical and graphical analysis of the data allows further understanding of the data and the business problem. 

EDA can be checked in the following Jupyter Notebook:


### 5. Data transformation (Feature Engineering)
All variables that are going to be used in the machine learning model need to be prepared for that task. Here, any new variables relevant for the problem might be created. Also, a first feature selection is carried out. Finally,


### 6. Model selection and training

### 7. Model evaluation

### 8. Model deployment

### 9. Communication
For this project a report was generated in the format of a PowerPoint presentation. It was a requirement to sum up all the insights in a single slide.
The report can be checked in the following file:

### BONUS: Lessons learnt
