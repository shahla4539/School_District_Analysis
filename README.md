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

## Affects of replacing the ninth graders’ math and reading scores on Thomas High School’s performance relative to the other schools:

After the change in 9th graders Math and Reading scores, Thomas High School lost its position 
![image](https://user-images.githubusercontent.com/105535250/179386365-03ed2d2b-3690-4a67-84cd-7c5dff7a032a.png)


![image](https://user-images.githubusercontent.com/105535250/179386467-1c001591-b1d8-43ae-a6d6-1d04c11fa6c3.png)




## Replacing the ninth-grade scores affect on the following:

### * Math and reading scores by grade

It only changes the vallue of 9th grader Math score to nan. Rest of the grades metrics are still intact.

![image](https://user-images.githubusercontent.com/105535250/179384993-e888b75d-4ed9-429d-a0d4-3c07d6064c33.png)

Similarly, it only changes the vallue of 9th graders Reading score to nan. Rest of the grades metrics are still intact.

![image](https://user-images.githubusercontent.com/105535250/179385014-ae594cdd-d320-40da-91db-94f0347b6fb6.png)


### * Scores by school spending


Spending Metrics Before the change:

![image](https://user-images.githubusercontent.com/105535250/179385848-0418ffec-fe07-4cfe-897e-854663dd4368.png)
![spending_before](https://user-images.githubusercontent.com/105535250/179385570-0395ed09-5ce3-4626-abda-1b767d3adbfb.PNG)

Spending Metrics After the change:

![image](https://user-images.githubusercontent.com/105535250/179385857-db6d5187-099d-4e1a-9ad2-ce3e751aeacb.png)
![spending_after](https://user-images.githubusercontent.com/105535250/179385597-6a40c1a3-ee47-45fa-9919-3958cc269975.PNG)

As it is clearly visible in the images there is a very sligh change in the metrics based on spendinf bins. 




### * Scores by school size

Based on the final results, there is no change in metrics based on the school size. 

![image](https://user-images.githubusercontent.com/105535250/179385915-e02ca353-63a8-4c48-b03d-73fca13fdb3f.png)





### * Scores by school type

There is no affect on metrics based on school type as well.

![image](https://user-images.githubusercontent.com/105535250/179385941-3b461d21-9caf-44de-b84a-9bcde0d6259d.png)



