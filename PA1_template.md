# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

The first step of this report is loading and preprocessing the "activity" dataset. We load the dataset with the following R code.

```r
data <- read.csv("activity.csv")
str(data)
```

```
## 'data.frame':	17568 obs. of  3 variables:
##  $ steps   : int  NA NA NA NA NA NA NA NA NA NA ...
##  $ date    : Factor w/ 61 levels "2012-10-01","2012-10-02",..: 1 1 1 1 1 1 1 1 1 1 ...
##  $ interval: int  0 5 10 15 20 25 30 35 40 45 ...
```
Note that steps and interval columns have the correct "int" type and the date column is a factor. No preprocessing is needed.

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
