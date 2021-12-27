# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project was to better visualize data in excel using data formating, formulas, pivot, charts. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
First, you have to understand the requirements to implement them as requested.
Second, make the correct formating. 
	- Format the dates from UNIX 
	- Separate the 'Category and Subcategory'(with text to columns) 
	- Separating the year from date. 
Third, be familiar with PIVOT and create exactly what's required
	- Filters
	- Columns and give it the exact value
	- Order of columns
Forth, create the chart.
	- Add the tittle

### Analysis of Outcomes Based on Goals
	- Create the table per request
	- Use the COUNTIFS() formula with 3 conditions on:
		- value of Goal
		- if it's successful, failed or canceled and
		- subcategory only 'plays'
	- Use SUM() formula to calculate the Total Projects
	- Calculate %
	- Create the Chart only for the: % Successful, % Failed, % Canceled

### Challenges and Difficulties Encountered
Possible challenges or difficulties that could be encountered:
	- Figure out and show exactly the Pivot as requested. 
	- Columns & Rows. Order the columns
	- Show in chart the requested data
	- Also the date formated in UNIX was not well explained in the requirements.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	1. Is a good way to show most of the data in the pivot table 
	2. There might be other way of presenting them. Different kind of charts as well.
 
- What can you conclude about the Outcomes based on Goals?
	1. Is a good way to summarize the analitical data and use the right formulas.

- What are some limitations of this dataset?
	- Don't notice any limitations. Found it ok to visualize it.

- What are some other possible tables and/or graphs that we could create?
	- Pivot to show the sum of 'backers_count' per each country(columns) broken down by category and subcategory(rows) and add filter them per year