# Task 2 - Exploratory Data Analysis (EDA) Report

## Overview

This repository contains an Exploratory Data Analysis (EDA) report for a given dataset. The main goal of this report is to uncover insights and patterns in the data using various techniques and visualizations. The dataset consists of stories data, and the analysis focuses on extracting meaningful information from it.

## Dataset

The original dataset was separated into multiple CSV files, and the first step of the analysis involved combining these files into one consolidated CSV file.

## Insights Obtained

### Insight 1: Category Counts

To gain an understanding of the distribution of examples across different categories, I performed a category count analysis. Using matplotlib and pandas, I visualized the number of examples in each category to get an overview of the data's class distribution.

### Insight 2: Top Frequent n-grams

I conducted a top frequent n-grams analysis to identify the most common n-grams in the text data. During this analysis, I observed some special characters that interfered with the results by being considered as separate words. To address this issue, I created a cell to remove specific special characters and ensure accurate n-gram extraction.

### Insight 3: Word and Letter Counts in Examples

To understand the length of the examples in terms of words and letters, I used the nltk library. For word count, I applied the word_tokenize function, and for letter count, I utilized ngrams from nltk. Both counts were obtained using a small for loop and len() to calculate the total number of words and letters in each example.

### Insight 4: Top Frequent n-grams Generally

Using nltk's word_tokenize function, I analyzed the text data to extract the most common n-grams (where n is a chosen value). This analysis provides valuable insights into the frequently occurring word sequences in the entire dataset.

### Insight 5: Top Frequent n-grams per Class

Similar to the previous insight, I used nltk's word_tokenize function to identify the most common n-grams within each class (where n is a chosen value). This analysis allows us to explore the specific word sequences that characterize each category.

## Conclusion

The Exploratory Data Analysis conducted in this project has provided valuable insights into the given dataset. The analysis covers category counts, top frequent n-grams, word and letter counts in examples, and more. The visualizations and findings in this report can be used to better understand the data and support further research and decision-making processes.

## PDF Report

You can find the detailed Exploratory Data Analysis (EDA) report in [this PDF file](EDA Report.pdf).

![PDF Report](report_cover.png)
