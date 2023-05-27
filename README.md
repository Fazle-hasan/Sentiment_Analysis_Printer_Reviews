# Sentiment Analysis of HP Printer Reviews

### Introduction
This project focuses on performing sentiment analysis on HP printer reviews obtained from Amazon's website. The analysis aims to extract sentiments expressed in the reviews to gain insights into customer opinions and satisfaction levels. Two different models, VADER (from NLTK) and the RoBERTa pretrained model (from Hugging Face), are employed for sentiment analysis. The results of the sentiment analysis are saved in a CSV file for further analysis and interpretation.

### Requirements
To successfully run this project, ensure you have the following dependencies installed:
1. Python 3.7 or above
2. NLTK library
3. Transformers library (from Hugging Face)
4. Pandas library

You can install the necessary dependencies using the following command:

pip install nltk transformers pandas

### File Description

Web_Scraping_Printer_Reviews.ipynb: This script is responsible for scraping the HP printer reviews from Amazon's website. It utilizes web scraping techniques to extract the review data and saves it in a text file. If you want to change the product just change the link present in the script.

HP_Printer_Sentiment_Analysis.ipynb: This script performs sentiment analysis on the scraped reviews using both the VADER model and the RoBERTa pretrained model. The reviews are processed, and sentiment scores and labels are assigned. The results are saved in a CSV file.

All_reviews.csv: This csv file contains the raw HP printers reviews obtained from Amazon's website.

All_reviews_Reviews.csv: This CSV file stores the sentiment analysis results. Each row represents a review, including the review text, Customer name and sentiment label for both model inform of complaint, suggestion or appreciation.
.

