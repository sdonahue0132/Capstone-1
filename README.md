Capstone 1:  Data Science and Retirement Planning 

README


Introduction:  
This is a project completed as a part of Springboard’s Data Science Career Track program, 
inspired by Tony Robbins’ award winning book, Money: Mastering the Game.  The objective is 
to use data science tools (python, EDA, Statistics, and ML) to understand the analyses that 
support one of the book’s flagship investment strategies:  the All Weather Portfolio.


Data Sources:
Data was obtained from Yahoo Finance via an ordinary download, since their API was discontinued in 2017.  
Funds representing each of the diverse categories of the portfolio were determined by author research.


How this project is structured:
Raw data is separated from csv files generated by the ipython notebooks.
Ipython notebooks are grouped by the phase of the project to which they belong.
Reports are the author’s conclusions, featuring text, graphs from the notebooks, and commentary.

To view the work in the order it is generated, please look to the following guide.

1) EDA + Data Preprocessing - produces all "_increments_training.csv" files in csv_files folder.

2) EDA + Simulation - produces all "5000____ portfolio.csv" files in csv_files folder.

3) EDA + Simulation Statistics

4) EDA Report

5) ML Preprocessing - produces the "historical_record.csv" file in csv_files folder

6) The Machine Learning Files:
	ML Initial
	ML Naive Resampling
	ML SMOTE
	ML ADASYN

7) Testing ML results with historical record:  ML Applied Analysis

	
Requirements.txt document is available at the root folder.

Thank you for taking time to review my project.  Special thanks go to my professional mentors, Evan and Kenneth.

Update 6/23/2019:  EDA notebooks now account for reinvested dividends and stock splits, but still do not account for potential tax burden.  PDF reports still reflect the previous version and a follow up announcement will be made when they've been updated.

~Steve
