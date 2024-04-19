# Project-1-Team-4
# Submission Details

Please refer to the file "FINAL SUBMISSIONS" and the readme in there for the file(s) we would like graded

Background:
• Dates: Crime data has been collected from the official Los Angeles City website using APIs. The dataframe time period is from Feb 10, 2024 to Mar 31 , 2024.
• Data size: More than 900,000 rows are present in the dataset, collecting over 4 years of crime history from L.A.
• COVID-19 official start date in California is Mar 11, 2020, when the first death for Coronavirus was reported. (1)
• COVID-19 official end date in California is Mar 31, 2023, according to the news. (2)
• Crime definition: According to Criminal Justice Information Services, there are 8 main offenses classifications: - Criminal Homicide - Rape, - Robery, - Assault, - Burglary, - Larceny/Theft, - Motor-vehicle theft and Arson. (3)
• Violent definition: Homicide, Rape, Robbery, Aggravated assaults, Simple assault. (4)
• Theft of property: Not considered a violent crime as per Los Angeles City definition, but considered in our study to prove increase on cyber crimes.
Assumptions:
• The increase in crime and violence were linked to the changes in COVID restrictions.
• Assumed 100% accuracy wehn original crimes on paper were transcribed to digital.
• Assumed crimes were reported to the nearlest police station.

Hypothesis:
As COVID-19 restrictions eased, violent crime in L.A. increased in numbers.
Null hypothesis:
As COVID-19 restrictions eased, violent crime in L.A. did not increase in numbers.

Research question:
How did COVID-19 affect crime metrics in Los Angeles?

Sub-questions:
1. Did COVID-19 restrictions affect some areas of Los Angeles more than others? Time versus geographical areas + in comparison with total crime/milestone - Yumai Situ
2. Did COVID-19 restrictions influence the type of crimes committed? Time versus type of crime (looking for distribution of crimes) - Vaibhav Singh
3. Did COVID-19 restrictions influence amount of violent crimes as restrictions eased (looking for trends in nature of crime) - Laura Roa
4. Did COVID-19 restrictions affect some victims more than others?.Time versus gender (looking for distribution of crimes) - Brendan Helou

Major findings:

Total crime increased with respect to COVID19 Milestones (elevated crime count persisted post COVID19 restriction end), with the trend apparent when subcategories of top5 Areas with most Crime and top5 Areas with least Crime were analyzed with respect to COVID19 Milestone as well. All three analyses displayed significance. 
Vehicle Stolen as number 1 crime in L.A. within the past 4 years, representing almost 11% of total.
Simple assaults increased as COVID restrictions eased by steady 12%.
Theft of identity increased by 17% since COVID restrictions began.
As COVID restrictions lessened, crime against minors increased.

Conclusions:
The data shows a gradual overall increase in crime.
Crime rate stayed elevated 1 year post COVID SOE end.
Preiminary statistical data was completed through both visualization of boxplot (for identification of outliers present in Q3 and Q4, correlated with vacation months) and histogram/scatter plots for normality and assessment for ANOVA assumptions. One-sided ANOVA was performed for the total crime, top5 most crime areas and top5 least crime areas, revealing significance of p<0.05 for all three assessed datasets. Total Crime x COVID Milestones had a p-value = 6.36e-14, Top5 Most LA Crime areas Crime Count x COVID Milestones and Top5 Least LA Crime areas Crime Count x COVID Milestones had p-value = 1.25e-15 and 1.92e-08, respectively. Considering the significance observed, the sub question (1)  null hypothesis can be rejected, supporting the hypothesis that there is interaction between COVID restriction stage and crime count. The answer to sub question 1 supports further analysis into the other sub questions and establishment of their statistics in order to better support or reject our main hypothesis. We can, at the moment, conclude only on the impact of Covid Milestone phase on crime, but cannot specifically validate negative/positive correlation and crime type/victim metrics. We have visualized trends that suggest data analysis into violent crime such as simple assaults and metrics such as age would be of interest, and further statistical analysis is pending to fully reject or accept our main hypothesis. 

Sources:
(1) https://www.nbclosangeles.com/news/coronavirus/2020-2021-california-coronavirus-pandemic-timeline-key-events/2334100/
(2) https://www.latimes.com/california/story/2023-03-31/l-a-county-ends-covid-19-emergency
(3) https://lao.ca.gov/1995/010195_calguide/cgcj1.html
(4) https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data 
