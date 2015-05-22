Getting-and-Cleaning-Data_Course-Project
This repository contains all of the deliverables for the Getting and Cleaning Data Course Project.

How this script works:

Unzip the dataset zip fiile into a folder on your local drive, i.e. C:\Users\yourname\Documents\R\

Place your run_analysis.R file into C:\Users\yourname\Documents\R\UCI HAR Dataset\

In RStudio: setwd("C:\Users\yourname\Documents\R\UCI HAR Dataset\"), followed by: source("run_analysis.R")

Enter the following to view the data:

data <- read.table("tidy_data_set.txt")
