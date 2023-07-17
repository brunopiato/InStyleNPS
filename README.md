# HackDays Comunidade DS - 5th Edition

**Date:** July the 15th and 16th of 2023

**Team:** 
- Bruno Piato, 
- Caio Slowik, 
- Juliani Chagas, 
- Kaique Faustino 
- Mattheus Gomes

<!-- TOC -->

- [HackDays Comunidade DS - 5th Edition](#hackdays-comunidade-ds---5th-edition)
- [1. The Businness Problem](#1-the-businness-problem)
- [2. The approach](#2-the-approach)

<!-- /TOC -->

# 1. The Businness Problem
The InStyle Company is a big fashion company based in the US. They are going through some customers sastisfaction issues, probably due to their expansion process. One of the biggest challenges of growing the income and revenue of a brand or store is to maintain the product's quality, the sales service and the customer's experience in high standards.

As the company expands reaching more and more clients, the internal sales processes begin to face issues and problems. Since the product's conception all the way to the payment services play an important role to the satisfaction level of the customers.

The product development team start to find difficult to determine the needs and desires of the majority of the clients. The marketing team face challenges to determine the ideal client profile. The e-commerce team suffers with high and intense volumes of webpage visits and buy attempts, causing system wreckage and site problems, making it offline for hours, which impacts enormously the income and revenue. Besides all these problems, the customers begin to complain about different aspects of the experience of purchasing from the brand. 

To solve this problem and mitigate its effects an interdisciplinary team is called to the 'War Room', where professionals from the product development area, the marketing area, the e-commerce area and the data analytics area are gathered to brainstorm, discuss and find a solution to deal with the issues the company is facing and improve the satisfaction levels of the customers.

One of the main strategies to deal with this challenge is to identify different aspects of the clients satisfaction index through a Net Promoter Score (NPS), a metric to assess the customers' satisfaction index concercing different aspects of the businness. This is a very important step towards this challenge solution because it provides insights to improve the customers service. 

With the NPS results in hands the data science and analytics team is designated to develop and train a machine learning algorithm to classify new customers as they answer the NPS as "Satisfied" and "Neutral/Unsatisfied" so the marketing team can reach for unsatisfied customers, gather information about the reasons they are not satisfied with the company and improve the company's services. 

---
# 2. The approach

To approach and solve this problem we used the CRISP-DS method. It consists of a cyclic set of steps, biginning with the comprehension of the question and the businness characteristics. After that we gather the data necessary to accomplish the goal we planned. 

With the dataset in hands we began the data cleaning and wrangling phase, which consisted of dealing with missing values, duplicated rows and outliers. An Exploratory Data Analysis was conducted to create and assess more than twenty different hypothesis so we could get a better understanding of the businness problem and the characteristics of the dataset.

A step of data engineering was conducted to derive some new features from the features we already had in the dataset and prepare it to be modelled. We used different kinds of data scaling and transformation to get the data as ready as possible for the machine learning algorithms we decided to test.

We tested the performance of four different kinds of supervisioned-learning classification algorithms: Random Forest Classifiers, XGBoost Classifiers, LightGBM Classifier and CatBoost Classifier. To compare the performance of the algorithms we used the precision metric subsetting the dataset to keep 80% of it to train the models and 20% to test its predictions.

The LightGBM Classifier was the best performing algorithms among the ones we tested and so was chosen to be used further in the hyperparameter fine-tuning to reach for the best possible performance.

---


