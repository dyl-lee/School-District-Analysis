# School-District-Analysis

## Overview
Evidence of academic dishonesty in standardized testing scores of ninth grade students in Thomas High School has prompted a reassessment of the school district's performance as a whole. In order to determine the extent of academic dishonesty, the analysis of the school district's performance was repeated after the math and reading scores of ninth grade Thomas High school students were removed from analysis. 

### Resources
Data sources: 
* [clean_students_complete.csv](Resources/clean_students_complete.csv)
* [students_complete.csv](Resources/students_complete.csv)
* [school_complete.csv](Resources/school_complete.csv) <!--link the CSVs after uploading-->

Software:
* Python 3.7.10
* Jupyter Notebook
* Anaconda
* Visual Studio Code 1.62.3

## Results
Seven school district metrics were produced initially, and have been reproduced to compare how performances were affected by the ninth grade Thomas High School scores below.

### 1. Changes to the district summary metric were contained to Thomas High School
After reanalysis, Thomas High School saw decrease in all areas of performance: average math and reading scores, percentage of students passing math and reading as well as percentage of students passing both math and reading. However, the magnitude of the difference between the original and reanalyzed figures is very minimal (at most 0.31% as seen in % overall passing numbers), indicating that the ninth grade scores of Thomas High School were close enough to the school's average that removing them did not affect the overall school's performance numbers in a significant way.
<details>
<summary>District Summary Comparison</summary>
  Reanalyzed
<img src="Resources/images/district_summary_reanalyzed.png"> 
  Original
<img src="Resources/images/district_summary_original.png"> 
</details>



### 2. School summary 
Per conditions of reanalysis, math and reading scores were removed for 9th grade students from Thomas High School and replaced with "NaN".
  <details>
  <summary>School Summary Comparison for Thomas High School</summary>
    Reanalyzed
  <img src="Resources/images/THS_school_summary_reanalyzed.png"> 
    Original
  <img src="Resources/images/THS_school_summary_original.png"> 
  </details>


### 3. Replacing Thomas High School ninth grade scores did not affect the school's performance relative to the other schools in the district.
  <details>
  <summary>District Summary Comparison</summary>
    Reanalyzed
  <img src="Resources/images/district_summary_reanalyzed.png"> 
    Original
  <img src="Resources/images/district_summary_original.png"> 
  </details>
4. Average Math and Reading Scores by grade level
  <details>
  <summary>District Summary Comparison</summary>
    Reanalyzed
  <img src="Resources/images/district_summary_reanalyzed.png"> 
    Original
  <img src="Resources/images/district_summary_original.png"> 
  </details>
5. Average Math and Reading Scores by school size
  <details>
  <summary>District Summary Comparison</summary>
    Reanalyzed
  <img src="Resources/images/district_summary_reanalyzed.png"> 
    Original
  <img src="Resources/images/district_summary_original.png"> 
  </details>
6. Average Math and Reading Scores by spending
  <details>
  <summary>District Summary Comparison</summary>
    Reanalyzed
  <img src="Resources/images/district_summary_reanalyzed.png"> 
    Original
  <img src="Resources/images/district_summary_original.png"> 
  </details>
7. Average Math and Reading Scores by school type
  <details>
  <summary>District Summary Comparison</summary>
    Reanalyzed
  <img src="Resources/images/district_summary_reanalyzed.png"> 
    Original
  <img src="Resources/images/district_summary_original.png"> 
  </details>

## Summary
