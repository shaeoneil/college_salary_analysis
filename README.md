# College Salary Analysis
Data Wrangling

### Description: 
Took raw data from Kaggle which compares salaries by college, region, and major. Then web scraped data from Wikipedia using RStudio on college Power 5 conferences. We then integrated these two datasets by a vertical merger within R. Performed an analysis to examine which colleges and conferences have the best salaries by using Q-Q plots, bar charts, t-tests, and ANOVA tests in RStudio. Visualized findings by using ggplot and dplyr within RStudio and summarized in a detailed written report.

## Table of Contents
- [General Information](README.md#general-information)
- [Technologies Used](README.md#technologies-used)
- [Features](README.md#features)
- [Screenshots](README.md#screenshots)
- [Project Status](README.md#project-status)
- [Contact](README.md#contact)

### General Information
Students must account for many factors when deciding where to attend college. From personal experience, proximity to home, expected tuition costs, and enrollment. Statistics and analysis can play a major role in determining how students spend their undergraduate years. One item on many students’ minds is their potential earnings their degree will provide after graduation. While the “college experience” cannot necessarily be quantified, there are data points available to offer insight on the salary students can expect to earn with a degree from a given conference and institution based on historical figures. 

In this project, we utilized salary data from academic institutions in the “Power 5” athletic conferences with varying characteristics in attempt to reveal the factors that greatly impact students’ earnings following graduation. It should be noted that the Power 5 schools do not represent the full range of academic institutions available to students but were chosen to provide a subset of the larger dataset to be analyzed.

- Purpose: The purpose of this project was to merge data in R using web scraping and a clean dataset. The second half of the project was about generating plots and interpreting them to demonstrate our understandings on the plots and tables. We did this to understand where it payed to attend college.
- Goal: The goal of this project is to examine which schools and conferences have the best outcomes from college, specifically starting median salaries and career growth. 
- Undertake: Webscraping can be very difficult and time consuming. 

### Technologies Used 
- Excel 
- R
- ANOVA
- dplyr

### Features
- Rigous webscraping
- Deep understanding of graphics


### Screenshots 

It appears that no conference has a significant advantage in terms of offering extraordinary salary growth to mid-career.

<img width="449" alt="Stacked Chart" src="https://user-images.githubusercontent.com/71461886/166580582-5abf76b6-d69d-47a1-af06-19003298b902.png">

The graph indicates that data passes the normality test and Coefficient sizes are accurate. The indication is seen by the marks rarely deviating from the line. 

<img width="404" alt="Q-Q Plot" src="https://user-images.githubusercontent.com/71461886/166582468-c328e493-e36f-4fec-a73b-e3b963e3875a.png">

Homoscedasticity of the model which checks If instances have equal variances. The plot below shows no true pattern except a slight skewness to the right! 

<img width="481" alt="Homoscedasticity Model" src="https://user-images.githubusercontent.com/71461886/166583059-907b6221-fc87-4c7b-817e-b90f984f0a3a.png">






### Project Status
- Completed

### Contact 
Shae O'Neil 
- shaeoneil26@gmail.com
