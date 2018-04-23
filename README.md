# Analyzing NYC High School Data using Python
## Dataset Information
New York City has published data on student SAT scores by high school, along with additional demographic data sets.
* SAT scores by school - SAT scores for each high school in New York City
* School attendance - Attendance information for each school in New York City
* Class size - Information on class size for each school
* AP test results - Advanced Placement (AP) exam results for each high school (passing an optional AP exam in a particular subject can earn a student college credit in that subject)
* Graduation outcomes - The percentage of students who graduated, and other outcome information
* Demographics - Demographic information for each school
* School survey - Surveys of parents, teachers, and students at each school
## Analysis Info
* Combined the following data sets into a single, clean pandas dataframe
* Understood the correlations between SAT scores and various features like average class sizeby plotting a bar plot of the correlations between these fields and SAT score.
* Computed the average safety score for each district and plotted a map that shows safety scores by district in NYC. How students and teachers perceived safety correlate with SAT scores. This make sense, as it's hard to teach or learn in an unsafe environment.
* Investigated the effect of racial percentage in schools with the SAT by measuring the correlations between the race percentage and SAT score. High White and Asian percentages indicated high SAT scores while high Black and Hispanic percentages indicated low SAT scores. This may be due to a lack of funding for schools in certain areas, which are more likely to have a higher percentage of black or Hispanic students.
* Analyzed the effect of gender on SAT scores. a high percentage of females at a school positively correlates with SAT score, whereas a high percentage of males at a school negatively correlates with SAT score.
## Python Libraries
* Pandas
* Numpy
* re
* Matplotlib
* Seaborn
* mpl_toolkits.basemap - Basemap
