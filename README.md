**Fundamentals of Data Analysis 2020 Project Submission**

**GMIT Higher Diploma in Data Analytics**

**Submitted by Fiona Lee - 8 January 2021**

**Introduction**

This project uses 'Simple Linear Regression' to predict power output of wind turbines based on a given wind speed using the 'Wind-Power' dataset.

![alt text](https://www.munichre.com/content/dam/assets/munichre/images/royalty-free-ppt-only/200416688-001_22.jpg/_jcr_content/renditions/original.image_file.5079.2857.0,329,5079,3186.file/200416688-001_22.jpg)

*Source: https://www.munichre.com/content/dam/assets/munichre/images/royalty-free-ppt-only/200416688-001_22.jpg/_jcr_content/renditions/original.image_file.5079.2857.0,329,5079,3186.file/200416688-001_22.jpg*

**Qualities and attributes of the Wind-Power dataset**

The original dataset contained 500 samples (rows), and 2 variables (columns) namely: 'speed' and 'power'. 

The changes made to the original dataset are as follows:

- The 'speed' and 'power' headers were renamed as 'Speed_Mph' and 'Power_KWph'
- 15 samples were deemed either 'test' or 'exceptional samples' and were removed from the dataset.  
- Additional columns were added i.e 'Power:Speed','Classification','Cost' and 'Power_Prediction'  

**The Mean, Median, Standard Deviation, Min and Max Values for each variable are contained in the Final Project 2020.ipynb file**

*Repository Link: https://github.com/Fiona-600/Fundamentals-of-Data-Analytics-2020-Project/blob/main/Final%20Project%202020.ipynb*

**Purpose of the project**

The elements explored will be:

1.	'Simple Linear Regression' applied to the 'Wind-Power' data set 
2.	Explanation of the 'simple linear regression' and analysis of its accuracy
3.	Prediction of power output based on a given wind speed
4.	Use of other types of Regression to produce the same output as the 'Simple Linear Regression' approach

**Simple Linear Regression**

Simple linear regression is an approach for predicting a response using a single feature.  It is assumed that there are two variables, a feature (Speed_Mph) and a response (Power_KWph) that are linearly related. 

This method attempts to find a linear function that predicts the response value (in this case Power_KWph) as accurately as possible as a function of the feature or independent variable (Speed_Mph).

The line which best fits the scatter plot of the dataset is called 'regression line'.  This line is used to predict feature values i.e. in this case 'Power_KWph' which are not already present in dataset.

The equation of regression line is represented as:

h(x_i) = \beta _0 + \beta_1x_i

source: https://www.geeksforgeeks.org/linear-regression-python-implementation/





**Structure & Project Navigation**

The project will be stored in a GITHUB Repository at url: https://github.com/Fiona-600/Fundamentals-of-Data-Analytics-2020-Project

1.	The GITHUB repository contains:

    •	A ‘gitignore’ file containing any files or file types which should be ignored by the github repository  
    
    •	A python program file called ‘Final Project 2020.ipynb’ which contains:
 
          • Online and other research into simpple linear regression and other approaches
          •	High level review and summary of the data set
          •	Identification of trends and exceptional samples (outliers)      
          •	Visualisation of the data set and the relationship between the variables
          •	Prediction models using simple linear regression and sklearn approaches
    
    •	A ‘LICENSE’ file containing a copy of the MIT Licence

    •	A ‘README.md’ file which contains:

          •	Introduction to the dataset 
          •	Explanation of the 'simple linear regression' 
          •	Conclusions and findings        
          •	How to run the python code
          •	References used in completing the project

    •	Wind-Power.csv - Wind Speed/Power Dataset


**Required Programs**

	•	Anaconda Navigator 3 - https://www.anaconda.com/
	•	Jupyter Notebook - https://jupyter.org/install  
	•	Python version 3.8.3 - downloaded via Anaconda Navigator 3 to Windows 10 OS
	•	Cmder Console Emulator - https://cmder.net/
 	•	GitHub Repository Storage - https://github.com/
	•	Firefox Internet Explorer - https://www.mozilla.org/en-US/firefox/new/


**Opening and running the code in the Jupyter Notebook**

	•	Clone or download the 'FinalProject.ipynb' file from Github onto your local drive
	•	Open the Jupyter Notebook file in your browser using CMDER
	•	Use 'Restart and Run All' in the 'Kernel' tab in Jupyter Notebook to re-run the entire code
	•	Hold 'Shift' + 'Enter' to run/test code in individual code cells in a Jupyter Notebook


**Libraries and Modules**

    •	NumPy - ‘import numpy as np’
    •	Pandas – ‘import pandas as pd’   
    •	From Pandas import Dataframe’       
    •	Matplotlib - ‘import matplotlib.pyplot as plt’
    •	from sklearn.metrics import r2_score 
    •	from sklearn import linear_model  
    •	from sklearn.linear_model import LinearRegression  


**Author & Contributors**

Fiona Lee


**License**

This project is licensed under the MIT License - see the LICENSE.md file for details


**Acknowledgments**

Ian McLoughlin for all the helpful tips in completing this assignment


**References**

https://realpython.com/linear-regression-in-python/

https://towardsdatascience.com/linear-regression-detailed-view-ea73175f6e86

https://machinelearningmastery.com/a-gentle-introduction-to-scikit-learn-a-python-machine-learning-library/

https://datatofish.com/sort-pandas-dataframe/

https://www.kite.com/python/answers/how-to-print-an-entire-pandas-dataframe-in-python

https://www.codegrepper.com/code-examples/python/how+to+align+column+name+to+center+in+pandas+dataframe

https://www.dataquest.io/blog/settingwithcopywarning/

https://realpython.com/pandas-groupby/

https://github.com/ianmcloughlin/jupyter-teaching-notebooks/blob/master/simple-linear-regression.ipynb

https://www.geeksforgeeks.org/python-coefficient-of-determination-r2-score/

https://medium.com/towards-artificial-intelligence/calculating-simple-linear-regression-and-linear-best-fit-an-in-depth-tutorial-with-math-and-python-804a0cb23660#9a2b

https://colab.research.google.com/drive/1WRdDbFFykiLv16-Vv-ghsregmfdbwtRX?usp=sharing&pli=1#scrollTo=3kbMmi6JYeB4

https://www.shanelynn.ie/select-pandas-dataframe-rows-and-columns-using-iloc-loc-and-ix/

https://datatofish.com/random-rows-pandas-dataframe/

https://scikit-learn.org/stable/auto_examples/linear_model/plot_ols.html

https://contactsunny.medium.com/linear-regression-in-python-using-scikit-learn-f0f7b125a204

https://stackabuse.com/linear-regression-in-python-with-scikit-learn/

https://www.geeksforgeeks.org/linear-regression-python-implementation/