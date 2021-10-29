# Federal Funding vs Student Achievement

![education.jpeg](https://github.com/trangbt278/education/blob/main/readme_images/Education.jpeg)

# Background

Our team conducted an exploratory data analysis on data we acquired from the National Assessment of Educational Progress. The NAEP is an organization that measures what U.S. students know and can do in various subjects across the nation, in each individual state. This assessment is given every two years and is given to a representative sample of students across the country. For our research purposes, we narrowed down the data and looked at average reading and math scores across each of the 50 states during the 2015 testing year. The following information provides our insights and conclusions on what we found.

* NAEP Website: https://nces.ed.gov/nationsreportcard/about/
* Data sources: https://www.kaggle.com/noriuk/us-educational-finances?select=states.csv

# Research Questions

Before analyzing the data, we posed two questions we hoped to answer:
1. Does the amount of federal funding provided to each state result in higher average test scores among students?
2. Does the amount of instructional expenditure per student result in higher average test scores among students?

# Summary of Findings
 
Through our exploratory data analysis, we set out to find if there was a correlation between federal funding and student achievement. Our analysis looked at the relationships between several different factors, and ultimately we concluded that there is no statistically significant relationship between the amount of federal funding received by a state and student achievement within that state. 

The first relationship we wanted to visualize was the amount of federal funding versus the amount of instructional expenditure per student. The following graph visualizes that relationship. A few important observations to note are that the District of Columbia has the highest federal funding out of the 50 states, but they only allocate about 40% of that funding to instructional spending for students. In addition, New York has the highest amount of instructional expenditure per student, but as we discovered later in our analysis, they did not score in the top 5 states for average reading and math scores, which would be expected if a relationship between funding and student achievement was present. These findings led us to conclude that a relationship between funding and student achievement was not evident, but we did further statistical analysis to confirm our hypothesis.

![H_State_Total_Rev.png](https://github.com/trangbt278/education/blob/main/readme_images/H_State_Total_Rev.png)

The next relationship we analyzed and visualized was the relationship between average reading and math scores and the amount of instructional expenditure per student per state. Massachusetts, New Hampshire, Minnesota, New Jersey and Vermont were the top 5 performing states for math, but only New Jersey and Vermont were among the top 5 states for highest instructional expenditure per student. New Mexico, Mississippi, Louisiana, Alabama, and District of Columbia were the bottom 5 performing states, and as noted above, District of Columbia was the state with the highest federal funding out of all 50 states, but it is the worst performing state based on math scores.

![Math_combine.png](https://github.com/trangbt278/education/blob/main/readme_images/Math_combine.png)

For reading scores, New Hampshire, Massachusetts, Vermont, Connecticut, and New Jersey were the top 5 performing states and Hawaii, Louisiana, New Mexico, Mississippi, and District of Columbia were the bottom 5 performing states. Again, we are seeing that there is not strong evidence of a correlation between instructional expenditure and student achievement. 

![Reading_combine.png](https://github.com/trangbt278/education/blob/main/readme_images/Reading_combine.png)

Finally, we ran statistical testing between the aforementioned relationships in order to quantify the results we were observing. In each scatter plot below, the p-values were consistently above 0.05, which indicates that there is no statistically significant relationship between the variables being analyzed. However, upon running a linear regression on the relationship between average test scores across every year the test had been given (this data set included 12 years) and the instructional expenditure per student per state for that year, there appeared to be some statistical significance between the variables. The p-values of both relationships were very near zero, which is below our selected alpha of 0.05. Because of this finding, we started to consider other opportunities for further research that could help us explain what we were seeing in our data.

![Reg_2015_Exp_Math.png](https://github.com/trangbt278/education/blob/main/Output_images/Reg_2015_Exp_Math.png)

![Reg_2015_Exp_Read.png](https://github.com/trangbt278/education/blob/main/Output_images/Reg_2015_Exp_Read.png)

![Reg_All_Exp_Math.png](https://github.com/trangbt278/education/blob/main/Output_images/Reg_All_Exp_Math.png)

![Reg_All_Exp_Read.png](https://github.com/trangbt278/education/blob/main/Output_images/Reg_All_Exp_Read.png)

# Implications of Further Analysis

Our analysis provided us with enough evidence to safely conclude that there is no apparent correlation between federal funding or instructional expenditure and student achievement, however, we do suggest further analysis be conducted in order to assess some of the interesting relationships noted above. We think it would be important to look at the allocation of funding within each individual state to see if there is another factor that could be resulting in higher or lower test scores. Additionally, further breakdown of the average test scores based on demographics like race, gender, or socioeconomic status could lead to some interesting conclusions. Finally, the NAEP assessment is given every two years, which could leave some gaps in our data. A more robust data set of average test scores collected every year could lead to a clearer understanding of the relationship, if any, between these two variables.

Further analysis across these variables could lead to individual states and individual school districts making more informed decisions about the allocation of their funds in order to support and improve student achievement. Based on our findings, increasing instructional spending per student is not equating to higher average test scores. Because of this information, school districts and states can take a closer look at the factors that contribute to student achievement and start to implement the changes necessary to make that happen. Some potential further research questions could be related to the impact of teacher turnover on student achievement, or the impact of student socioeconomic status on performance. Overall, a more in depth analysis of the multiple factors that impact student achievement could lead to states and individual schools making better decisions that result in higher test scores, and ideally more well rounded students.



