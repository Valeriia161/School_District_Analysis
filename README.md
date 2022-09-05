# `PyCitySchools Challenge`


## `Project Overview `  <br/>
In this analysis, I looked at the state testing outcomes for the PyCity School District. I calculated the average math and reading scores for each school site, as well as the passing rates for each section of the test, and the overall passing rate. I determined the top 5 and bottom 5 performing schools in the district. I further broke down the data into categories in order to compare performance between schools based on a number of variables including the amount spent per student, school size, and type of school (charter or district). After the initial analysis, there became some question of the reliability of the data from the Thomas High School 9th grade class. In order to correct for these possible issues, I stripped the 9th grade scores from Thomas High School and replaced them with blank, Nan values. Then, I re-ran the analysis with the corrected data. <br/>
### `Resources`  <br/>
•	Data Source: [Google]( Google), [PyCitySchools_Challenge](https://github.com/Valeriia161/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)<br/><br/>
•	Software: Python 3.6.1, Jupyter, Git Bash.
## `Results` <br/>
#### How is the district summary affected? <br/>
Excluding the Thomas High Schools 9th grade students Reading and Math scores were slightly affected by tenths of average scores in Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing. 


![](https://github.com/Valeriia161/School_District_Analysis/blob/main/pic1.png)
![](https://github.com/Valeriia161/School_District_Analysis/blob/main/pic2.png)


#### How is the school summary affected? <br/>
In the tables below, the difference when excluding the Thomas High Schools 9th grade students Reading and Math scores are minimum. In this table, the Thomas High School scores without the 9th, slight decrease, for example in % Overall Passing from 90.94 to 90.63. Comparing Thomas High School % Overall Passing placement does not change much either. 


![](https://github.com/Valeriia161/School_District_Analysis/blob/main/pic%203.png)
![](https://github.com/Valeriia161/School_District_Analysis/blob/main/pic4.png)


#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? <br/>
Replacing ninth graders’ math and reading scores does not affect their % Overall Passing marks. They are still within the 90 percentile passing mark. Also, Thomas High School is in second place of the top high school.


![](https://github.com/Valeriia161/School_District_Analysis/blob/main/pic5.png)


#### How does replacing the ninth-grade scores affect the following: <br/>
###### Math and reading scores by grade. <br/>
Excluding the ninth graders’ math and reading scores from Thomas High School only change slightly and Thomas High School still holding the 2nd Top Five Schools in the district. <br/>
###### Scores by school spending. <br/>
These appear to show that higher scores on the exams tend to be more associated with being in the lower spending ranges. <br/>
###### Scores by school size. <br/>
The scores by school size are also minimum affected by excluding the ninth graders’ math and reading scores from Thomas High School (The larger the school, the lower the test scores). <br/>
###### Scores by school type. <br/>
The scores by school type size are also minimum affected by excluding the ninth graders’ math and reading scores from Thomas High School (District schools had lower passing rates than the Charter schools in the district). <br/>

## `Challenge Overview` <br/>
For the Module 4 Challenge I needed to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact because the [students_complete.csv]( https://raw.githubusercontent.com/Valeriia161/School_District_Analysis/main/students_complete.csv.csv) file shows evidence of academic dishonesty. <br/>
## ` Summary` <br/>
In this analysis, I removed the math and reading test scores and replaced them with blank, NaN values for Thomas High School in the PyCity Schools District Analysis. This was requested after there was some suspicion of the academic integrity of the scores of these students. After the 9th grade scores were removed, the analysis was performed again. There were no changes in the overall outcomes of the analysis when these suspect values were removed. The ranking of Thomas High School was not altered relative to the other schools and the overall percentages for Thomas High School were not changed when rounded to the nearest whole value.
