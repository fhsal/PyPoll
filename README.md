# PyPoll County Election Analysis

CWRU Data Analytics Module Three Challenge


## Overview of the Election Audit

The challenge involved learning about a wide range of Python functions, data structures and methods for calculations, modifying data structures, looping, conditionals reading/writing to files and formatting outputs.   These skills were used to create summary statistics from a modestly large election dataset from three counties for three candidates and ~370,000 voters. The information was created by iterating through the dataset to create totals and % for each candidate and county the overall winner.   


### Purpose

The purpose of the challenge was to exercise our skills to segment and summarize the data, identify the overall winner and the county with the largest turnout.  This information was formatted for display and written to a file for reference. created with using pandas in a variety of ways to summarize, aggregate, sort, filter, format and replace data to facilitate summary-level views of the student and school populations.  

## Analysis 

The Election analysis had four components:

(1) Reading the election data from a csv file 

(2) Producing totals and % for candidates from the data and identifying the overall winner

(3) Producing totals and % for counties from the data and identifying the county with the highest turnout

(4) Formatting the results for display and writing them to a text file 

### Analysis approach 

The analysis involved using the csv.reader module to load the file and building a list (called 'election_table') from which to work.  Then iterating through that list to create lists of Counties and Candidates which were subsequently used to create dictionaries with summary totals for Candidated and Counties.  This was done by iterating through the 'election_table' for each set of totals.   A series of 'For' loops were used to do this with each aggregate total statistic.   The higest totals for County and Candidate were identified using the 'max' function and the results were formatted for display and then also writing to the text file.     


### Summary

The results were not at all close.   

- Denver had the dominant turnout, with nearly 10x the number of voters 

- Diana DeGette won almost 74% of the vote 

![img](https://github.com/fhsal/PyPoll/blob/main/election_results.png)

### How this be re-used for other elections

The script can be re-used in future elections as none of it is 'hard coded' for this data, meaning that more candidates and/or more counties would simply flow through. 

The formatting and categories, however, would need to be updated if other stats or comparisons were sought (mean, distribution, etc.). 

### How the script iterates through the data and formats outputs 

**Loading the data:**

![img](https://github.com/fhsal/PyPoll/blob/main/loading.png)

**Pulling out the counties:**  

![img](https://github.com/fhsal/PyPoll/blob/main/pull_counties.png)

**Pulling out the candidates:**  

![img](https://github.com/fhsal/PyPoll/blob/main/pull_candidates.png)

**Totals for the counties:**

![img](https://github.com/fhsal/PyPoll/blob/main/county_counts.png)

**Totals for the candidates:**

![img](https://github.com/fhsal/PyPoll/blob/main/count_candidates.png)



**displaying results:**

![img](https://github.com/fhsal/PyPoll/blob/main/display_summary.png)

**writing results to file:**

![img](https://github.com/fhsal/PyPoll/blob/main/write_file_election_results.png)

