## Analysis of City Schools

![Education](Images/education.jpg)

This project concerns the education sector.
Assisting the Chief Data Scientist for this city's school district, I needed to help the school board and mayor make strategic decisions regarding future school budgets and priorities.

I was asked to analyze the district-wide standardized test results.
Given access to every student's math and reading scores, as well as various information on the schools they attend,
my responsibility was to aggregate the data to and showcase trends in school performance.

The final report included each of the following:

### District Summary

* A table of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### School Summary

* An overview table that summarized key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### Top Performing, and Bottom Performing Schools (By Passing Rate)

* Tables that highlighted the top 5, and bottom 5, performing schools based on `Overall Passing Rate`. Included are:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### Math Scores by Grade, Reading Scores by Grade

* Tables that list the average Math, or Reading, Score for students of each grade level at each school.

### Scores by School Spending, School Size, and School Type

* Tables that break down school performances based on `average Spending Ranges (Per Student)`. Included are:
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)
  
  ## School Analysis
  
* When observing the data, the top five performing schools were all charter schools, while the bottom five were all district schools. In fact, when comparing all fifteen schools on their overall passing rate, charter schools ranked above district ones.
  * Regarding future school budgets and priorities, we need to understand why all the schools under the district are not performing as well as schools operating under their own charter.
* Passing rates among grade levels were consistent, independent of which school was being looked at, i.e. if 80% of 9th graders were passing at any individual school, roughly 80% of students were passing at the 10th, 11th, and 12th grade levels.
* Passing rates have a negative correlation with how much money is spent relative to their student population. 
  * The district schools had the largest populations, largest budgets, and lowest passing rates.
  * We need to understand how schools are spending their budgets, as well as how charter schools are able to get by with some of the smallest budgets in the district.
* Perhaps the most surprising finding was discovered when comparing school types. While charter schools had significantly higher scores and passing rates when it comes to math, it is not as simple to reach a conclusion with reading scores.
  * The average reading score among charter schools was only 3 points higher than that among district ones, but district schools suffer a significant drop in their student population that is passing reading – roughly 16% lower than their charter counterparts.
  * We need to possibly consult with the head of the reading department for the district and understand why this discrepancy exists.

