# Athletic Wear Sales Analysis

   ### CONTENTS
**[The Challenge](#the-challenge)**<br>
**[Starter Code](#starter-code)**<br>
**[Challenge Checklist](#challenge-checklist)**<br>
**[Running the Program](#running-the-program)**<br>

## The Challenge

Utilizing Pandas in Jupyter Notebooks, will perform data analysis of a national sales of athletic wear across two years (2020–2021). The analysis will answer three questions:

1. Which retailers had the greatest total sales of athletic wear?
2. Which retailers sold the most women’s athletic footwear?
3. Which day and week had the highest sales of women’s athletic footwear.

## Starter Code

The starter code for this challenge consists of three files.  

1. A comma-separated values (CSV) file that provides data for sales of athletic wear across the U.S. for the year of 2020.
2. A comma-separated values (CSV) file that provides data for sales of athletic wear across the U.S. for the year of 2021.
3. A Jupyter notebook (.ipynb) file that prompts for the expected code.

This challenge is of a more interesting flavor without any prompted output, and, excepting importing pandas, no actual code. The challenge's starter file has instruction in the form of comments broken up into seven main sections and several subsections via markdown headers.



## Challenge Checklist

### Part 1: Combine and Clean the Data

- [ ] Import and display data
- [ ] Check data types
- [ ] Combine and clean data

### Part 2: Determine which Region Sold the Most Products

- [ ] Use groupby to compute most product sales by region and display top 5
- [ ] Use pivot_table to compute most product sales by region and display top 5

### Part 3: Determine which Region had the Most Sales

- [ ] Use groupby to compute total sales by region and display top 5
- [ ] Use pivot_table to compute total sales by region and display top 5

### Part 4: Determine which Retailer had the Most Sales

- [ ] Use groupby to compute total sales by retailer and display top 5
- [ ] Use pivot_table to compute total sales by retailer and display top 5

### Part 5a: Determine which Retailer Sold the Most Women’s Athletic Footwear

- [ ] Filter data to women’s athletic footwear
- [ ] Use groupby to compute total sales of women’s athletic footwear by retailer and display top 5
- [ ] Use pivot_table to compute total sales of women’s athletic footwear by retailer and display top 5

### Part 5b: Determine the Day with the Most Women’s Athletic Footwear Sales

- [ ] Create and display a pivot table by date
- [ ] Resample data into bins to find daily total
- [ ] Sort data

### Part 6: Determine the Week with the Most Women’s Athletic Footwear Sales

- [ ] Resample data into bins to find weekly total
- [ ] Sort data

## Running the Program

The program folder contains the completed Jupyter notebook which can be run cell by cell from and results displayed in Jupyter, Jupyter Lab, or VS code with Jupyter extensions.

```
athletic_sales_analysis.ipynb
```

The outputs for all cells in the notebook have been cleared. The notebook cells should be run from top to bottom. Outputs will closely resemble those displayed in the Bootcampspot challenge instructions.

Note: the original start code file (athletic_sales_analysis_starter_code.ipynb) will be a clone of the completed challenge file, just in case whatever grading process is used will be looking for the original file to run, but I didn’t like its name.