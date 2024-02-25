# School District Data Analysis Report

Welcome to my School District Data Analysis Report! In this assignment, I utilized Pandas and Jupyter Notebook to analyze school and standardized test data for my fictional city's school district. As the "Chief Data Scientist" at the time, I was tasked with aggregating the data to showcase trends in school performance to assist the school board and mayor in making strategic decisions regarding future school budgets and priorities.

## Background

As the Chief Data Scientist for the city's school district, I had access to every student's math and reading scores, as well as various information on the schools they attended. My objective was to create a report that included key metrics and trends in school performance. All calculations and code can be found in the PyCitySchools/PyCitySchools_RV.ipynb file.

## District Summary

I calculated key metrics for the entire district and created a DataFrame.
  - Total number of unique schools
  - Total students
  - Total budget
  - Average math score
  - Average reading score
  - % passing math
  - % passing reading
  - % overall passing

## School Summary

I created a DataFrame summarizing key metrics about each school.
  - School name
  - School type
  - Total students
  - Total school budget
  - Per student budget
  - Average math score
  - Average reading score
  - % passing math
  - % passing reading
  - % overall passing

## Highest-Performing Schools (by % Overall Passing)

I sorted schools by % Overall Passing in descending order and displayed the top 5 rows. I saved results in a DataFrame called "top_schools".

## Lowest-Performing Schools (by % Overall Passing)

I sorted schools by % Overall Passing in ascending order and displayed the top 5 rows. I saved results in a DataFrame called "bottom_schools".

## Math Scores by Grade

I created a DataFrame listing the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

## Reading Scores by Grade

I created a DataFrame listing the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

## Scores by School Spending

I created a table that broke down school performance based on average spending ranges (per student).

## Scores by School Size

I created a DataFrame called "size_summary" that broke down school performance based on school size (small, medium, or large).

## Scores by School Type

I created a new DataFrame called "type_summary" showing school performance based on the "School Type".

## Conclusion

In this report, I analyzed various aspects of school performance, including overall district metrics, individual school summaries, top-performing and lowest-performing schools, grade-level performance in math and reading, and the impact of school spending, size, and type on performance. Through this analysis, I aimed to provide valuable insights to inform strategic decisions regarding future school budgets and priorities. Through my analysis, I found two interesting facts about the data:

- Test scores for both math and reading actually got worse as school budget spending (per student) increased. As can be seen in the spending_summary data frame, schools that spent less than $585 per student had the highest average math and reading scores, as well as the highest percentage of students that passed those subjects. The average test scores and passing rates progressively decreased for every subsequent spending range.

- Charter schools outperformed district schools in all standardized test score measures. Average test scores and passing rates for both math and reading were all higher at charter schools than they were at district schools.

## Code Citations

Count items greater than a value in a groupby:
(Found in input cells 15 and 16 of PyCitySchools_RV.ipynb file)

https://stackoverflow.com/questions/40710811/count-items-greater-than-a-value-in-pandas-groupby

Create series then set index with .index:
(Found in input cells 11 and 13 of PyCitySchools_RV.ipynb file)

https://sparkbyexamples.com/pandas/pandas-set_index-explained-with-examples/?expand_article=1
