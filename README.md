# Data Scientist Nanodegree (Term 2)

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I have used the data from Stack Overflow 2020 developer survey to answer the below questions:

1. What are the top languages used by the surveyed people along with the desired to be learned next year?
2. Looking at the data for languages used and desired, is it different between developers by profession and others?
3. How job seeking is compared across different segmentation?
4. Aside from compnensation, benefits and location, what factors are important when looking for a job?

## File Descriptions <a name="files"></a>

This repository contains analysis for the Stack Overflow 2020 shared relsults.
Main file run is (mok stackoverflow.ipynp) a Jupyter notebook to go over the anlysis and results genrated. 
Other files are the survey results and a python file for some of the funcions used in the notebook

## Results<a name="results"></a>

Analysis of the findings and results can be found at the post available [here](https://medium.com/@sraab2003/a-glimpse-into-the-2020-popular-programing-languages-788fe4825bb9).

Not much of the data were missing for the job seek column and the desires language and used language. Thus I felt safe in dropping the rows where these data were missing. I have used one categorical variable for the job seek, where to get better the mean of the available data I have converted them into numerical to be able to get the statistical mean of the segmentation. More explanation can be found in part III of the blog for the conversion between the job seek categorical value to a numerical one. For the language used, I have dropped the N/A values, because they do not contribute to the popular language usage. If they happen to be missing, it would mean that the respondent did not use any of them nor planning to use one in the upcoming year. 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data analyzed. Complete list of data can be fount [here](https://insights.stackoverflow.com/survey).  





