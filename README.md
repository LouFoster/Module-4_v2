# Module-4_v2
#Overview of Project
(As captured from Data Bootcamp Module 4) 

As a Data Analyst, I am assisting Maria, the chief data scientist for a city school district. Maria is responsible for analyzing information from a variety of sources and in a variety of formats. In this role, she is tasked with preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns.

By the end of this module, as assigned Data Analyst, I ,will complete the following::
•	Collect data by importing CSV files into Pandas DataFrames.
•	Prepare and clean data for analysis by using Pandas functions.
•	Generate summary statistics for a DataFrame.
•	Create and customize plots for the data in a DataFrame.
•	Select specific data for close analysis.

##Purpose

In this module, as the assigned Data Analyst I will be using Pandas, which is a Python library, along with Jupyter Notebook to automate and simplify processes that analysts do every day.

Pandas is designed specifically for data analysis. So, it eases working with data from practically any type of file. And with the combination of Pandas and Jupyter Notebook, we can efficiently import, prepare, and analyze data of any type or quantity.

##Results

##Deliverable 1: Collect the student data into a DataFrame.
1.	Import the data 

2.	Confirm that Pandas correctly imported

![image](https://user-images.githubusercontent.com/117233641/226212215-82463898-6cb7-4b6b-9d6a-77e81e30fb51.png)



##Deliverable 2: Prepare a cleaned version of the DataFrame.
1.	In the student DataFrame, check for rows that have NaN (or missing) values, and remove those rows

2.	In the student DataFrame, check for duplicate rows, and remove them.

![image](https://user-images.githubusercontent.com/117233641/226212238-1f297f63-8b05-49c7-b3d2-fc0460aacf8b.png)


3.	Check the data types of the columns by using the dtypes property, as the following image shows:

![image](https://user-images.githubusercontent.com/117233641/226212254-eb53fd91-b5e0-4464-98a2-fdede4521b95.png)

 

4.	In the grade column, remove the "th" suffix from every value by using str and replace, as the following image shows:

![image](https://user-images.githubusercontent.com/117233641/226212269-adb54a7e-0459-4fcf-a9bd-4a0657d31905.png)

 

5.	Change the "grade" column to the int type, and then verify the column types, as the following image shows:
 
 ![image](https://user-images.githubusercontent.com/117233641/226212276-decf79fd-6123-44af-b716-72ca3b425dfd.png)



##Deliverable 3: Summarize key pieces of the data.
1.	Generate the summary statistics for the student DataFrame by using the describe function, as the following image shows:

![image](https://user-images.githubusercontent.com/117233641/226212286-6961ed54-4682-40fd-9c28-f34d51cd7cc6.png)

 

2.	Display the mean math score by using the mean function.
 
 ![image](https://user-images.githubusercontent.com/117233641/226212292-2a2ab9c8-58ab-4911-bd28-6ef2a3d57d09.png)


3.	Store the minimum reading score in min_reading_score.

 ![image](https://user-images.githubusercontent.com/117233641/226212310-f27a590e-d9c9-4ce8-a5c8-44f43b022cbc.png)




##Deliverable 4: Drill down into the data to analyze specific subsets.
1.	Display the grade column by using loc, as the following image shows:
 
 ![image](https://user-images.githubusercontent.com/117233641/226212316-f52fe58d-cf89-49fd-af38-4ccaada36d76.png)


2.	Display the first three rows of Columns 3, 4, and 5 by using iloc, as the following image shows:

![image](https://user-images.githubusercontent.com/117233641/226212324-9dfb92e7-e67b-4faf-9703-6ba8fc8312bf.png)

 
3.	Select the rows for Grade 9, and display their summary statistics by using loc and describe, as the following image shows:

![image](https://user-images.githubusercontent.com/117233641/226212329-7b65ba9d-59f9-40d2-9157-426ab14c6b56.png)


4.	Store the row with the minimum overall reading score in min_reading_row by using loc and the min_reading_score variable from Deliverable 3, as the following image shows:
 
![image](https://user-images.githubusercontent.com/117233641/226212340-884eda3e-2fef-4edd-ab67-5bc063cb1b26.png)


5.	Select all the reading scores from the 10th graders at Dixon High School by using loc with conditionals, as the following image shows:

![image](https://user-images.githubusercontent.com/117233641/226212346-c9f6a0a0-0446-45d7-981c-fc344252a4e6.png)

 


6.	Find the mean reading score for all the students in Grades 11 and 12 combined by using conditional statements and loc or iloc.

 ![image](https://user-images.githubusercontent.com/117233641/226212352-b4fa7dea-72f8-4ab7-86dd-8b9801c967f2.png)


##Deliverable 5: Compare and contrast the data through grouping and aggregation functions.

1.	Display the average budget for each school type by using the groupby and mean functions, as the following image shows:
 
![image](https://user-images.githubusercontent.com/117233641/226212362-51dcee06-73fb-4854-a916-a7dece5f542a.png)


2.	Find the total number of students at each school, and sort those numbers from largest to smallest by using the groupby, count, and sort_values functions, as the following image shows:

![image](https://user-images.githubusercontent.com/117233641/226212368-ff9ae6ad-5747-486f-9731-377c7b868a7c.png)

3.	Find the average math score by grade for each school type by using the groupby and mean functions, as the following image shows:

 ![image](https://user-images.githubusercontent.com/117233641/226212382-ae66d47c-f97b-4437-8689-c4923d1572a0.png)



##Deliverable 6: A written analysis of your results (README.md).

(As outline and demonstrated in module 4 ) Although no single best way exists for analyzing data, it typically follows a three-phase process:
1.	Collect the data: In this phase, we collect the data for analysis by importing it into a structure that Python and Pandas can work on.

2.	Prepare the data: In this phase, we clean the data to account for missing, incomplete, erroneous, and duplicated data. This phase also includes manipulating segments of the dataset to highlight the relationships among variables.


3.	Analyze the data: This phase consists of an iterative process and varies depending on the goal of the analysis or research. Regardless of the specifics, the analysis involves testing a thesis, reviewing the results, and refining both until we reach a conclusion.


Based on this approach, the data analyzed shows Charter schools generally performed better than District schools in this analysis. The top five schools with the highest overall passing percentages are all Charter schools, whereas the bottom five are all District Schools.

Display the average budget for each school type by using the groupby and mean functions, as the following image shows:
 
![image](https://user-images.githubusercontent.com/117233641/226212409-e26c1954-7d4e-4c09-9abd-54b7c762b806.png)


