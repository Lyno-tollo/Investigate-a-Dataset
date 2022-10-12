# Investigate-a-Dataset

# Project: Data Wrangling


## Introduction

Generally, any good Data Analyst should be able to gather information from various sources,assess any problems in the data and resolve any quality and tidiness issues. Quality and tidiness in this aspect refers to the content and structural issues respectively.
In Udacity's Data Analyst Nanodegree program that i enrolled in, i got introduced to various data wrangling methods, analysis and visualizations. In one of the data wrangling projects, i managed to collect,assess,clean,analyze and visualize the data. The dataset i used in this project was WeRateDogs from twitter where dogs are rated based on humorous tweets. The main objective of this project was data wrangling. Data wrangling is the process of collecting,assessing and cleaning data into a valid format for futher analysis. Here, i used various python libraries and functions.
### Gathering Data:
Three datasets were gathered using different methods in this project:

- **Twitter Archive Enhanced File**:
This dataset was downloaded manually and read into a dataframe before further actions on the data were taken. The data contained tweets upto August 2017.
- **Image Prediction File**:
This dataset contained images from tweets which predicted the names and breeds of dogs using these images through a neural network mechanism. This dataset was downloaded programmatically using **Requests**, one of pythons libraries.
- **JSON File**:
This dataset was gatherered using the Twitter API for each tweet's JSON data using tweepy, one of twitter's libraries. This data was saved and later read line by line.

### Assessing Data
Both visual and programatic assessments were employed in this stage. The main aim was to identify any quality and tidiness issues in the three dataframes.
- **Quality**: The issues in this category are issues regarding the content of the data and have four dimensions of Completeness, Accurscy, Validity and Consistency.
- **Tidiness**: The issues in this category relate to the structure of the data for instance, each variable forms a column and each observation forms a row.

Visual assessment helped me in identifying accuracy and consistency issues.
Programmatic assessment was the source of most quality issues such as incorrect datatypes, duplicates and missing data.

### Cleaning
This means dealing with issues identified in assessments in order to end up with clean data that can be analyzed. This could mean correcting,removing and replacing the data to fix issues identified,or ensuring each variable forms a column and each observation is a row.
During my claning, i used the provided cleaning best practice of **Define, Code  and Test**

### Storing
Finally, after cleaning my datasets, i merged the three to form a master dataset on which analysis was to be performed on.

### Analyzing
I perfomed anlaysis on the cleaned datasets and got insights which i used in  creation of visualizations.
- **Most Popular Dog**:
The most popular dogs were Alfie,Walter and Winnie.
- **Source of tweets**
The top source of tweets was Iphone with 90 per cent.

### Conclusion
Several other insights can be drwan from this dataset apart from what i have analyzed. The requirements to pass this project was to write two reports on my data wrangling efforts and analysis where the analysis report was more of like a blog. I had fun doing this project and i thank you for reading.
