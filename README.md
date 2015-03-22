# Creation of a Tidy Data Set using Data collected from Accelerometers in Samsung Galaxy S smartphone

Purpose: Demonstrate ability to collect, work with, and clean a data set
------------------------------------------------------------------------
Goal: Prepare a tidy data set for analysis - using data referred to in the References link below
-------------------------------------------------------------------------------------------------
### Pre-Requisites:
  * Samsung Data Set from the link below that is unzipped into a directory called "UCI HAR Dataset" under the working directory

### Run Instructions:
  1. Unizip data files in working directory
  2. Copy run_analysis.R into working directory
  3. Source run_analysis.R
  4. The code creates a tidy data set called "tidydata.txt" in working directory
  5. Read the tidy data into a dataframe using data <- read.table("tidydata.txt", header = TRUE)
  6. View the data using View(data)

### References
  1. Data Set: [link] (http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
  2. The linked data represents data collected from the accelerometers from the Samsung Galaxy S smartphone
  3. FAQ: [David's personal course project FAQ] (https://class.coursera.org/getdata-012/forum/thread?thread_id=9) 

