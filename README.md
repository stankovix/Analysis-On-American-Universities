
# **ANALYSIS OF AMERICAN UNIVERSITIES**

**The aim of this project is to find out which are the most important features that students consider before choosing their preferred American University. Some of the essential questions for developing this project are related to the number of applications, admissions, and enrollments, cost of tuition and fees, cost of living on campus, types of degrees offered, and features of the states where universities are located (population and GDP).**

**The dataset used for this analysis was taken from Kaggle. It contains a lot of information about American Universities (that are not necessarily the top 10-20) in 2013. Although this dataset does not contain information about all the first-ranked American Universities, the patterns and insights extracted from it are highly representative of the whole behavior. The dataset contains more than a thousand rows (Universities) and 145 columns (features about those Universities). Several of those features are out of the scope of this project. Only the features that have information to answer the questions to achieve the goal of the project were deployed. The most powerful tools for data analysis used in this project are the packages Numpy and Pandas, and to visualize and explore the data: Matplotlib and Seaborn was used**


## Authors

- [@octokatherine](https://github.com/stankovix)


## Installation

Kindly take note of the following libaries and models below:

```bash
  
import warnings
warnings.filterwarnings("ignore")

IMPORT THE FOLLOWING LIBRARIES:

import pandas as pd
import numpy as np
import matplotlib
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns
```
    

## **STEPS TAKEN IN THIS PROJECT:**

1. # **Reading the Dataset.**
This chapter presents the steps to read the dataset about American Universities.


2. # **Data Preparation: Cleaning and Formatting.**
In all data-analysis projects, the data preparation step is not only necessary but also vital to find and handle features that could cause some problems while making the quantitative analysis, or that could lead to low efficient coding. According to Alivia Smith[1], this step usually takes up to 80% of the entire time of a data analysis project. Therefore, missing, invalid, and inconsistent values have been addressed. Finally, this step presents a code for changing the format of column names.


3. # **Exploratory Data Analysis (EDA) and Visualization. Quantitative and qualitative analysis (Asking and Answering Questions).**
Although in many cases, the exploratory data analysis and the quantitative and qualitative analysis are separated steps, in this specific project, they have been joined. This step, previous to asking questions that could lead to reaching the project's aim, presents global-useful information about the different columns of the dataset. Some initial examinations were performed as a way of beginning finding patterns, creating hypotheses, and corroborating early assumptions. Later, deeper investigations were depicted as part of reaching the project's goal.

Quantitative and qualitative analysis: Asking and Answering Questions.
The hypotheses and questions generated to develop this projects are:

Do universities with a high number of applications are the preferred ones by students?; in other words, could the number of applications tell us that a university is one of the most preferred by students?.
Do students prefer universities that have a high rate of admission?, in other words, do students prefer a university where it is easier for them to be admitted?.
Do students prefere public or private universities?
Do students prefer universities with low tuition and fees?
Do students prefer a university for its low on-campus cost of living?
Do students prefer universities from highly populated states?
Do students prefer a university because it belongs to a state with a high GDP per capita?
Do students prefer a university based on the possibility of a higher, additional academic degree in the same university?




Although all conclusions and answers are exposed in the previous section accordingly to each question, this section also presents, in a concise manner, the most significant insights.





![Logo](https://github.com/stankovix/Analysis-On-American-Universities/blob/main/american-university.png?raw=true)

 # **Inferences and Conclusions.**
 
1. A high number of applications does not imply that a university is preferred among students. In fact, the universities that receive a lower number of applications are the ones with a higher enrollment rate. Obviously, there are some exceptions, but this is the strongest tendency.

2. Based on the lack of a strong pattern among admissions and the enrollment rate, we can say that students do not necessarily prefer a university because of its high acceptance rate or, in other words, the students'preference is not based on how easy it is for them to be admitted to a university.

3. By analyzing the enrollment rate, we saw that this rate, on average, is higher for public universities than the average for private universities. So, there is a strong students' preference for public universities.

4. When it comes to tuition and fees, students prefer affordable universities. Additionally, the reason or one of the reasons for the students' preference for public universities is that public universities are much more affordable than the majority of private universities.

5. In all the analyses made to find a pattern about costs for on-campus living, we found a high enrollment rate more frequently when costs are affordable. This means that students, in-state and out-state students, prefer universities with affordable costs of on-campus living.

6. The majority of public universities offer a much more affordable price for in-state students than private universities.

7. The average cost of living for out-state students that public universities offer is higher than that for in-state students. However, the average cost that private universities offer does not make a distinction between in-state and out-state students.

8. Since there was no firm trend when analyzing the state population with enrollment rates, we cannot say that students prefer universities of crowded states.

9. Students do not prefer a university because of the GDP per capita of the state where the university locates. In other words, students do not choose a university based on the overall well-being of states.

10. When students look for a university to study for a Bachelor's degree, they do not frequently choose the university thinking about a future possibility of pursuing a higher degree at the same university.

11. To get more accurate results, it's necessary to have the information of other years, expand the number of universities, and add information about their ranking.

