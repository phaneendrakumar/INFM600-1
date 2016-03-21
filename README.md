# INFM600
This document is created for INFM600 assignment - Information Discovery and Analysis Assignment

#Version
Version 1.0 (March 2016)

#Description
This data set has been derived from the two datasets of 2016 US Election which has the data updated till 25 Feb 2016 (https://www.kaggle.com/benhamner/2016-us-election) created by Ben Hamner. The first original data set includes county demographic information from the US Census. The second original data set includes election results of four states; South Carolina, Nevada, IOWA, New Hampshire.

From the original dataset, information that is required to answer the question "Is there a correlation between a number of educated people and the number of votes cast for both the parties (Democratic and Republic) has been maintained. This includes County, Votes, EDU685213- Bachelor's degree or higher, percent of person age 25+, 2009-2013,area_name. 

The dataset is released in the framework of INFM 600, Information Environments, and Spring 2016, at the University of Maryland iSchool, http://ischool.umd.edu/mim.

#Research question
Is there a correlation between a number of educated people and the number of votes cast for both the parties (Democratic and Republic) has been maintained

#Hypothesis
Ho: Null Hypothesis: It states that there is no correlation between the education of people and the number of votes cast in the primary election.

Ha: Alternate hypothesis: It states that there is a significant correlation between the education of the people and the number of votes cast in the primary election.

#Data statistics
State -> 4
county ->  1929
                       Min.   1st Qu.   Median    Mean      3rd Qu.    Max. 
Votes  ->              95    9904      24620      69940     73290    646400
Educated people  ->  60780   1131000   2310000   7386000    5619000 194900000

#Files
+Combinesresults.csv
 This data set is derived from merging two datasets.

+county_facts.csv
 This data set includes county demographic information from the US Census

+county_facts_dictionary.csv
 This files includes desciptive names of all the columns in county_facts files.

+primary_results.csv
 This data set includes election results of four states; South Carolina, Nevada, IOWA, New Hampshire.

#License
The data in the INFM600 repository is distributed under a Creative Commons 
Attribution-NonCommercial-ShareAlike 4.0 International License (see 
https://creativecommons.org/licenses/by-sa/4.0/legalcode).






