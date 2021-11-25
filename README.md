# School District Analysis
## Overview
The purpose of this project was to analyze student outcomes (math and reading scores) based on certain parameters, such as school size, spending, and type. The analysis was initially completed on the assumption that there was no academic dishonesty. Later on, it was learned that the grades of the 9th grade students at Thomas High School were not completely accurate. The code was refactored and the analysis was performed again after nullifying the inaccurate scores. 
## Results
The overall district school summary DataFrame was fairly similar when comparing the analysis before and after refactoring the code. The results were as follows for the analysis before and after, respectively. 
![Before](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/PyCitySchools%20-%20district_summary_df.png)\
![After](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/Challenge%20-%20district_summary_df.png)\
The average math scores for the entire district had a 0.1 difference, whereas the remainder of the values were basically the same. As for the school summary DataFrame, only the values for Thomas High School were changed. Although small, the score changes were all slightly lower than the original value, save for the overall reading score. The percentage of students who passed reading, math, and both were all reduced. The results are shown in the following DataFrames, prior to and after altering the score values respectively.
![Before](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/PyCitySchools%20-%20per_school_summary_df.png)\
![After](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/Challenge%20-%20per_school_summary_df.png)\
Although an entire grades' scores were removed from the analysis and the values were reduced, Thomas High School remained the 2nd ranked school based on the overall passing rate of the students. 
![Before](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/PyCitySchools%20-%20top%205%20schools.png)\
![After](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/Challenge%20-%20top%205%20schools.png)\
The bottom 5 schools were unchanged as none of the scores were altered for these particular schools. 
![Before](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/PyCitySchools%20-%20bottom%205%20schools.png)\
![After](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/Challenge%20-%20bottom%205%20schools.png)\
The overall math and reading scores from each grade level were identical, except for the scores for the 9th graders at Thomas High School, which were expectedly null. The average math scores based on grade level before and after the refactoring, respectively, were as follows:\
![Before](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/PyCitySchools%20-%20math_scores_by_grade.png)\
![After](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/Challenge%20-%20math_scores_by_grade.png)\
The average reading scores based on the grade level before and after the refactoring, respectively, were as follows:\
![Before](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/PyCitySchools%20-%20reading_scores_by_grade.png)\
![After](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/Challenge%20-%20reading_scores_by_grade.png)\
The scores by school spending per student were also unchanged before and after nullifying certain grades, as shown in the following DataFrames.\
![Before](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/PyCitySchools%20-%20spending_summary_df.png)\
![After](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/Challenge%20-%20spending_summary_df.png)\
As for the scores by school size, because Thomas High School was a "Medium" size school, there were slight changes in the overall values. Although the average reading scores for the "Medium" schools increased, the overall passing percentages were lowered, which can be seen in the following DataFrames:\
![Before](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/PyCitySchools%20-%20size_summary_df.png)\
![After](https://github.com/carrotdip/School_District_Analysis/blob/main/Images/Challenge%20-%20size_summary_df.png)\
The overall scores and passing percentages by school type, District and Charter, were unchanged before and after the analysis. The nullifying of the scores had no significant impact in the overall scores of the Charter schools. The District schools were unchanged, as the scores were not altered. 
## Summary

