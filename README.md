# School_District_Analysis

## Overview of the school district analysis:

Maria and her supervisor has been asked to assist them with a dilemma that __Py City School__ is facing with the results of the standardized tests results.  From all appearances there seems to be evidence of grade dishonesty for grades in math and reading for __Thomas High School__. This is significant because standardize test grades are important for the decision making process for student funding such as budget priorities and making other strategic decisions on a school and district level. 
Maria has been instructed to replace the test scores for math and reading, specifically for the 9th grade. She is then asked to analyse how this impacts the overall results of all the school districts as a whole and how Thomas High school stacks up agains other schools in the district after the change. Below we will review the results first the performance with out the removal of the "suspect" score and the refactored results, that is after the removal of the scores for the 9th graders.

## Results:

**Original District Summary**
![District Summary](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/District_Summary.PNG)

**Refactored District Summary**
![Refactored District Summary](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Refactored_District_Summary.PNG)

###### Analysis of District Summary

In an overview of the __District Summary__  we observe that the overall passing percentage had a very slight decrease, before the scores were removed it was __65.17__ and after the refactored score is __64.90__.  This is influenced by the expected decreases in in the percentage passing reading which fell from __85.80__ to __85.70__; in math the percentage fell from __74.98 to 74.80__.

**Top Performing Schools**
![Top Performing Schoolsy](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Top_Performing_Schools.PNG)

**Refactored Top Performing Schools**
![Refactored Top Performing Schools](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Refactored_Top_Performing_Schools.PNG)

###### Analysis of Top Performing Schools

Dispite the removal of 9th grade math and reading scores __Thomas High School__ remained the __second highest__ top performing school before removal of the math and reading scores their overal percentage was __90.95__, which then fell to __90.63__. This left them behind the top performing school __Cabrea High School at 91.34__ and just infront of the third highest performing school __Griffin High School at 90.59__.  It is noted that all three of these schools are 'Chartered Schools'.

**Math Scores by Grade**

![Math Scores by Grde](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Passing_Math_ByGrade.PNG)

**Average Math Scores by Grade Refactored**
![Average Math Scores by Grade Refactored](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Refactored_Passing_Math_ByGrade.PNG)

###### Analysis of Average Math Scores by Grade

Thomas High School average math score __before the 9th grade scores was removed was 83.43__ and after it was removed the overall score fell to __83.36__ which is a small fraction of a difference of __.08__.  The top prforming school Cabreara High overall average was __83.1__ and third highest performing school Griffin High was __83.35__. 
In terms of the 9th grade scores that was removed, __Thomas High School had an average of 83.6__. This however was not the highest average in math score, the __highest score__ was by __Holden High Score with 83.8__ and __Pena High tied with Thomas High with an average of 83.6__.

**Reading Scores by Grade

![Reading Scores by Grade Refactored](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Passing_Reading_by_Grade.PNG)

**Reading Scores by Grade Refactored**

![Reading Scores by Grade Refactored](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Refactored_Reading_byGrade.PNG)

###### Analysis of Reading Scores by Grade

In terms of __9th grade reading scores Thomas High had an average of 83.7__ however it should be noted that two other schools _tied with this exact average namely: Holden High and Cabera High_. The school with __highest 9th grade reading score was Wilson High with a score of 83.9__ followed by a tie of __Wright High and Pena High with an 83.8__. It is noted that the school with the __highest overall average is Cabera High with a score of 84.03__ followed by __Wilson High with a score of 84__.  Both __Thomas High and Griffin are in third place with an average of 83.85__. When the scores are refactored removing the 9th grade score this actually improved the overall average of Thomas High and now ties them in second place with an overall average of 83.9.

**Scores by Spending**

![Scores by Spending](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Schools_Spending.PNG)

**Scores by School Spending Refactored** 

![Scores by School Spending Refactored](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Refactored_School_Spending.PNG)

###### Analysis of Scores by Spending 

Schools with th largest budget that fell between __$645 to 675 per student__ and had an __overall passing of 54%__, whereas schools with __smaller budget of $584 per student__ or less an an __overall passing of 90%__. For Thomas high schools that fell in the category of a __medium budget of $630 -644 per student__ the percentage of passing math and passing reading was _76% and 86%_ respectively. We see a small expected drop in the passing math and passing reading figures, for passing reading we saw a drop from _76% to 73.46%_ and for math from _86% to 84.3%_.

**Scores by School Size**
![Scores by School size](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/School_Spending_Size.PNG)

**Scores by School Size Refactored**
![Scores by School Size Refactored](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Refactored__School_Spending_Size.PNG)

###### Analysis of Scores by Size

For small schools that is schools with __less than 1000 students__ and medium schools with a student population of between __1000-2000__, passing math scores are __93.5% and passing reading is at 96 - 96.79%__.  Medium sized schools have an overall passing of __90.62 which is the highest__.  It is observed that schools with the __largest student population of 2000 - 5000 students__ have an overall passing of __58.28%__. Thomas High school falls in the category of medium sized school and we see only a small fraction of decrease in the overall passing % when the grades are refactored to remove the 9th graders score from _90.62 to 90.55_.

**Scores by School Type**
![Scores by School Type](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Spending_School_Type.PNG)

**Scores by School Type Refactored**
![Scores by School Type Refactored](https://github.com/wallaceportia/School_District_Analysis/blob/main/Resources/Resource_pics/Refactored_Spending_Type.PNG)

###### Analysis of Scores by School Type

We can quickly observe that Chartered Schools outperform Distrit Schools in all categories.  The overall passing percentage for Chartered Schools is at least 40% higher than that of District Schools; Chartered Schools have an overall passing of 90% whereas District Schools have an overall passing of 54%

## Summary:

We can then summarize that replacing the math and reading scores for 9th graders in Thomas High Schools did not cause the school to have an overall lowere performance.  In fact Thomas High School remained the second highest performing schools in both the Chartered and District schools.
The following can be observered by our analysis:
  ** Replacing Thomas High Schools 9th graders scores with nans did not improve or make worst the scores of any of the other grades in all of the schools
  
  ** In fact in one instance the removal of the math grade improved Thomas Hight School overall passing percentage
  
  ** Schools performance is not directly corealated to budget spent per student, it was clear that schools with the largest budgest did not necessary perform better than             schools with medium budgets
  
  ** Schools size seems to have more of a positive realationship to student and school performance.  However it is medium sized schools that perform the best.  It may be            because there is a good teacher to student ratio, where kids get sufficient individual attention but there are enough students to foster competition
  
  ** Also Chartered schools outperform District schools, this may have to do with the ciriculum (we do not have data for this insight), as well as smaller class sizes.



