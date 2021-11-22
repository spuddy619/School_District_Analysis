# School_District_Analysis
## Purpose 

We have been tasked with searching for academic dishonesty from the file “students_complete.csv.” The school board believes that the data for Thomas High School’s 9th graders may have been altered. We will accomplish our objective by inserting NaN values for Thomas High School’s 9th grade data and running the school district analysis again. Conclusions will then be drawn by comparing the new analysis with the old analysis. There is a lot of data but there will be a focus on Thomas High School’s data.

## Results 
* [How is the district summary affected?]: Comparing the analysis with THS 9th graders with the analysis without THS 9th graders, there does not seem to be any noticeable differences. While they are not entirely the same - differences in formatting between the analyses make it difficult to be that precise - the two sets of data are quite similar. The differences in value between their respective Average Reading Score / Average Math Score / % Passing Math / % Passing Reading / % Overall Passing  are all within a single point or percentage.
<img width="766" alt="district_summary_after" src="https://user-images.githubusercontent.com/72320203/142822458-be9e3aad-277b-42d7-a846-820fb4ba7b52.PNG">
<img width="861" alt="district_summary_before" src="https://user-images.githubusercontent.com/72320203/142822511-98a48529-147a-4f64-a171-661f2d80e21d.PNG">


* [How is the school summary affected?]: Looking at the school summary dataset with THS 9th graders and the school summary dataset without THS 9th graders,  it can be concluded that the other schools were not affected by this change. Naturally, that is the case as the only data changed was data concerning Thomas High School. However, there is a noticeable difference in Thomas High School statistics. With the 9th graders included in the analysis, Thomas High School had: An average math score of 83.4, An average reading score of 83.8, 93.3% of students passing math, 97.3% of students passing reading,90.9% of students passing overall. When omitting the 9th graders, Thomas High School had: An average math score of 83.4, an average reading score of 83.9, 66.9% of students passing math, 69.7% of students passing reading, 65.1% of students passing overall. As you can tell, there is a large discrepancy in the percentage of students passing math, or reading, or both, between the two analyses. The data not considering the THS 9th graders reflects a noticeable decline in student performance.

<img width="662" alt="per_school_summary_before" src="https://user-images.githubusercontent.com/72320203/142822858-f346a9d7-d4f7-4587-8535-683eb20cf8c6.PNG">



<img width="671" alt="per_school_summary_after" src="https://user-images.githubusercontent.com/72320203/142822847-19c594d7-caf1-4180-a887-dba9e14028eb.PNG">

* [How Does Replacing the ninth-grade scores affect: Scores by school spending?]: The original analysis shows that as spending per student increases, the average grades and percentage of passing students goes down. A concise testament to this trend can be seen in the “% Overall Passing” column. At the lowest spending range the “% Overall Passing” value stands at 90 percent. Then, as the spending increases, it goes to 81 percent and then 63 percent and finally 54 percent. The analysis omitting the THS 9th graders follows a similar trend. Examining the “% Overall Passing”,  the percentage declines as the spending ranges increase.

<img width="688" alt="spending_summary_before" src="https://user-images.githubusercontent.com/72320203/142824119-1d7117df-0ed6-46a8-9822-88c504fd2a7e.PNG">


* [How Does Replacing the ninth-grade scores affect: Scores by School size?]: The original analysis shows that as school size increases, the “% Overall Passing” decreases. It begins at 90% at the smallest school size and then ends up at 58% at the largest school size. In the second analysis, there is a similar trend - At the smallest there is 90% overall passing rate and at the largest, there is a 56.6% overall passing rate.

<img width="670" alt="size_summary_before" src="https://user-images.githubusercontent.com/72320203/142824212-ef7322a5-8f29-4f1b-8b76-4e5f17a287bc.PNG">
<img width="745" alt="size_summary_after" src="https://user-images.githubusercontent.com/72320203/142824227-e71b55da-2074-481f-adaa-b4dabfa5c763.PNG">




* [How Does Replacing the ninth-grade scores affect: Scores by school type?]: These two set of data show that charter schools tend to do better than district schools. When comparing the datasets against one another, it can be seen that the dataset in which THS 9th graders were involved has better scores and percentages.

<img width="648" alt="type_summary_before" src="https://user-images.githubusercontent.com/72320203/142824479-c405ea3a-8045-4466-aa5b-08dbf1aea621.PNG">
<img width="728" alt="type_summary_after" src="https://user-images.githubusercontent.com/72320203/142824498-2d43b901-2103-48e5-945f-3999764d6fe6.PNG">



## Summary 
After replacing the reading and math scores for the ninth grade at Thomas High School, there were the following changes: 
* By taking out the 9th graders from the analysis, Thomas High School, academic performance drops noticeably, suggesting that there is academic dishonesty from the 9th grade of Thomas High School. The % passing math begins at 93% with the 9th graders but after taking them out, the percentage becomes 67%.
* The passing reading % is 97% at first but is then reduced to 70%. 
*  Overall Passing is  at 90% with the 9th graders. When taking out the 9th graders, the data drops to 65%. The effect of omitting 9th graders from Thomas High School would be most apparent in a dataset with information exclusively about the school so it seems likely that there is some academic dishonesty amongst the 9th graders of Thomas High School.
* The statistics on medium-sized schools declined when the 9th graders of THS were taken out of the analysis. This is probably due to the fact that Thomas High School was a medium-sized school. The other school sizes did not seem to have much data change. 



