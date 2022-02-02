# NASA Astronaut Selection Analysis


## Question/need:
### What is the framing question of your analysis, or the purpose of the model/system you plan to build?

In January 2022 NASA’s OIG released an [audit report](https://oig.nasa.gov/docs/IG-22-007.pdf) analyzing NASA’s current management of the of the Astronaut Corps. Among the major concerns listed was the current diversity of the Corps. The purpose of the proposed project is to identify biases in NASA’s selection process and to make a recommendation for changes to that process based on trends in education attainment among demographic groups in the US.

### Who benefits from exploring this question or building this model/system?

NASA’s Astronaut Office, the Artemis program, future NASA astronaut applicants

## Data Description:
### What dataset(s) do you plan to use, and how will you obtain the data?

* NASA’s [Astronaut Yearbook](https://www.kaggle.com/nasa/astronaut-yearbook)
* Anonymized applicant data from the [2009](https://plos.figshare.com/articles/dataset/Analysis_of_age_as_a_factor_in_NASA_astronaut_selection_and_career_landmarks/5252974?file=898183) and [2013](https://plos.figshare.com/articles/dataset/Analysis_of_age_as_a_factor_in_NASA_astronaut_selection_and_career_landmarks/5252974?file=8981851) minimum-qualified astronaut applicants  
* NCES 2020 [education attainment report](https://nces.ed.gov/programs/digest/2020menu_tables.asp)

### What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?

* For the NASA applicant and astronaut corps data, an individual sample is one person/applicant, along with age, gender, degree status, and status as a NASA-defined minority

* For the NCES data, an individual sample is degree type and title, broken down by year awarded and numbers awarded by gender and race. 

### If modeling, what will you predict as your target?

To identify bias I will do exploratory analysis of the above datasets to identify trends. I will also propose a model to predict the effect of factors such as age, gender, degree attainment and race on designation by NASA as “Highly Qualified” during the application process.

## Tools:
### How do you intend to meet the tools requirement of the project?

I plan to use Google Sheets for basic data exploration, scikit-learn for initial regression model, and Tableau for visualization. 

### Are you planning in advance to need or use additional tools beyond those required?

I am not currently planning to use additional tools.

## MVP Goal:
### What would a minimum viable product (MVP) look like for this project?

A chart detailing areas of concern - for example, demographics over- and under-represented in NASA’s Astronaut Corps compared to the general population.
