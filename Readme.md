For our groups project, we examined data from the CDC(https://catalog.data.gov/dataset/vsrr-provisional-drug-overdose-death-counts) and Rutgers to investigate the nationwide issue of drug overdose deaths. We wanted to understand if there truly is an opioid crisis occuring in our country and if there are any socioeconomic factors that contribute negativly or decrease the amount of OD deaths state/nation wide. 

#Question 1: Which drugs are the most lethal.

1 Opioids
2 Pscyho Stimulants
3 Cocaine 
4 Herion
5 Methadone

After downloading the data from the CDC our teams first steps were to understand what data was represented in the file.  We explored which drugs, states and years were used in the data set, then filtered our new data sets down to contain only the values we wanted. We removed blank values and reorganized our data so it was clearer to understand. Finally we made graphs depicting the key findings of the data set.


#Question:is there an opiod crisis in the US?

For my second graph I filtered for deaths from only the top four lethal drugs and compared them over time.
From this we found that Opiods were responsible for over 800kdeaths while the next most lethal drugs Psycho stimulants had only 400k
The reamining three drugs which were all opiods had less that 300k deaths with heroin use decreasing over time.
From this we can conclude that with an upward treading reaching numbers twice and great as the next drug on the list, there is an opiod crisis in the country


Question #2 

#Question: How many drug overdoses are there in the U.S. and which state has the highest death count?
Using the VSRR dataset we got from the CDC, I filtered the dataset to eliminate the columns that were unnecessary and only contain the overall US statistics for all years included in the data, 2015-2022. I created summed totals for all years and defined a function to calculate the percentage increase among the years, I then proceeded to graph my findings using a bar graph titled: 'Number of Total Drug Overdose Deaths in the US' .  My conclusion for this graph is that from 2015 up until 2022 there has been an overall increase of drug overdose deaths in the U.S. by about 113.86% . There was a moment in between these years from 2017-2019 when the overall deaths remained almost the same with there even being a small decrease in 2019 of 0.43%. We see the biggest jump in overdose deaths in between 2020 and 2021 with a total of 221,145 deaths or an increase of 22.21%

For my second visualization Titled: 'Top 5 States : Most Drug Overdose Deaths in the past 3 years', I visualized data from the same VSRR dataset from the CDC but this time filtered the dataset to contain statistics for each state and only using the past 3 years, 2020-2022. The reason for only this is to visualize the most recent data and also because those years had the most deaths as shown in my first visualization. I summed up the totals and calculated the average per state and discovered the following conclusions.
The top 5 states with the most overdose deaths combined for all three years are as follows:

1. California : 356,691 Deaths
2. Florida : 272,273 Deaths
3. Pennsylvania: 186,224 Deaths
4. Ohio: 184,468 Deaths
5. Texas: 161,322 Deaths

The average combined overdose death count for all states is 22,296 Deaths


#Question 3
The final factor our group analyzed brought in another dataset from schoolfundingfairness.org and compared Federal and State Funding to drug overdoses. To look at this, we first cleaned the new dataset and created a statistic standardized based off the number of students in the district. Our predicotr was the Mean of (Federal Funding + State Funding/ # of students). We grouped this information by state and merged the dataset with the original Drug Overdose information to perform our analysis. Both graphs indicated a minor correlation and if anything this correlation showed positive indicating higher educational funding would predict drug overdoses. For this reason it is safe to say with a basic linear regression test that there is no correlation between these two variables. Correlation statisics showed as 0.07 and 0.09 respectively.



Through our examninations, we were able to conclude several findings:
1. Based on our data , the number of overdoses per year has significantly increased since 2015.
2. Opioids account for the vast majority of overdose deaths in the US and the number of deaths have increased dramatically starting in 2019. This is evidience of a crisis.
3. There seems to be no correlation between school funding an drugoverdose deaths. 


