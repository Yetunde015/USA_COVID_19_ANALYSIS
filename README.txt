# USA_COVID_19_ANALYSIS
Covid 19 Data Analysis for USA showing death rate, infection, rate and recovery rate from 2020 till 3/29/2022.
The data was culled from CDC website(https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36/data). 
-The project shows covid 19 spread across the United State. -It also shows the death rate, infection rate, recovery rate of any state selected by the user.

# The Code Louisville Data Analysis Course1 for January 2022 requirements met are:
  1. Read data from an external file, such as text, JSON, CSV, etc, and use that data in your application.
  2. Visualize data in a graph, chart, or other visual representation of data.
  3. The program should utilize a virtual environment and document library dependencies in a requirements.txt file.
  4. Use pandas, matplotlib, and/or numpy to perform a data analysis project. Ingest 2 or more pieces of data, analyze that data in some manner, and display a new result to a graph, chart, or other display.
  5. Use a Jupyter notebook to document your data analysis.
  6. Create and call at least 3 functions or methods, at least one of which must return a value that is used somewhere else in your code. To clarify, at least one function should be called in your code, that function should calculate, retrieve, or otherwise set the value of a variable or data structure, return a value to where it was called, and use that value somewhere else in your code. For example, you could create a function that reads how many items there are in a text file, returns that value, and later uses that value to execute a loop a certain number of times.

# The following packages are required to run this project:
 1. Python 3.9.11
 2. Jupyter notebook 6.4.5
 3. Pandas
 4. Numpy
 5. Matplotlib
 6. Plotly

# How to run the project (NB: Jupyter Notebook 6.4.5 is essential to run this project):


A. Using Jupyter Notebook
      >>!pip install pandas numpy matplotlib plotly

		OR 

B.- Using Virtual enviroment: (IF YOU HAVE ANACONDA) Type the following in Anaconda CMD: 
      >> conda create -n venv python=3.9.11 
      >> conda activate venv 
      >> pip install -r requirements.txt 
      >> jupyter-notebook

2. Once in Jupyter Notebook, navigate to the directory where you downloaded the project
3. Open the Covid_19_Analysis_using_USA_data.ipynb
4. CLick 'Run All'
5. The project will ask you to select a state. Type the state abbreviation e.g KY, TX, CA etc
