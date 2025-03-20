# Presidential Inauguration Speeches: Unification or Polarization? 
By _Data Destroyers (Kelsey Matsik - leader, Karan Rawat, Emma Mills, Emily Macris)_



## Contents of Repository
This repository contains all the work for Project 2 of Prototyping which has the goal of working with time series data. Specifcally, the goal of the repository is to answer the question: 
_How have crime rates in Charlottesville changed over time, specifically with respect to the UVA academic calendar?_<br>




## Section 1 -- Software and Platform
Throughout this project we used Github, Jupyter Notebook, VS Code and Python. The packages we used were pandas, seaborn, matplotlib, scipy, numpy, requests, and bs4 (Beautiful Soup), Prophet, SARIMAX, Astral, Pytz 
All of these packages would have to be downloaded in order to run the notebooks. Both Windows and Mac were used to complete this project. 

## Section 2 -- Directory Map
ds4002_project1/<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── data/<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── Crime_Data.csv<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;└── cleaned_data.csv<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── scripts/<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── SARIMA_analysis.ipynb<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── VAR_analysis.ipynb<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── preprocessing_EDA.ipynb<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;└── prophet_analysis.ipynb<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── .DS_Store<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── LICENSE<br>
&nbsp;&nbsp;&nbsp;&nbsp;└── README.md<br>



## Section 3 -- Reproducing the Results

1. [Clone the repository](https://github.com/KaranRawatUVA/ds4002_project1.git)
2. First go to the python notebook _scraping_cleaning.ipynb_ and run each code box in order. This will produce the data set.
4. Now go to the python notebook _EDA.ipynb_ and run each code box in order. This will produce data visualization.
5. Lastly, go to the python notebook _analysis.ipynb_ and run each code box in order. This will produce the statistical analysis. 
