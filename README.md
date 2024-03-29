# Using sentiment analysis on reddit data to analyse crypto markets
---
## **Project description:**


Getting data from Reddit using Praw and Psaw libraries. We gathered time, title, authors, flair, score and number of comments and wrote it in CSV file. 
With the help of flair library for sentiment analysis we computed score of each title and text and grouped them into one(average).
Using Binance API we gathered Bitcoin prices for 6 months back and made a seperate file for price change in "%".
The CSV files were then used to do some basic analysis using **matplotlib**.

## **What we have done:**

- Getting data from Reddit using **Praw** and **Psaw** libraries
- We gathered time, title, authors, flair, score, number of comments
- By using Binance API we gathered Bitcoin prices from October 2021
- Sentiment analysis using [flair framework for state-of-the-art NLP ](https://github.com/flairNLP/flair)
- Analysis and visualisation using matplotlib

## Which authors influenced/were rigth most of the time

![image info](Figure1.png)

## Authors that were right relative to coefficient

![image info](Figure2.png)

## **Python script** 

![image info](Figure4.png)

## **Accuracy over multiple data samples** 

![image info](Figure_3.png)

## **Link to video description of the project** 

* <https://youtu.be/aVGUlsw4Vf0>
