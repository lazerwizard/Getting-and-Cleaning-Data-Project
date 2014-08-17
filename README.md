Getting-and-Cleaning-Data-Project
=================================

#first, download the data:

url <- "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip" 
download.file(url=url, destfile="data", method="curl")
unzip(zipfile="data")

#the run_analysis.R script in this repo will clean and elegantly present the above set of data.
