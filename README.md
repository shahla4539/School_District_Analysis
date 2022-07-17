# School_District_Analysis-Module_4

# Overview of the school district analysis:

**Maria** is the **Chief Data Scientist** for City School District. She is tasked to prepare standardized data for:
* Analysis,
* Reporting and
* Presentation

This data will provide the insight about the school`s performance trends and patterns and will be utilized towards making stretegic decisions at the school and district level.

I will be helping Maria analyze data on **School Funding** and **Student Standardized Test Scores**. I have access to every student`s Math and Reading scores as well as various information on the school they attend. My task is to aggregate data and showcase trends in school performances. This analysis will assist the board in school budgeting and also on setiing priorites. We will be handling data with confidentiality abiding the Family Educational Rights and Privacy Act (FERPA) to protects the students. 

### Development in Project:
 
Later the school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Therefore they want to uphold state-testing standards and asked Maria for help. I will help Maria to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I will replace the math and reading scores, I will repeat the school district analysis.

# Results:

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

## Affects on District Summary:

After repeating the analysis the district summary changes in almost every aspect. As we replaced the Math and Reading scores for 9th graders  with  **nan**, the codes I applied ignored the related information and that resulted in reduce of all the figures.

#### District Metrics Before the change:

![District_before](https://user-images.githubusercontent.com/105535250/179383709-e0866d68-b5dc-4685-b464-66e3c1d2004a.PNG)

### District Metrics After the change:

![District_After](https://user-images.githubusercontent.com/105535250/179383691-74e324c6-fc5f-4cbd-a8b8-af97b954f393.PNG)

## Affects on School Summary:

Similarly, the school summary also got affected but just in the Thomas High School details. Rest of the school did not get affected.

#### School Metrics Before the change:

![School_before](https://user-images.githubusercontent.com/105535250/179384208-2be69e64-8b39-4bec-b92c-c81347b09311.PNG)


#### School Metrics After the change:

![school_after](https://user-images.githubusercontent.com/105535250/179384217-7751e698-66a7-49f4-89d4-50d4c58c7091.PNG)



How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type
