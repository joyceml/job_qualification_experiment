## An experiment on whether FaceTune virtual face filters have an effect on the perception of job qualification

Created by Joyce Li, Meer Wu, and Amy Jung for our MIDS Data W241 final project

## Repository Files

1. **Job Qualification Experiment Report.pdf**
    - Explains experiment background, motivation, methods, results, and conclusions
    - Final paper for MIDS W241 course
2. **regression.Rmd**
    -  Final statistical analysis regressions on both final datasets (drop and no drop)
    -  Covariate balance check done for randomization
    -  Calculate AMCE and ATE's for each individual feature
3. **subset.Rmd**
    - Statistical analysis on subsets of data (female vs. male, front-facing roles vs. back-facing roles)
4. **final_dataset.csv** 
    - Final dataset for regression analysis, dropped all survey questions where respondent indicated that one or more pictures were missing
5. **final_dataset_no_drop.csv**
    - Final dataset for regression analysis, only dropping respondents where no pictures appeared in the survey at all

## Additional Folders
1. data prep
    - Contains original data reformatting and data cleaning notebooks before final analysis
2. archive
    - Contains data files that were not used in final analysis
