# spark-project
An end-to-end sentiment analysis project with Apache Spark and Spark NLP
![Spark Logo](https://upload.wikimedia.org/wikipedia/commons/f/f3/Apache_Spark_logo.svg)

# Project Description
This is the final project of the Big Data course. The purpose of this project is to develop a sentiment analysis model with a Multinomial Naive Bayes algorithm 
that could predict youtube comments' sentiment (Negative/Positive) regarding iPhone 15 products. The model itself was trained on iPhone 14 Pro datasets (also coming from youtube comments) that were labeled
using a pre-trained hugging-face model (cardiffnlp/twitter-roberta-base-sentiment-latest). Youtube comments were collected using Youtube Data API. 

**This project implements : 
**✅ Custom Spark Transformers
✅ Spark ML Pipelines
✅ Spark ML Evaluators & Models
✅ Spark NLP Annotators
✅ Spark NLP Pre-trained Pipelines
✅ MongoDB connector for Spark 
