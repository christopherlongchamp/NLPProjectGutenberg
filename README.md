## NLP Project Gutenberg

#### This Final Project is for DS 5001 Exploratory Text Analysis taught by Professor Alvarado. 

## Purpose of Project

#### The purpose of this project is to compare and contrast three early 1900s authors. These authors were F. Scott Fitzgerald, Ernest Heminway, and Virginia Woolf. 

## Proposed Analysis

#### The Corpus that will be used is a corpus of 13 texts from the three authors. The author with the most amount of texts in the corpus is Virginia Woolf. She has 6 texts in the corpus, F. Scott Fitzgerald has 4 texts, and Ernest Heminway has 3 texts. The proposed analysis will contain topic modeling for the corpus, a word embedding analysis of the corpus, and a sentiment analysis of the corpus.  

## The Data Pipeline/How to Get Started

#### The data pipeline begins with forking this Github Repository and getting both the Python Notebook and the folder with the text files. Once the files are forked onto your computer, you will have to adjust the file path of the data home, from `data_home = "../DS5001"` to `data_home = "../whateverfolderfilesarein"`. 

## What is in the Repository

1. `final-set`, this is a folder that contains the original text files of the novels from Project Gutenburg, changed so that they can be run through the text parser. 

2. `data`, this is a folder that contains all the data files used in the analysis. All of the tables are made from these or are these. 

3. `FINAL_REPORT.ipynb`, this is the file that contains the analysis with explanation. 

4. `Final_Project.ipynb`, this is the file where the analysis and the code for the analysis is written. 

5. `salex_nrc.csv`, this is the CSV file where the emotions and sentiments for the Sentiment Analysis section of the code come from. 

6. `textparser.py`, this is the Python file where the TextParser function comes from in order to get the original text files to a dataframe. 
