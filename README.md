**Reading CSV File:**
Make sure that the 2 csv files are sitting in, "Resources" folder: 
    1. Python-Challenge\PyBank\Resources\schools_complete.csv
    2. Python-Challege\PyPoll\Resources\students_complete.csv


**Sources**

In the School Summary section, no code was provided for selecting school type. 

Pandas dataframe get first row of each group
https://stackoverflow.com/questions/20067636/pandas-dataframe-get-first-row-of-each-group


Pandas, groupby where column value is greater than x
https://stackoverflow.com/questions/29632784/pandas-groupby-where-column-value-is-greater-than-x


Python - Converting dollar values to float
https://stackoverflow.com/questions/59043604/python-converting-dollar-values-to-float


** Extra code that I didn't use because I didn't understand the question at the time. This is for my own reference. 
School Summary Section 

#students_passing_math = school_data_complete[(school_data_complete["math_score"] >= 70)].groupby(["school_name"]).count()["math_score"]
#school_students_passing_math = students_passing_math/ per_school_counts * 100

#students_passing_reading = school_data_complete[(school_data_complete["reading_score"] >= 70)].groupby(["school_name"]).count()["reading_score"]
#school_students_passing_reading = students_passing_reading/ per_school_counts * 100