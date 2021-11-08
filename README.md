# Overview of the school district analysis
School district requires to analyze information like schools & student information for example school budget, cost per student etc., how students performing their score in classes. Data comes by verity of source in csv files. Maria, the chief data scientist is responsible for analyzing & standardize test data for analysis, reporting and presentation to provide insight about performance, trends and pattern. These insights are used to informed discussion and strategic decision at the school and district level.

School board noticed and informed Maria and her supervisor that the “Thomas High School’s 9th grade data has been tempered for math and reading, School board doesn’t know state-testing standards and have asked Maria for help.

The Purpose of this analysis is to analyze the impact on various results like district summary, school summary and scores by schools spending and scores by school size and type are getting impacted without 9th grade math and reading score for Thomas High School.
# Results
## District Summary
As result of taking out 9th grade math and reading scores, 491 students’ math & reading results of THS got impacted, so it impacted district Summary as given below.

Before
![District_Summary_Before](https://user-images.githubusercontent.com/91766890/140677400-8e265a67-5480-4cc7-8831-23f4d1b76bd0.PNG)
After 
![District_Summary_After](https://user-images.githubusercontent.com/91766890/140677417-bd747aee-a2b1-4f08-8d4d-54676597c580.PNG)

1. The Average Math Score reduced from 79.0 to 78.9, however Average Reading was remains same.
2. Math % Passing score reduced from 75% to 74.8 
3. Similarly reading % Passing score slightly reduce from 85.8 to 85.7
4. Overall passing percentage also have change from 65.2 to 64.9

In short if we remove 9th grade score from THS, all metrics in terms of school district going down. This also indicates THS 9th grade scores where higher than the overall average. 

## School Summary 
Even after removing 9th grader score from Thomas High Schools, its didn’t much impact in terms of average and percentage value of number. It manages to maintain their position 

Before 

![School_summary_before](https://user-images.githubusercontent.com/91766890/140682118-1b3c62e7-837b-43a0-8e89-5cacb5e02131.PNG)

After 
![School_summary_after](https://user-images.githubusercontent.com/91766890/140682131-8bcd575a-24f0-4357-ba1e-d075c9da28e2.PNG)

Similarly, in-terms of comparing school positions with other schools, It remain in top 2nd other schools, this demonstrates that replace 9th grade score impact school because other class students are still high performing students. Below picture depicting clearly that even with some change in decimal number , its in the top 2nd position.

Before
![Top_5_schools_Before](https://user-images.githubusercontent.com/91766890/140682141-8e3f4df1-f410-4f0d-8de2-d71c2199e600.PNG)

After

![Top_5_schools_After](https://user-images.githubusercontent.com/91766890/140682148-0459f8bc-706d-4800-a871-3c2ca3fdef56.PNG)

