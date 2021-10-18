# School_District_Analysis

## Overview
The purpose of this analysis was to help the chief data scientist of a city school district combine data from multiple sources and provide insights on student performance trends. Specifically, we looked at how student performance differed by grade, school type (district or charter), budget (per student), and size (number of students). After the original analysis, there were some questions about the integrity of 9th grade reading and math scores at Thomas High School. It was decided that those data points would be removed and the analysis would be performed again to see whether or not our results were affected.

## Results<br/>

### District Summary Before and After Thomas High School 9th Grade Math and Reading Scores Were Removed<br/><br/>


#### Before<br/>
![old_district_summary](https://user-images.githubusercontent.com/90878911/137651718-2b44afa3-8ad1-4da9-b246-6937fa09108a.png)<br/>
	
#### After<br/>
![new_district_summary](https://user-images.githubusercontent.com/90878911/137652177-28e4af7a-2b39-4f1b-8382-d49f8e4753ae.png)<br/><br/>

From this, we can see that removing the data in question did not significantly alter district-wide scores. In fact, the only difference is that the average math score dropped by .1 points.<br/><br/><br/>

### Per School Summary Before and After Thomas High School 9th Grade Reading and Math Scores Were Removed


#### Before
![old_school_summary](https://user-images.githubusercontent.com/90878911/137652948-d59f4559-fc53-4402-8e2b-28619dcf941a.png)

#### After	
![new_school_summary](https://user-images.githubusercontent.com/90878911/137653576-bdd38bbf-82c2-4299-969b-18cb7cd2ea21.png)


After removing the math and reading scores from Thomas High School, we can see that average scores and the percentage of students passing both math and reading was largely unchanged. <br/><br/><br/>


### Scores by: Grade, School Spending, School Size, and School Type
In the tables below, Thomas High School (or the spending, size, and type category it falls into) are highlighted. These tables show us that after removing the 9th grade math and reading scores at Thomas High School, the overall analysis was virtually unaffected. This means the district can feel confident that the analysis is still realiable after removing that data.<br/><br/>

#### Math and Reading Scores by Grade
                       Before 9th Grade Data Was Removed
               Math                                        Reading
![old_math_by_grade](https://user-images.githubusercontent.com/90878911/137656420-83ed59c6-2a2d-4c88-8f83-dc592e935452.png)  ![old_reading_by_grade](https://user-images.githubusercontent.com/90878911/137656429-630f0cdd-1912-4eed-b3d9-480f3ef642df.png)

                       After 9th Grade Data Was Removed
                Math                                        Reading
![new_math_by_grade](https://user-images.githubusercontent.com/90878911/137656651-542b16e0-6274-4c99-bcb5-fbf1fadd44bf.png)  ![new_reading_by_grade](https://user-images.githubusercontent.com/90878911/137656653-67171cf8-b5e1-466e-ab55-68ef25ac3451.png)<br/><br/>


#### Scores by School Spending<br/>


                                 Before 9th Grade Data Was Removed
![old_by_spending](https://user-images.githubusercontent.com/90878911/137658513-7b93f1d1-0cb8-4421-8761-45b48784c09d.png)<br/><br/>

                                 After 9th Grade Data Was Removed
![new_by_spending](https://user-images.githubusercontent.com/90878911/137658503-be701da5-fb03-4f5b-9201-73c06bf2c909.png)<br/><br/>

#### Scores by School Size<br/>


                                 Before 9th Grade Data Was Removed
![old_by_size](https://user-images.githubusercontent.com/90878911/137659134-13a5d8a3-caa2-4c9a-9cb7-6736ab0523a6.png)<br/><br/>

                                 After 9th Grade Data Was Removed
![new_by_size](https://user-images.githubusercontent.com/90878911/137659127-dff5ae97-b4c3-4e96-8a8a-ed390f75a730.png)<br/><br/>


#### Scores by School Type<br/>


                                 Before 9th Grade Data Was Removed
![old_by_type](https://user-images.githubusercontent.com/90878911/137659367-c2e1f55a-0d63-4bbc-9c8b-c9de49c1deb3.png)<br/><br/>

                                 After 9th Grade Data Was Removed
![new_by_type](https://user-images.githubusercontent.com/90878911/137659363-231fa8c6-02c2-4c2b-aa32-e6d14364f599.png)<br/><br/><br/>


## Summary
From this analysis, we were able to confirm that removing the 9th grade scores from Thomas High School did not significantly impact our analysis. In fact, when we looked at scores by school spending, size, and type, our outputs were exactly the same. We could have inferred this from the district summary alone. When we saw that Thomas High School scores were only slight different after removing 9th grade scores, it would have been safe to say that aggregate data from the district would be affected even less.

