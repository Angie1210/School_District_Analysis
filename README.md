# School_District_Analysis

## Overview of the Analysis
In this project we are going to get information that helps a School District Board to make decisions about budget allocations, we are going to analyze how different factors can affect the performance of each high school based on standardized math and reading tests, to do this we will start by cleaning the data, without taking in consideration all the Thomas High School 9th grader's test results due to dishonesty evidence. Then we will create different DataFrames to see how much the replacing scores affect the overall performance of the THS, by identifying possible correlations between the performances in the tests and the size, type and assigned budget of each school.  Our resources are two databases, one of the schools and one of the students in the District.

## Results
* How is the district summary affected?

The district summary didn't change, the average scores and percentages remain in the same proportion.
![Screen Shot 2022-03-20 at 12 35 37 AM](https://user-images.githubusercontent.com/43548929/159152853-9a278a98-2dc8-4dab-a2e6-3d75f59d40f6.png)

* How is the school summary affected?

It affects only the information of Thomas High School, changing it's passing_percentages, that's why we have to consider only THS's grades and students from 10th to 12th grades. In the first row we are considering the 9th graders on the student count but then we changed it.

![Screen Shot 2022-03-20 at 1 38 21 AM](https://user-images.githubusercontent.com/43548929/159154630-c7397dbc-e183-4361-8b93-658db9784aba.png)
![Screen Shot 2022-03-20 at 1 38 47 AM](https://user-images.githubusercontent.com/43548929/159154641-3323eaa1-f7f5-49b5-a17f-08947990e0f6.png)


* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

At the end it didn't affect, because as I said we only consider from grades 10th to 11th, so it was the second best school in overall passing.

![Screen Shot 2022-03-20 at 1 37 10 AM](https://user-images.githubusercontent.com/43548929/159154595-5f859a63-c03c-4570-a1ca-787c1b366017.png)

* How does replacing the ninth-grade scores affect the following:
** Math and reading scores by grade
All the information for THS 9th graders was declared null.

![Screen Shot 2022-03-20 at 1 34 56 AM](https://user-images.githubusercontent.com/43548929/159154530-9b0bfb1c-e0f1-4492-9e74-722e13dcc368.png)
![Screen Shot 2022-03-20 at 1 27 44 AM](https://user-images.githubusercontent.com/43548929/159154310-12342b58-bc26-41fa-b1ec-209a33b30794.png)

** There were no changes in the Scores by school spending
There were no changes
![Screen Shot 2022-03-20 at 1 31 13 AM](https://user-images.githubusercontent.com/43548929/159154394-a770fd46-19b6-4439-9afa-a5b9bb21a557.png)

** There were no changes in the scores by school size
![Screen Shot 2022-03-20 at 1 32 53 AM](https://user-images.githubusercontent.com/43548929/159154445-d5fab554-891a-40de-8a8f-50a376785286.png)

** There were no changes in the Scores by school type
![Screen Shot 2022-03-20 at 1 33 20 AM](https://user-images.githubusercontent.com/43548929/159154462-27d4cf0c-055b-40f2-9443-3997fc0d2d7c.png)

Summary.
After THS's reading and math scores for the 9th graders were considered to be alter. 
1) We have to clean the data and declared the grades as null values.
2) We have to reduce the total student count, to consider only those with valid grades.
3) Recalculate the averages of math and reading scores based, to consider only the grades of 10-12th graders.
4) Recalculate the passing math, reading and overall percentages based on the new total student.
