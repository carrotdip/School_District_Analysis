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
