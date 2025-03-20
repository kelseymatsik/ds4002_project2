# Presidential Inauguration Speeches: Unification or Polarization? 
By _Data Destroyers (Kelsey Matsik - leader, Karan Rawat, Emma Mills, Emily Macris)_



## Contents of Repository
This repository contains all the work for Project 2 of Prototyping which has the goal of working with time series data. Specifcally, the goal of the repository is to answer the question: 
_How have crime rates in Charlottesville changed over time, specifically with respect to the UVA academic calendar?_<br>




## Section 1 -- Software and Platform
Throughout this project we used Github, Jupyter Notebook, VS Code and Python. The packages we used were _pandas, seaborn, matplotlib, scipy, numpy, requests, and bs4 (Beautiful Soup), Prophet, SARIMAX, Astral, and Pytz_. All of these packages would have to be downloaded in order to run the notebooks. Both Windows and Mac were used to complete this project.

## Section 2 -- Directory Map
ds4002_project1/<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── data/<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── Crime_Data.csv<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;└── cleaned_data.csv<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── scripts/<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── SARIMA_analysis.ipynb<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── SARIMA2_analysis.ipynb<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── preprocessing_EDA.ipynb<br>
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;└── prophet_analysis.ipynb<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── .DS_Store<br>
&nbsp;&nbsp;&nbsp;&nbsp;├── LICENSE<br>
&nbsp;&nbsp;&nbsp;&nbsp;└── README.md<br>



## Section 3 -- Reproducing the Results

1. [Clone the repository](https://github.com/kelseymatsik/ds4002_project2.git)
2. First go to the python notebook _preprocessing_EDA.ipynb_ and run each code box in order. This will produce the data set and some data visualizations.
4. Now go to the python notebook _SARIMA_analysis.ipynb_ and run each code box in order. This will produce the SARIMA model statistical analysis.
5. Then go to the python notebook _SARIMA2_analysis.ipynb_ and run each code box in order. This will produce the SARIMAX model statistical analysis.
6. Lastly, go to the python notebook _prophet_analysis.ipynb_ and run each code box in order. This will produce the Prophet model statistical analysis. 
