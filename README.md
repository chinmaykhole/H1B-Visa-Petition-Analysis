# H1B-Visa-Petition-Analysis
The goal of the project is to analyse the H-1B visa petition data for the past 5 years and perform
exploratory analysis and predictive model on the same.
This includes all the petitions filed for H-1B from 2015 to 2019.


There are multiple categories on which it depends if a petition gets certified or denied.
*The basic parameters for a petition to be eligible to get certified are:*

● Someone needs to have found a job in the U.S.

● Employer agrees to sponsor an H-1B petition (working visa), who also pays the
	application fees, attorney, plus other paperwork hassles.

● The employee needs to have the appropriate expertise/education.

● Salary offered for that job needs to match the average wage for that particular job and
	that particular job in that area.

● Job position needs to be advertised online, local newspapers etc.
Not to mention other requirements.


*Was this project a Success? *
The project was to an extent a success as we were able to implement the majority of the things
that we had planned for, however initially had a plan to fit the data to a decision tree model to
predict the case status of a new case based on it’s feature parameters (Columns). But as it
turned out, this data is not that suitable to build a classifier on for prediction. We included a
regression model to predict the growth of a particular job in the coming years.

The data can be found at: https://www.foreignlaborcert.doleta.gov/performancedata.cfm
On this Link, press the Disclosure Data tab, when you scroll down you will find a table with
header “LCA Programs (H-1B, H-1B1, E-3)”. There are links to download the yearwise petition
data from that table. We worked on data from 2015 through 2019. (Both years inclusive).
As the data was raw, we had to spend a lot of time to firstly understand the same, clean it and
finally club it to make it ready for analysis. There names of the columns were mismatching, few
columns were added as and how we went ahead in terms of years from 2015 to 2019.
Data cleaning steps are as below (Kindly refer to the python notebook shared for the code):



*General findings about the data we analyzed (Details in the Notebook):*

● Number of applications keeps fluctuating throughout the years. Maximum applications in
the year 2019.

● CA, NJ and TX are the states from where most of the applications are.

● If we consider the states which have filed more than 150,000 applications in the last five
years cumulative and check their petition trend yearly, only CA has constant growth in
the number of filed petitions throughout the years. Other states have fluctuating number
of applications.

● The highest petition filing employers are considerably different from highest paying
employers.

● There is not much linkage between the case status getting certified or Denied with the
JOB_TITLE and job type as Full time or part time.


I want to thank Sharan Naribole for this amazing topic he shared on Kaggle. 
