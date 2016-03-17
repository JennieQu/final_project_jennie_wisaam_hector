# final_project_jennie_wisaam_hector

We Re-analyzed Krivo and Peterson’s Extremely Disadvantaged Neighborhoods and Urban which dealt with two main hypotheses: extremely disadvantaged neighborhoods have unusually high rates of crime and local structural disadvantage is equally important in influencing crime in black and white neighborhoods. They examined crime rate in predominantly black and predominantly white high poverty neighborhoods in Columbus, Ohio. They found that race effects tend to be smaller than effects of disadvantage and that extreme disadvantage results in higher levels of violent crimes.

We collected data on crime rate, SES, and educational attainment for Chicago from the Chicago Data Portal and American Fact Finder. Grouping community areas into extreme (65-100 hardship index) and mid (20-65 hardship index). 

Before we could run the regressions, we ran pre-analyses on our data to see what we’re working with. First, we had to find out how census tracts work so we could merge the data using the block id’s and the census tracts. Then we needed to see if we could find identical numbers of highly disadvantaged community areas of predominantly white and predominantly black. Unfortunately, there were 14 predominantly black highly disadvantaged community areas, and 0 predominantly white highly disadvantaged community areas. Therefore, we tested to see if there was an equal amount of black and white community areas in the mid range poverty (hardship index 0-65). We found 11 black and 11 white community areas in this range, and so we decided to run the regression using these groups.
![alt tag](https://raw.githubusercontent.com/JennieQu/final_project_jennie_wisaam_hector/master/maps.png)

This analysis requires to have comparable counts of community areas facing similar hardship or poverty, a feature that was not present in the Chicago considering neighborhoods facing extreme poverty. Our analysis could then only be justified among community areas in neighborhoods facing mid levels of poverty as measured by the hardship index. 

Results:
A positive relationship between the hardship index and crime were observed.
![alt tag](https://raw.githubusercontent.com/JennieQu/final_project_jennie_wisaam_hector/master/crime_hardship_graph.png)

However, because of the limitations in finding a comparable count of white neighborhoods with extreme poverty we can only make inference about neighborhood in mid-range poverty levels. We observed a significant effect of hardship on crime experience in mid-range disadvantaged community areas, but the effect is very small effect, explaining only 51% of the general model. 

![alt tag](https://raw.githubusercontent.com/JennieQu/final_project_jennie_wisaam_hector/master/OLS_Mid_range_crime_and%3Dhardship.png)
