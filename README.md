# School_District_Analysis
## Overview of the school district analysis
The purpose of this project was to analyse data from several district schools in order to guide district's planning for the next school year. The data included information about reading and math scores, school size, type of school, and budget.However, after the analysis was completed in PyCitySchools.ipynb, the analysis had to be modified to exclude math and reading scores for 9th grade students from Thomas High School due to those scores being modified, 
## Results
Deliverable 1. 
![Deliverable_1](https://user-images.githubusercontent.com/96098938/151106147-d4a0a3ef-d510-4681-8e5f-d056bf14eaf2.PNG)
In order to re-run the analysis, all results for reading and math results for 9th grade students from Thomas High School were replaced with Nan. 

After comparing results of the analysis in PyCitySchools_Challenge.ipynb vs. PyCitySchools.ipynb several differences were observed. 
### How is the district summary affected?
- After the grades for 9th grade students from Thomas High School were removed, there was a slight downward change in all average scores(Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing) since some of the higher scores were removed. 
### How is the school summary affected?
- After the  grades were removed, it changed the position of Thomas High School on the list of high and low performing schools, moving it from the 2nd place to the 13th with overal passing percenatage of 65% vs. 90% before the change.  
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- After cleaning the data, math and reading scores for Thomas High School changed to 66.9%% for math and 69.6% for reading vs. 93% for math and 97% for reading prior to change. Such a drastic change is attributed to replacing all values for 9th grade students for reading and math with NaN which ultimately replaced them with zeros and now counts all 9th grade students as failing. 

### Summary: 
After the analysis was performed with the exclusion of corrupted data, several things have changed. The biggest change was observed in the overall ranking of Thomas High School, moivng it from one of the top performing schools to the 13th positon on the list consisting of 15 schools in the district. With all scores for 9th graders now being reported as zeros, the average reading, math, overall scores and percentages are inacurate and are affected in a negative way significantly dropping the average results. The smallest change observed was in the overall district summary due to the large pool of scores. 
