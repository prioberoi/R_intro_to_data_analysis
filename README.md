# R_intro_to_data_analysis
Class materials for Intro to Data Analysis with R

## While we are waiting to get started:

# Clone this repo
You can find instructions on how to do that here:
https://help.github.com/articles/cloning-a-repository/

If you are having a hard time, you can click on each item in the repo and download it manually by clicking "Raw"

# Make sure you have the packages you need

Run the first chunk of code in the data_analysis_with_R.Rmd file


what is basic data analysis
	summary stats 
	visualization

techniques
	Your Turn
	Edit This Code
	Don't run this code, someone tell me whatyou think it does

pipeline
	ingestion
	cleaning: munging and wrangling
	analysis
	modeling and application
	reporting and visualization
tools we use throughout the pipeline:
	statistics
	aggregation
	visualization

Topics
	why data analysis
		clean up data
		decide on wrangling
		summarize and describe data
		communicate findings through data visualization
		inform development of more complex statistical models
	reporting with r markdown
		present
		reproducability 
	Data Visualization with ggplot2
		scatter plots
		histograms and bar charts
		box plots and violin plots
			boxplots for normal distribution
			violin for other distributions, like bimodality
	Introduce NTIA usecase
	cleaning data
		structure of tidy data 
			variable = column
			observation = row
			observational unit = table
		messy data
			column headers are values, not variable names
				melt
			multiple variables are stored in one column
			variables are stored in both rows and column
			multiple types of observational units are stored in one table
			a single observational unit is stored in multiple tables
	summarizing data within groups
	merging data
	exploratory data analysis
	comparing two samples
		for DC, see if the mean advertised speed is equal to the mean typical speed for downloads
	correlation
		scatterplot matrices
	Getting into statistics and ML territory
		linear regression
			geom_smooth(method="lm")
		multiple linear regression
		hierarchical clustering?
		k means clustering and dimensionality reduction
