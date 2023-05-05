# Data science project: British Airways customer satisfaction analysis and customer buying prediction (classification problem) (UNFINISHED)
Data science project as part of the British Airways data science virtual programme, where it is required to analyse customer satisfaction and build predictive models.

This is a **machine learning project**, where the main goal is to explore the data sources, check hypotheses and find out new patterns and insights relevant for the business , as well as developing machine learning models.

The main topics covered in this project are:

- Web scraping
- Data visualisation
- Classification machine learning models

## Context
British Airways requires to analyse customer satisfaction with their flights experience in order to know how they can improve their service. Moreover, it is required to build a machine learning model to predict customer behaviour towards booking flights with them.

<p align="center">
  <img width="480" height="270" src="https://github.com/luis-cj/data-science-british-airways/blob/main/images/airplane-gif.gif">
</p>


## Methodology

### 1. Objective
Analyse the customer satisfaction by collecting data from a third-part customer review provider and gain insights toavailable data to find out what is causing the problem in the power plants and conclude if it is necessary to send a technical team to fix the problem in site.

Before proceeding with the other points, it is important to know the basics of solar power production. 

### 2. Levers (action variables)
It is necessary to have some knowledge about how the energy is generated in a solar power plant. The data science team has been informed by the technical team on how the process works. 

With that, the levers (variables that affect the business objective, which in this case is generating AC power) are the following:

- **Irradiance**: the greater the irradiance the more DC power can be generated. But there is a limit since at very high panel temperatures the generation capacity is decreased.
- **Panel status**: it is important to have clean modules so they can perform at their full capacity.
- **Inverters' performance**: the process of transforming DC into AC is never 100% efficient. But the closer to 100% the better.
- **Sensors**: if sensors do not work correctly then it is not possible to detect potential plant failures.

### 3. KPIs
- Irradiance: is measured as the rate of solar energy hitting a surface per squared meter [W/m<sup>2</sup>].
- Ambient temperature and module temperature: measured by the sensors [ºC].
- DC power: power measured in direct current from the panels to the inverters [kW].
- AC power: power measured in alternate current from the inverters to the grid [kW].
- Inverters' efficiency: ratio of the AC power delivered to the grid to the DC power generated by the PV panels [%].

### 4. Entities and data
The relevant entities we can retrieve data from in order to accomplish our objective are the following:

- Solar power plants: there are 2
- Inverters: there are many inverters in each plant
- Irradiance sensor: 1 for each plant
- Ambient temperature sensor: 1 for each plant
- Module temperature sensor: 1 for each plant

All the sensors retrieve data every 15 minutes, and the total data set comprises 34 days.

### 5. Seed questions
These are the first questions we need to start finding relevant insights. Different questions apply to each lever.

About irradiance:

- Is there enough irradiance every day?
- Is it similar for both power plants?


### 6. Analysis and insights
All the analysis is carried out in the following Jupyter Notebooks (Python):


### 7. Communication
For this project a report was generated in the format of a PowerPoint presentation, communicating all the analysis and found insights.
The report can be checked in the following file:


## BONUS: Lessons learnt


