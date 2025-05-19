# Healthcare Insurance Cost Analysis

This is a study on how personal attributes and geographic factors influence insurance charges based on a healthcare insurance dataset extracted from Kaggle.

# ![logo](https://storage.googleapis.com/kaggle-datasets-images/3852935/6678394/92af7560770ed0fc7cfdb3e96f33f51e/dataset-cover.jpg?t=2023-10-12-20-28-56)


## Dataset Content
The dataset contains information on the relationship between personal attributes (age, gender, BMI, family size, smoking habits) and geographic factors and their impact on medical insurance charges.  This can be downloaded from the link below.

https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance


## Business Requirements
1) Display basic statistics, including average insurance charges by age, gender and region.
2) Visualise correlations between different attributes and insurance charges.
3) Geographic Analysis: Visualise the impact of geographic regions on insurance charges.


## Hypothesis and how to validate?
Insurance charge is expected to:

1) increase with age
2) be higher for smoker
3) be lower for female
4) vary with BMI

Family size may also be a contributing factor to insurance charges.

We will examine and validate through analyses and visualisations that are set out under the business requirements.


## Project Plan
Project is managed over 6 stages, supported by GitHub project board (https://github.com/users/8osco/projects/6/views/1):

1) Project setup with new GitHub repo for storage and version control, VScode as IDE, and access to Kaggle for dataset
2) Data extract and familiarisation
3) Data cleaning and preparation
4) Data quality check
5) Data analysis and visualisation
6) README documentation


## The rationale to map the business requirements to the Data Visualisations
Insurance charges are set based on a number of factors.  The relationships between charges and these factors are best examined and visualised in charts.  Interactive features are invaluable for comparison between factors and combination of factors, when they are carefully designed.  They can also help identify outliers or areas for further examinations more easily.

The relationship between charges and age, for example, would be best represented in a chart, given the value range of both variables.  Generation of subplots to further break down the relationship by region, gender, smoker status, etc provide greater information to help understand the inter-relationships amongst the variables.


## Analysis techniques used
My analysis begins with data familiarisation and an attempt to understand the data distribution.

This provides some indication on the materiality of different factors and limitations of the analysis (e.g. due to limited data points available).

This helps prioritise and feed into the design of the visualisations.

Interactive features are particularly useful for this project, for providing and comparing between visualisations to help observe relationships and patterns.  Code Institute learning materials, tutoring and AI tools have been helpful in every stage from visual designs, code optimisation, visualisation enhancements.


## Ethical considerations
The data has already been anonymised at source.

The results of the analysis may pose potential ethical questions, for example if charges are noticeably higher in a region a consistent differential between male and female charges.

## Unfixed Bugs
I was exploring the use of dotted lines in the plots to help make clearer distinctions between lines.  Whilst the AI tool offer some suggestions, it was not successfully implemented.  This is to be further experimented.

The image added on top of this README file does not seem to load on GitHub, although it can be seen here in the VScode preview.  I would like to follow up to understand.  I have tried changing the image size with this code also: "<img src="dataset-cover.jpg" alt="Description" width="400" height="100"/>", but it didn't work.

## Development Roadmap
There are many routes from both coding and data structuring perspective to arrive at the some output.  I would like to explore the most efficient and effective way to do this, through further testing and experimenting, and getting a better handle on the strengths and limitations of different packages.


## Main Data Analysis Libraries
NumPy and Pandas for data interrogation and manuipulation.
Seaborn and Plotly, supported by Matplotlib, for the visualisations.


## Credits
Code Institute course materials, SME, data coach, PDBA sessions.
ChatGPT for code clarification and creation.
The image at the top of this README file was sourced from Kaggle.


## Acknowledgements
A special thanks to Project Group 2, Apr 2025 data analytics cohort and coaches. The support received and discussions have been invaluable.