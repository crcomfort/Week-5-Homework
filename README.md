# Week5-Homework-Assignment
## Week Five Homework Assignment R-Project

Chayson Comfort
6-12-17

## What is it?

This is an R formated data set from the file R_rollingsales_brooklyn.R that I was tasked with completing.  The source directory containing R_rollingsales_brooklyn.R is what I had to complete; There are 4 TODO comments that I had to look at and complete. My code R_rollingsales_brooklyn.R clean up the input csv data. The clean up includes finding out where there are outliers or missing values, I had to decide how to treat them, making sure values I though were numerical were being treated as such (correct R class), etc.


## Why did I make this?

This was an assignment given to me in my SMU MSDS 6306 Week 5 couse homework assignment.

## Import into R

To import the file directly into **R** simply use the `source_data` function:

```{r}
Data <- repmis::source_data(url = "http://www1.nyc.gov/home/search/index.page?search-terms=Rolling+sales+update")
```
