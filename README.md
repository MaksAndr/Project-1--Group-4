[Deaths by State.docx](https://github.com/MaksAndr/Project-1--Group-4/files/10727101/Deaths.by.State.docx)
# Project-1--Group-4

Project title
	○ Understanding the prevalence of hepatitis and measles within the United States over the past n years
• Team members
	○ Bethlehem
	○ Umeadi
	○ Maksym
	○ Joshua
• Project description/outline
	○ We seek to understand the prevalence of contagious diseases within the United States over the past n years and determine if there are any hotspots or trends from the research.
• Project scope
	○ The analysis will include a review of data provided by the University of Pittsburgh which spans from 1966 to 2011 for the following contagious diseases:
		§ Hepatitis 
		§ Measles
• Research questions
	○ Which states had the most and least incidence of contagious diseases over time, overall and per capita?
	○ Which year was a particularly "bad" year in the U.S. based on the incidence of contagious diseases?
	○ Is there a correlation between the incidence of one contagious disease and another?
• Data to use
	○ Project Tycho: Contagious Diseases - https://www.kaggle.com/datasets/pitt/contagious-diseases
• Task overview
	○ Import hepatitis and measles .csv into a dataframe (Jupyter Notebook)
	○ Data Preparation
		§ Analyze & understand shape, structure, missing fields, etc.
		§ Clean datasets
			§ Change and align Data types for year/week
		§ Merge based on year/ww and state
			§ Ensure that the years overlap and are consistent
		§ Add population column (=iferror(cases * 100) / incidence_per_capita,0))
	○ Analyzing
		Exploratory data analysis
		Charting/plotting
	○ Presentation
		§ Write-up of findings
![image](https://user-images.githubusercontent.com/113949097/216836698-69b29ec4-94dd-4eb5-aa4b-731ce93c1650.png)
