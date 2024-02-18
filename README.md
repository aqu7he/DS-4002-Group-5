# DS-4002-Group-5

Code for various projects in DS 4002 Spring 2024. Group 5 consists of Andrea, Cato, and Charlie.

We analyzed posts from the Kansas City Chiefs subreddit to answer the question: Will the sentiment of tweets about the Kansas City Chiefs have changed a significant amount (a magnitude of greater than 0.05 sentiment score) after the first game Taylor Swift attended (September 24, 2023)? We hypothesize that there will be a significant increase in the sentiment score of the posts after the announcement that Taylor Swift is dating star player, Travis Kelce.

## Content 
README.md -- Serves as an orientation to everyone who comes to this repository, it should enable you to get their bearings. You are in the README.md file now.
LICENSE.md -- The terms under which they may use and cite your repository.
SCRIPTS folder -- Contains all the source code for the project.   
DATA folder -- Contains all of the data for this project.   
OUTPUT folder -- Contains all of the output generated by our project, e.g. figures, tables, etc.

- - - -

## Section 1: Software and platform section
To scrape data from Reddit, we used the Reddit Extractor package in R. For more detailed instructions, we used this [github](https://github.com/ivan-rivera/RedditExtractor "github"). After obtaining our dataset, we used the VADER sentiment analysis package in Python to conduct our analysis. 

The add-on packages we used in R are:
* library(ggplot2)
* library(tidyverse)
* library(wordcloud)
* library(RedditExtractoR)
* library(dplyr)
* library(stringr)

The add-on packages we used in Python are:
* !pip install vaderSentiment
* import vaderSentiment
* import pandas as pd
* import matplotlib.pyplot as plt
* from textblob import TextBlob
* import numpy as np
* import seaborn as sns
* from wordcloud import WordCloud
* from vaderSentiment.vaderSentiment import SentimentIntensityAnalyzer

The platform we used for our project was Mac.

## Section 2: Map of documentation
### What you will find in this repo:
* DATA folder:
  * chiefs_data.csv
  * one more file I still need to add
* SCRIPTS folder:
  * mi2_project_1_code.py
  * or tbd
* OUTPUT folder:
  * tbd
* LICENSE.md
* README.md

## Section 3: Instructions for reproducing results

## Resources:
[1] “Swift effect: Kelce jersey sales see 400% spike,” ESPN.com, Sep. 26, 2023. https://www.espn.com/nfl/story/_/id/38496220/taylor-swift-effect-travis-kelce-jersey-sales-spike-nearly-400

[2] Z. Keita, “Social Media Sentiment Analysis In Python With VADER — No Training Required!,” Medium, Mar. 01, 2022. https://towardsdatascience.com/social-media-sentiment-analysis-in-python-with-vader-no-training-required-4bc6a21e87b8

[3] I. Maintainer and Rivera, “Package ‘RedditExtractoR’ Type Package Title Reddit Data Extraction Toolkit,” 2023. Available: https://cran.r-project.org/web/packages/RedditExtractoR/RedditExtractoR.pdf
