# Covid-19 Prediction of NewCases and TestKits Requirements using SARIMA
This repository contains source code for Time series prediction of COVID19 data.

## Steps for Data Cleaning 
Find the whole [Flow chart](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/FlowChart/Data_Preparation-Flowchart.html) and [Psudo Code](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/PseudoCode/PseudoCode_PreProcessing.pdf) for data claaning 

## Objective 1
### Considering current trend of COVID-19 cases in Malaysia, I want to determine if Malaysia could achieve 14 days average of below 100 cases/day within the next 3 months(Cumulative count of new cases over 14 consecutive days should be less than 1400).
Find the whole [Flow chart](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/FlowChart/Objective_1-New_Cases_Prediction-Flowchart.html) and [Psudo Code](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/PseudoCode/PseudoCode_Objective1.pdf) for Objective 1 

## Objective 2
### Considering current trend of COVID-19 tests in Malaysia, I want to determine the number of COVID-19 test kits that would be required each week in Malaysia, over next 3 months
Find the whole [Flow chart](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/FlowChart/Objective_2-Test_Kits_Prediction-Flowchart.html) and [Psudo Code](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/PseudoCode/PseudoCode_Objective2.pdf) for Objective 2 

# Steps

## Pre Processing

### Before Pre-Processing & After Pre-Processing
![1](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/UnProcessed%20Data%20Malaysia.png) 
![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/Processed%20Data%20Malaysia.png) 

## Daily New-Cases

### Data Visulization of current data
Current Data ![1](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Cases_Initial.png) 
Decomposition ![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Cases_Decomposition.png) 
Corelation ![3](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Cases_AutoCorelation.png) 
Partial Corelation ![4](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Cases_PartialAutoCorelation.png) 
### Data Visulization of Model and Prdicted data
Test Train Model ![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Cases_TestTrain.png) 
Model ![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Cases_Model.jpg) 
Result Analysis![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Cases_result_diognostics.png) 
Predicted Values ![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Cases_FuturePredict.png) 

## Daily New-Tests

### Data Visulization of current data
Current Data ![1](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Tests_Initial.png) 
Decomposition ![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Tests_Decomposition.png) 
Corelation ![3](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Tests_AutoCorelation.png) 
Partial Corelation ![4](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Tests_PartialAutoCorelation.png) 
### Data Visulization of Model and Prdicted data
Test Train Model ![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Tests_TestTrain.png) 
Model ![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Tests_Model.jpg) 
Result Analysis![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Tests_result_diognostics.png) 
Predicted Values ![2](https://github.com/Sai2000-20/Covid_Cases_TestKits_TimeSeriesPrediction-SARIMA/blob/main/images/New-Tests_FuturePredict.png) 

