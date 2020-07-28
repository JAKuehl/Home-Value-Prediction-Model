# Project 2 - Ames Housing Data
---


## Problem Statement
---
Use past home sale data to predict what features of a home do the best to predict resale value so real estate agents can best advise their clients what repairs/upgrades to focus their efforts on.

## Executive Summary
---
While there are many improvements a home owner can focus his or her time and money on, there are some that add more value to a home than others.  This project will show that focusing on quality over condition generally adds more to value to the home with particular emphasis on the kitchen.

## Findings
---
For this project, I used linear regression on 4 years of home sale data in Ames, Iowa in order to predict the feature improvements that would would provide the most boost to the sale price of a home.  After building four models with varying levels of prediction power these are the features that displayed the most impact on sale price.

### Model 1
**Coefficients**

overall_qual	15,380    
total_sq_ft	    52.1502	  
exter_qual	   -11,720	  
garage_area	    74.4705	  
totrooms	   -4,144.8241	  
Intercept      181,099.03  


### Model 2
**Coefficients**

overall_qual	    9,159	
mas_vnr_area	    43.3941	  
total_bsmt_sf	   -35.27	  
full_bath	       -9,903	  
totrms_abvgrd	   -7,518  
total_sq_ft	        68.56  	
garage_area	        43.03   
total_bath	        6,449	 
foundation_pconc	17,760	  
bsmt_qual_ex	    60,300	  
Intercept           181,131.77   

### Model 3
**Coefficients**    

This output had 18 variables, please refer to 02_Model_Benchmarks_and_Tuning.ipynb for the figures.


### Model 4
**Coefficients**

overall_qual	35,670	  
overall_cond	-3,819.18	  
kitchen_qual	24,280	  
functional	-12,920       
Intercept        181,131.77

**Please note:**  A detailed analysis of each model and its coefficients can be found in 02_Model_Benchmarks_and_Tuning.ipynb 

## Project Organizaiton
---
```
project-2
|__ code
|   |__ 01_EDA_and_Cleaning.ipynb   
|   |__ 02_Model_Benchmarks_and_Tuning.ipynb    
|__ data
|   |__ train.csv
|   |__ test.csv
|   |__ ames_Clean.csv
|   |__ test_Clean.csv
|__ presentation.pdf
|__ README.md
```

