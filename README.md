# (Ford_GoBike_Trip_data_Exploration)
## by (Kommomo Usang)


## Dataset

> This initial dataset contains data associated with approximately 184,000 individual rides made in a bike-sharing system covering the greater San Francisco Bay area in the month of February 2019. The dataset was downloaded from the url- https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv. My goal was to investigate this dataset, analyze, explore, visualize and communicate findings associated with what factors determine the duration of a trip. I performed some preliminary wrangling on the dataset -where i studied the variables and picked out 5 variables i believe were relevant to answering my goal question. member age, member gender, user type, start hour of the day and start day of the week. Furthermore, The dataset initially contained 183,412 entries with 16 features but in the course of assessing the data, i discovered some data quality issues like incorrect data type, missing values, long column names, and a lot of extraneous columns that required cleaning. At the end of my cleaning process, i had 174,952 entries and 15 columns to work with. The cleaned dataset was saved as a new file called ford-gobiketrip_master.csv which i used for my Exploratory Data Analysis. 


## Summary of Findings

> In the course of my exploration,i made a lot of findings for which i will be discussing here. One notable discovery is about the distribution of the duration variable, when plotted on a standard scaled plot would not reveal many interesting insights about the variable, to get better and clearer insights, it had to be plotted on a logarithimic scale.
> The second finding i made is on the relationship between age and duration of a trip. I found out that age is a strong determinant factor in the determination of the duration of a trip. Furthermore, a particular age group, ranging from about 20 years of age up to about 40 years are the most agile and energectic set and so my exploration showed that this age group took the shortest time to complete trips
> Thirdly, i found out about the relationship between duration and gender. The Male gender has a higher likelihood of completing trips in the shortest time possible 
> Fourthly, I also observed a strong correlation between the usertype and the duration. Subscribers are more likely to complete trips in the shortest time possible. This makes sense as they are frequent riders on the Ford GoBike system community
> Initially, i had thought that the start hour of the day and the start weekday would be a determinant to the duration of the trip, which was why i choosed them as part of my investigations. I had felt that trips taken at the start of the day when it was still cool would be completed faster, i had also felt that more trips would be completed on weekends. However, in the course of my exploration, i discovered that it was not the case with these 2 variables and their correlation plots with duration were inconsistent and so i had to discontinue investigations with them
> I also discovered that a combination of 2 predictor variables made a great pair in determining the duration of a trip

## Key Insights for Presentation

> The key insights i would focus on for my Presentation are those that have to do with the strongest interactions which were between the member's age variable, member's gender and user type as they influence duration. The relationships are depicted below-

- Distribution of Duration
- Distribution of Age
- Interactions between Duration and Age
- Interactions betweeen Duration and User type
- Correlation between Duration and Age by User type
- Correlation between Duration and Age by Gender

> During my bivariate exploration, i made use of plot matrices to plot an overview of my numeric variables against each other, my categorical variables against the numeric variables and my categorical variables against each other.
For my multivariate exploration, i made use of a non-positional encoding- color for my third variable.

> I also employed the Question-Visualization-Observation approach in recording the flow of my exploration and made use of appropriate plots for each visualization. My exploration contained barcharts, histogram, piecharts and donot plot, scatter plots, heatmaps, violin & box plots, clustered bar chart etc.
