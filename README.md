# WorldQuantUniversity-DataScience-Module II
As part of the WQU DataScience Module, we were assigned a miniproject to predict which nursing home providers maybe fined and for how much. 


## Introduction

A federal agency, Centers for Medicare and Medicaid Services (CMS), imposes regulations on nursing homes. However, nursing homes are inspected by state agencies for compliance with regulations, and fines for violations can vary widely between states.
Nursing homes vary greatly in their business characteristics. Some are owned by the government or non-profits while others are run for profit. Some house a few dozen residents while others house hundreds. Some are located within hospitals and may work with more vulnerable populations. We will try to predict which facilities are fined based on their business characteristics.

Objective I: Prediction of whether the facility is fined or not/Classification

Objective II: Prediction of fine amounts/Regression

Objective III: Prediction of Survey Scores

Surveys reveal safety and health deficiencies at nursing homes that may indicate risk for incidents (and penalties). CMS routinely makes surveys of nursing homes. 
I built a model that combines the business_features of each facility with its cycle 1 survey results, as well as the time between the cycle 1 and cycle 2 survey to predict the cycle 2 total score.
