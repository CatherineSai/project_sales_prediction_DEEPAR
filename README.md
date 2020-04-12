# Sales_prediction_DEEPAR


What? 
Timeseries, regression project.


Goal: 
Predicting the sales (=target) for drug stores.


Additional Info: 
- the data is from a "Rossmann"-store Kaggle competition
- data contains multiple stores (cat = 0-1114)
- data contains multiple to the target related features (which were used as input for the prediction)  
- this project applies the AWS Sagemakers DeepAr Algorithm


Framework:

This Project was done along the CRISP-DM framework. The 7 Steps have been split uo as follwos:

1.	Business Understanding

The GitHub includes a "Proposal" with an overview of this projects approach. In this case it is not so much business understanding but really more project setup. This document also includes a more detailed workflow breakdown.  

2.	Data Understanding 
3.	Data Preparation
4.	Feature Engineering

Steps 2 - 4 are mainly done in the notebook "Data_Preprocesing_Step_2-4"

5.	Modelling
6.	Evaluation
7.	Deploy & Document

Steps 5-7 are done in the notebook “Benchmark_Model_Step_5-7” for the benchmark model (Simple Exponential Smoothing) and in the notebook “DeepAR_Model_Step_5-7” for the Amazon Sagemaker DeepAR model.

Step 7 is mainly done in the “Report” document, although the notebooks include brief comments and evaluations for the steps as well. 
