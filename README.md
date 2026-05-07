# Risk Analysis of Natural Hazards 
#### Civil Engineering Analysis II 
#### Section 151 Group INFRA-02-15 
#### Carter Janssen, Alex Throener, Isaiah Jones
#### May 8, 2026
#

## Overview

#### Introduction

Our group analyzed tornado risk across six selected states using NRI data, developed summary plots highlighting regional trends, evaluated how hazard risk relates to population exposure and Social Vulnerability Index metrics, interpreted whether regional trends exist, and discussed ethical considerations and bias in coding decisions during analysis. For this analysis, our group examined the following states: Nebraska, Iowa, Kansas, Missourri, Oklahoma, Arkansas. We used the NRI Census Tracts dataset to base our data geographically. We also used data from FEMA on tornadoes since 1950 in the United States. 

#### Meathods
We first loaded the NRI census tracts data is loaded into Python and separated it into each state we are analyzing. Then we graphed the annual expected cost of building damage and annual loss with population for tornadoes in each state. We plotted how the number of significant tornadoes has changed by decade for each state, and the proportion that each state contributes to the regional total of tornadoes. To analyze a shift in tornado alley, we divided the states into west and east. We then plotted the number of significant tornadoes for each side going back to 1950 and also focusing on the most recent trends.

#### Results
Overall, the data showed Nebraska and Kansas are the most at risk of community damage according to the NRI definition. However, Oklahoma historically has recorded the most tornadoes. For eastern vs. Western states, we did find a significant trend that shows tornadoes decreasing in frequency in the west, while increasing in the east.

#### Conclusion
These results support the possibility of an eastward shift in tornado activity across the selected region. This means that eastern states may need increased investment in tornado warning systems, emergency response planning, and building resilience. This trend may be due to a natural cycle of tornado alley shift, or the result of climate change. However, the results also show that tornado risk differs depending on how risk is measured, so risk should be evaluated using both hazard frequency and exposure-based loss metrics. Also, due to the NRI using a long-term average from 1950 to the present, replacing its annualized frequency calculation with a 25-year average would better reflect current tornado risk and help distribute mitigation funding more fairly.



#
## Repository Contents

-(RAW Files): The raw data files used in the Python code file for each of our identified states at the Census Tract Level and rthe metadate from the NRI website.

-(CIVE202_Spring 2026_INFRA-02-15_Project 5_Python Code.ipynb): Python code 

-(CIVE202_Spring 2026_INFRA-02-15_Project 5_ACD.docx): Includes a line-by-line explanation of code.

-[Gantt Chart](CIVE202_Spring2026_GroupINFRA-02-15_Project5_GanttChart.xlsx) : Contains Gantt Chart table with project plans and work time frames. 

-[Scope of Work](CIVE202_Spring2026_GroupINFRA-02-15_Project5_SOW.docx) : Contains Scope of Work outlining project's goals and defines the tasks to conducting our risk analysis study.

-[Written Report](CIVE202_Spring2026_GroupINFRA-02-15_Project5_Report.docx) : Written report including Scope of Work, Technical and Non-Technical Summaries, Analysis of Bias, and Results and Discussion

-[Timesheet](CIVE202_Spring2026_GroupINFRA-02-15_Project5_Timesheet.xlsx) : Contains Engineer Timesheet showing time, date and tasks worked on by each team member as well as compensation. 

#
## User Guide
1. Open attached Python Code 
2. Download required libraries:Numpy, Pandas, Seaborn, Matplotlib, Geopandas
3. Download all .csv data files and make sure they are in the same folder as the project code
4. Run each section in order
5. The notebook should display all graphs from the analysis





