Assignment5 Homework

Purpose:  To store data and code related to SMU MDS "Doing Data Science" assignment5.

Topic: Import 2 raw data files of 2015 and 2016 most popular children's names in the U.S., clean, merge, analyze, and produce output file of top 10 most popular female names in 2015-2016 combined.

Files in this directory:

1) Assignment05.pdf - Homework assignment.
2) EricMcCandless_LiveSession5Assignment.Rmd - R Markdown document.
3) EricMcCandless_LiveSession5Assignment.html - corresponding html.
4) EricMcCandless_LiveSession5Assignment.htm- - corresponding markdown document.
5) itsagirl.csv - Data file of top 10 female names 2015+2016 showing name and total number of children.
6) yob2015.txt - original raw data set for names in 2015 showing name, gender, and number of children.
7) yob2016.txt - original raw data set for names in 2016 showing name, gender, and number of children.


Objects in EricMcCandless_LiveSession5Assignment.Rmd - R Markdown document.

1) df <- raw data table "yob2016." (first df refers to Q1a).
2) mispell <- mispelled name in "yob2016."
3) y2016 <- new "yob2016" table without mispelled name.
4) df <- raw data table "yob2015." (second df refers to Q2a).
5) y2015 <- new "yob2015" table.
6) final <- merged table from "y2016" and "y2015."
7) final$Total <- new column showing sum of total children in 2015 and 2016 from "final." 
8) pop_names <- list of combined "Total" top 10 most popular names in "final."
9) girl <- list of combined "Total" top 10 most popular female names in "final."


Sources: 

1) Raw data provided by Professor Tibbett.

Contact Info:

1) Eric McCandless (emccandless@SMU.edu)