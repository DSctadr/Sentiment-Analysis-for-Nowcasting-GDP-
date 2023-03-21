# Sentiment Analysis for Gross Domestic Product (GDP)

## Objectives and Goal
It is crucial to consider how sentiment analysis and data extraction from economic news sources enables us to gain crucial information into Malaysia’s economic status. Thus, this paper wants *to investigate textual data from local news articles in improving nowcasting models.*

## Dataset Information
This project consists of two (2) types of data :

• **Structured Data**

The study utilises a mixed-frequency dataset for nowcasting    GDP, which comprises 46 variables covering the period from January 2015 to December 2022. The data is obtained from three sources, the Department of Statistics Malaysia (DOSM), Central Bank of Malaysia (BNM) and other online sources (eg: Bursa Malaysia).

• **Unstructured Data**

In order to develop sentiment indicators for a significant time period, this study extracted economic news generated from January 1st, 2015 to December 31st, 2022. The Malaysia online news corpus was extracted, capturing the article's title, description and date for use in building the sentiment indicators. 

The processed dataset that encompasses 46 variables employs three distinct datasets as shown below:

Full data : (Q1,2015-Q3,2022)

During COVID-19, excluding vaccination rollout : (Q1,2020-Q1, 2021)

During COVID-19, including vaccination rollout : (Q1,2021-Q3, 2022)


## Requirements
There are some general library requirements for the project as follows:

• numpy

• VADER(Natural Language Toolkit)

• googletrans

• Spark(Natural Language Processing)

• pandas

• langdetect

## Project Steps

1. Download the "Data" folder since it contains the dataset for the project.

2. Download the "Code" folder since it contains the whole coding for this project.

3. Open "GDP Sentiment Analysis.ipynb" in python IDE, change the directory for loading dataset and run step 1-9.

4. Open "Spark_Sentiment.ipynb" in GoogleColab and start executing step 1-10.

5. Open "GDP Sentiment Analysis.ipynb" in python IDE and start executing step 10 until the end.

6. Open "Spark_test.ipynb" in python IDE and start executing step 1-6.

7. Open "Visualization(VADER & Spark).ipynb in python IDE and start executing step 1 to 11.

**Note:** Every result file produced by the coding need to store in one Code folder in order to make 
          process of loading directory task easier.



## Methodology Summary
![image](https://user-images.githubusercontent.com/106640534/225506086-9123775a-406e-4e7c-b1da-3b8f3f90dd80.png)


