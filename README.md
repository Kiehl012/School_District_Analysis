# School_District_Analysis

## Overview
The purpose of this analysis was to help the chief data scientist of a city school district combine data from multiple sources and provide insights on student performance trends. Specifically, we looked at how student performance by grade, school type (district or charter), budget (per student), and size (number of students). After the original analysis, there were some questions about the integrity of 9th grade reading and math scores at one particular school. It was decided that those data points would be removed and we performed the analysis again to see whether or not that changed outcomes.

## Results

### District Summary Before and After Thomas High School 9th Grade Math and Reading Scores Were Removed

#### Before
![old_district_summary](https://user-images.githubusercontent.com/90878911/137651718-2b44afa3-8ad1-4da9-b246-6937fa09108a.png)
	
#### After	
![new_district_summary](https://user-images.githubusercontent.com/90878911/137652177-28e4af7a-2b39-4f1b-8382-d49f8e4753ae.png)

From this, we can see that removing the data in question did not significantly alter district-wide scores. In fact, the only difference is that the average math score dropped by .1 points.


### Per School Summary Before and After Thomas High School 9th Grade Reading and Math Scores Were Removed

#### Before
![old_school_summary](https://user-images.githubusercontent.com/90878911/137652948-d59f4559-fc53-4402-8e2b-28619dcf941a.png)

#### After	
![new_school_summary](https://user-images.githubusercontent.com/90878911/137652814-d5bd91a5-b756-4c12-a358-44933fae1615.png)

After removing the math and reading scores from Thomas High School, we can see that while the average scores were largely unaffected, the "Percent Passing" metrics fell drastically. That's because this summary was still counting the 9th graders in the total student count even though their scores were removed from the data set.