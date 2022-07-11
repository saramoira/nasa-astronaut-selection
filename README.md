# NASA Astronaut Selection: Exploratory Analysis

## Abstract
The goal of this project was to analyze overall trends in NASA's astronaut selection process and specifically, the 2013 applicant pool in order to motivate a recommendation for future thorough analysis and modeling of potential biases in selection. 

## Design 
In January 2022 NASA’s OIG released an [audit report](https://oig.nasa.gov/docs/IG-22-007.pdf) analyzing NASA’s current management of the Astronaut Corps. Among the major concerns listed was the current diversity of the Corps. The purpose of the proposed project is to identify biases in NASA’s selection process and to make a recommendation for changes to that process based on trends in education attainment among demographic groups in the US. I looked at the overall demographic makeup and career milestones for the current astronaut corps, as well as trends in educational attainment (specifically STEM degrees that NASA deems qualifying) among various demographic groups.  

## Data
* NASA’s [Astronaut Yearbook](https://www.kaggle.com/nasa/astronaut-yearbook): I updated this file manually with selectee information and career milestones since this yearbook was created. 
* Anonymized applicant data from the [2013](https://plos.figshare.com/articles/dataset/Analysis_of_age_as_a_factor_in_NASA_astronaut_selection_and_career_landmarks/5252974?file=8981851) astronaut applicants.   
* NCES 2020 [education attainment report](https://nces.ed.gov/programs/digest/2020menu_tables.asp) and manually requested datasets tracking the awarding of NASA-qualifying STEM degrees in the US from 2010-2020 

## Algorithms/Tools
I used Google Sheets for initial analysis and scoping of the project, and then Excel for analysis of the larger datasets (2013 applicant data and NCES records of STEM Degrees awarded from 2010-2020). The final data visualization was built using Tableau - the interactive dashboard is online here: [NASA Astronaut Selection Dashboard](https://public.tableau.com/app/profile/saramoira.shields/viz/NASAAstronautSelection/Dashboard1?publish=yes)

## Initial Findings 
The chart below shows the percentage of active women and minorities in the NASA Astronaut Corps vs the general population - the representation of these groups in the Astronaut Corps is consistently lower than the general population. 

![US Population Compared to Astronaut Selectees](https://github.com/saramoira/nasa-astronaut-selection/blob/main/images/US_Pop_vs_Astronaut.png)

Furthermore, looking at the highest degree recieved, there is a pattern of women and minorities holding a much higher degree at the time of selection. 

![NASA Astronauts: Higest Degree at Selection](https://github.com/saramoira/nasa-astronaut-selection/blob/main/images/Astronauts_Highest_Degree.png)

This initial analysis suggests that there may be some biases in the selection process that manifest as women and racial/ethnic minorities needing higher educational qualifications to be chosen. 

## Outcome
The finished dashboard allows for users to filter NASA Astronaut selectees by gender, race/ethnicity, and year of selection. Breaking out the selectees by year allows the user to compare educational attainment and major career milestones (first flight and total time in space) for the demographic populations while taking into account changes to NASA's selection policies over time. Notable insights include: 
* While NASA's selectees included more women over the years, the vast majority of those women have been white. From 1978-2021 there have been 50 women selectees (50 white women, 6 black women, 2 asian women, 2 hispanic women, and one Native American/Alaskan Indian woman). 
* Average time from selection to first flight is 6.7 years. For men the average is 5.65 years and for women the average is 7.58 years. 
* As of June 2022, two out of the six black women selectees (one selected in 1996 and one selected in 2009) have never flown to space - leading this demographic group to have both the longest average time to first flight (11.5 years) and the lowest average number of space flights (0.8). 

## Completed Dashboard
[NASA Astronaut Selection Dashboard](https://public.tableau.com/app/profile/saramoira.shields/viz/NASAAstronautSelection/Dashboard1?publish=yes)

![NASA Astronaut Selection](https://github.com/saramoira/nasa-astronaut-selection/blob/main/images/nasa-astronaut-dashboard.png)



