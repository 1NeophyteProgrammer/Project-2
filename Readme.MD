 + # Getting and Cleaning Data, Peer Assessment Project
  
 - Peer Assessment Project for Coursera Course: Getting and Cleaning Data
 + ## <u>Creating a Tidy data set</u>
 + To repeat the work done in this project:
 
 + * 1. Download source data from http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
 + * 2. Unzip to your working directory
 + * 3. Execute the script run_analysis.R from that directory.

 + ## <u>The Steps</u>
 + The bulk of the steps done by the script involve loading the data provided from the source, and tidying this into a single data frame containing just the original data cells of interest, in the desired format.  Only the final major step computes a new result from the tidied data, writing out subject ids, activites, and mean of all measures of interest.
 
 + ### First
 + Get feature names and subset to only those features of mean or std measures
 
 + ### Second
 + Get the train and test feature sets and subset only the desired features
 
 + ### Third
 + Combine the two datasets into 1
 
 + ### Fourth
 + Attach column names to features
 
 + ### Fifth
 + Read and combine the train and test activity codes
 
 + ### Next
 + Get activity labels and attach to activity codes
 
 + ### After that
 + Get and combine the train and test subject ids
 
 + ### Then
 + Combine and name subjects and activity names
 
 + ### Lastly
 + Combine with measures of interest for finished desired data frame
 
 + ### And Compute New Result
 + From the set produced for analysis, compute and report means of all measures, grouped by subject_id and by activity.
