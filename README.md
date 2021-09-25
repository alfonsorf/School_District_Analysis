# PyCitySchools with Pandas
For this challenge, I was responsible for creating a school district analysis using Jupyter Notebook and Pandas to prepare standardized test data for analysis, reporting, and presentation to provide insights about performance patterns. Using Python, I first cleaned data with altered results and then I created multiple dataframes showing the district and school summaries, the top and bottom performing schools, and the scores based on their spending and sizes.
## Results
After cleaning the data and performing the analysis there were a few changes in the results:
- The district summary remained virtually the same, with the math score average dropping 0.1 and the percentage results for math, reading, and overall passing were lower by 0.2%, 0.3%, and 0.1%, respectively. 
- The results for the school summary were largely the same with the exception of the math/reading averages and the passing percentages. You can see in the images below that all three percentages decreased over 25% after the 9th grade scores were removed from the calculations. 

![PyCitySchools summary](https://user-images.githubusercontent.com/88118759/134784000-afc6bd2e-28a0-4d0e-a5aa-606f4fcfb9f4.PNG)
The first image is the dataframe with the original data, for reference.

![PyCitySchools challenge summary](https://user-images.githubusercontent.com/88118759/134784003-50d4dc03-2161-42d4-82c0-ce25fc2a083a.PNG)

- Replacing the 9th grade math and reading scores does not change too much in comparison to the other schools in the district, as Thomas High School is still ranked in second place. The averages for both categories are lower, but only by less than 0.1% so this change is not very significant.
- Comparing the math and reading scores by grade after removing the 9th grade scores makes no change to the data other than having no results in the 9th grade THS cell. All other scores by grade and school remained the same.
- By replacing the 9th grade results, the scores by school spending changed the two middle bin results, $585-629 and $630-644, and brought both of the averages and all the passing percentages up. 
- Replacing the 9th grade results made no changes to the final two dataframes, scores by school size and scores by school type. All averages and percentages were the same.
## Summary
The first of the major changes to this analysis was replacing the math and reading scores for the 9th grade Thomas High School students but doing so returned a few others worth noting. The district passing percentages were lowered but by negligible amounts. The school summary was the most affected as the passing percentages for THS were significantly decreased after the new calculations, and lastly the scores grouped by school spending were the most affected having seen improvement in the averages and percentages of passing students. Overall, these changes were pretty significant mainly in the passing percentages of Thomas High School, it would be advisable to have these tests retaken as the results could impact the budget decisions significantly.
