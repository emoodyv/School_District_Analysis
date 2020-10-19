# School District Analysis
## Overview
The goal of this project was to assist Maria and the school board in their analysis of 15 different high school's math
and reading grades. Unfortunately, there was evidence of academic dishonesty in the 9th grade at Thomas High School.
However, even with the exclusion of those grades there was still 38709 students data points to work with. With those 
points several important conclusions were able to be made.

## Results
With the data there was 7 results were resultants of the analysis. These, of course, were effected by the academic 
dishonesty in the 9th grade at Thomas High School. Therefore this section will seek to observe the difference between
the results with the 9th grade at THS include and the results with that grade discarded. Those comparisons are as
follows:

* How is the district summary affected?
One of the most rudimentary ways to look at the effect of the academic dishonesty is to look at the results from all of 
schools. If the dishonestly wasn't pervasive there would not be that big of a difference between the all inclusive
results and the 9th grade THS less results. Therefore, the fact that there is a .2% difference between the results
is concerning.

Orginal Results:
![District1](https://user-images.githubusercontent.com/71234992/96401105-4fae1d00-1187-11eb-8018-bcceb3a09ac7.PNG)
Refactored Results:
![District2](https://user-images.githubusercontent.com/71234992/96401106-4fae1d00-1187-11eb-83a0-0499803df87c.PNG)

* How is the school summary affected?
It is also important to look at the results for just Thomas High School. These results will show how the 9th grade
stacked up to the other grades. What was discovered was that the overall passing rated was decreased by .3% when
excluding the 9th grade. This shows that 9th grade may have had results skewed towards more passing students

Original Results:
![School1](https://user-images.githubusercontent.com/71234992/96401683-e5967780-1188-11eb-91b6-06d792848f35.PNG)
Refactored Results:
![School2](https://user-images.githubusercontent.com/71234992/96401684-e62f0e00-1188-11eb-98da-d046c8e7c8fe.PNG)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the 
other schools?
With the results for THS we can also compare to the results of the other 14 schools. What is found is that was THS was
the #2 performing school both before and after the refactoring.

Original Results:
![AllSchool1](https://user-images.githubusercontent.com/71234992/96406186-c0f3cd00-1193-11eb-8480-0cd85385c5c8.PNG)
Refactored Results:
![AllSchool2](https://user-images.githubusercontent.com/71234992/96406188-c18c6380-1193-11eb-90b9-68ddc09e68ce.PNG)

* How does replacing the ninth-grade scores affect the following:

    * Math and reading scores by grade
    Obviously only the 9th grade was effected by the change. So, when looking at the by grade results how did the 9th
    grade at Thomas High match up before their exclusion? In math THS 9th was tied for #2 and in reading THS was tied 
    for #4. Whereas, in 10th, 11th, and 12th and math and reading THS was #7, #1, #5, #8, #4, and #7 respectively.
    
    Math Results:
    ![Grades1](https://user-images.githubusercontent.com/71234992/96407424-3365ac80-1196-11eb-9224-592d32ac1ab5.PNG)
    Reading Results:
    ![Grades2](https://user-images.githubusercontent.com/71234992/96407427-33fe4300-1196-11eb-9f7f-53bdb7296306.PNG)

    * Scores by school spending
    The scores categorized by score spending before and after the change are as followed. As can be seen the category
    that was effected was the $630-644 range. These results were decreased.
    
    Original Results:
    ![Spending1](https://user-images.githubusercontent.com/71234992/96408208-dd920400-1197-11eb-8bc5-9d00e05bba82.PNG)
    Refactored Results:
    ![Spending2](https://user-images.githubusercontent.com/71234992/96408211-de2a9a80-1197-11eb-8708-0a8bf1d1c9e5.PNG)
    
    * Scores by school size
    The scores by school sized were similarly changed. The category that was manipulated was the Medium size one. As
    can be seen, the scores decreased after the change.
    
    Original Results:
    ![Size1](https://user-images.githubusercontent.com/71234992/96408441-5f822d00-1198-11eb-9c0e-f76fcbfe532f.PNG)
    Refactored Results:
    ![Size2](https://user-images.githubusercontent.com/71234992/96408443-601ac380-1198-11eb-9026-4c0662e338f2.PNG)
    
    * Scores by school type
    Finally the scores by the school type are shown to be decreased as well in the charter category. This is due to 
    the fact that THS is a charter school.
    
    Original Results:
    ![Type1](https://user-images.githubusercontent.com/71234992/96408724-efc07200-1198-11eb-8cdd-30bdcf764e86.PNG)
    Refactored Results:
    ![Type2](https://user-images.githubusercontent.com/71234992/96408726-f0590880-1198-11eb-9c1d-0b49008213a6.PNG)

## Summary
