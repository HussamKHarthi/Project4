# Data Science Blog Post
This is the fourth project "Data Science Blog Post" in Data Scientist-Nano Degree Program by UDACITY.
In this project i've chosen the survey data provided by Stack Overflow.The aim of this project is to practice how to communicate with stakeholders your findings in a professional manner.
The survey used in nthe analysis was taken upon the website's members in year 2019. I've started by cleaning up the data and proposed 5 questions.

Through out the code i've analyzed, visualaized and communicated my findings for these questions.
The Libraries used are the typical ones: Matplotlib, Pandas, numpy & Seaborn.
Cleaning the data:
The dataset - as every dataset- had missing values, wrong data types. For missing data, i've chosen to drop them through out my analysis. For the columns [ConvertedComp], i've recalculated its values to be the annual salary instead of [Monthly,weekly,Annual]. For two level texual categorical values, i've chosen to recalaculate them as 0 & 1. 

##Findings

Q1) What are the common programming languages that are paid the most?

By Looking at the graph provided above, we can see that Erlang and Clojure are the most paid two languages with slightly more than 140k$ a year.

Q2) What are the most common languages with hobbyists?

The graph above shows us the popularity of common languages among surveyed members. we can notice that JavaScript, HTML/CSS, SQL & Python are by far the most popular three languages.

Q3) Most desired programming languages between developers?

Noted from bar chart above, the popularity and the desire of programming language are almost similar, except for the small difference that brought Java into 4th position.

Q4) Does More years, means more salary?

This question’s answer might seem trivial, but through looking at the data we have we can notice that the answer is a bit tricky. Through the first ten years of professional job as developer, we can observe some sort of steady increment regarding the annual salary, but after that, there aren’t observable trend in the following years of experience. I thikn the ansnwer to this question is “Personal Qualities”. Continuous self-learning in the field is the key for standing out and gaining growth in following years.

5) Stack Overflow reputation over years between surveyed entities?

thorugh looking at the graph shown in the article, we could see that SO was peaked around 2010, but it has steadily declining since 2012.


Here's the link for the article in Medium highlighting my findings:

https://medium.com/@hos.alharthi/eager-to-learn-programming-here-are-the-most-common-languages-between-stack-overflow-members-72ff37486abb

This Repo has three files:
1) ReadMe which communicate my motivation for the project.
2) Jupyter Notebook showing my analysis
3) HTML file of the Jupyter for a preview.


Thanks,
Hussam
