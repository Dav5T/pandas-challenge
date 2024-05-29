# Project Background
The school board and mayor has asked for help with making strategic decisions regarding future school budgets and priorities. The first task is to analyze the district-wide standardized test results. Provided is the access to every student's math and reading scores, as well as various information on their school. In order to showcase the obvious trends in school performe, the data needs to be aggregated. 

### Required files:
In the Resources folder, there are 2 files: 
    <br>1. Python-Challenge\PyBank\Resources\schools_complete.csv
    <br>2. Python-Challege\PyPoll\Resources\students_complete.csv

### Perform aggregate
In order to perform all the aggregation, you will need to run each line of code from PyCitySchools.ipynb. You will also find a summary of the analysis and trends at the top of the file. 

### Sources
*Pandas dataframe get first row of each group*
<br>https://stackoverflow.com/questions/20067636/pandas-dataframe-get-first-row-of-each-group

*Pandas, groupby where column value is greater than x*
<br>https://stackoverflow.com/questions/29632784/pandas-groupby-where-column-value-is-greater-than-x

*Python - Converting dollar values to float*
<br>https://stackoverflow.com/questions/59043604/python-converting-dollar-values-to-float



#students_passing_math = school_data_complete[(school_data_complete["math_score"] >= 70)].groupby(["school_name"]).count()["math_score"]
#school_students_passing_math = students_passing_math/ per_school_counts * 100

#students_passing_reading = school_data_complete[(school_data_complete["reading_score"] >= 70)].groupby(["school_name"]).count()["reading_score"]
#school_students_passing_reading = students_passing_reading/ per_school_counts * 100
