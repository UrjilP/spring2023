# Write a Brief Descriptive Title Here

Authors:  **Name 1**, **Name 2**, etc.

YouTube Video:  [Link](http://your_link_goes_here)

---

**NOTE**:  The *italicized* content below is for your reference only.  Please remove these comments before submitting.


---
## Task List
*The table below will serve as your Progress Report (due by end of day on Monday, May 8).  Be sure to list all tasks that you need to complete to finish your analysis and to successfully complete the requirements of this project.*

| ID | Task Description | Due Date | Status |

| 1 | Update this table with detailed list of tasks | 2023-05-08 | DONE |
| 1.|	Standardizing the Data:|
|	|1.1|	Check for void entries in the address and listing date attributes.|	|
|	|1.2|	Write a program to handle void entries and standardize the data format.|	|
| 2.|	Calculating Statistics for Rent:|	|
	|2.1|	Extract rent values for each area.|	|
	|2.2|	Perform an analysis of variance (ANOVA) to compare rent across different areas.|	|		
	|2.3|	Calculate the mean and median rent for each region.|	|
| 3.|	Visualizing Rent, Availability, and Amenities Data:|	|
	|3.1|	Gather data on rents, availability, and amenities.|	|
	|3.2|	Use appropriate visualization libraries (e.g., Matplotlib, Seaborn) to create plots and graphs.|	|
	|3.3|	Visualize rent data to identify patterns and make inferences about location preferences.|	|
	|3.4|	Visualize availability data to determine the best time for renting.|	|
	|3.5|	Analyze the relationship between amenities and rental options.|		|
| 4.|	Regression Analysis for Rent Forecasting:|	|
	|4.1|	Collect historical rent data for each area.|	|
	|4.2|	Conduct regression analysis using a suitable regression model (e.g., linear regression).|	|
	|4.3|	Train the model using historical data and generate predictions for future monthly rents.|	|
| 5.|	Analyzing Availability and Rent:|	|	
	|5.1|	Explore the availability and rent trends across various areas.|	|
	|5.2|	Identify rental hotspots based on high demand and low availability.|	|
	|5.3|	Determine the best time for renting by analyzing availability patterns.|	|
	|5.4|	Identify affordable options based on rent and availability data.|	|
| 6.|	Identifying Top Amenities and Features:|	|
	|6.1|	Analyze the availability of rental options with different amenities and features.|	|
	|6.2|	Identify the most commonly available amenities and features.|	|
	|6.3|	Determine the trends and preferences based on the availability of specific amenities.|	|

| n-1 | Complete YouTube video and upload to YouTube | 2023-05-16 | |
| n | Upload README.md document to Github | 2023-05-17 |

--- 

## Introduction
*The purpose of this section is to provide some background about your project.  For example, your introduction should discuss*
- *The purpose of your project;*
- *The type of data you're using;*
- *What you're doing with this data;*
- *What types of analysis you're conducting;*

*Your introduction should make the reader excited to read the rest of this document.*

---

## References
*In this section, provide links to your references and data sources.  For example:*
- Source code was adapted from [the magic source code farm](http://www.amagicalnonexistentplace.com)
- The code retrieves data from [the organization for hosting cool data](http://www.anothermagicalnonexistentplace.com)
- The forecasting models were modified from [some academic research paper](http://www.linktotheacademicpaperyouused.com)

---

## Requirements
*In this section, provide detailed instructions for installing any necessary pre-requisites.  This could include:*
- *Python packages/libraries;*
- *API keys;*
- *etc.*

---

## Explanation of the Code
*In this section you should provide a more detailed explanation of what, exactly, your Python script(s) actually do.  Your classmates should be able to read your explanation and understand what is happening in the code.*

The code, `needs_a_good_name.py`, begins by importing necessary Python packages:
```
import matplotlib.pyplot as plt
```

- *NOTE:  If a package does not come pre-installed with Anaconda, you'll need to provide instructions for installing that package here.*

We then import data from [insert name of data source].  We print the data to allow us to verify what we've imported:
```
x = [1, 3, 4, 7]
y = [2, 5, 1, 6]

for i in range(0,len(x)):
	print "x[%d] = %f" % (i, x[i])		
```
- *NOTE 1:  This sample code doesn't actually import anything.  You'll need your code to grab live data from an online source.*  
- *NOTE 2:  You will probably also need to clean/filter/re-structure the raw data.  Be sure to include that step.*

Finally, we visualize the data.  We save our plot as a `.png` image:
```
plt.plot(x, y)
plt.savefig('samplefigure.png')	
plt.show()
```

The output from this code is shown below:

![Image of Plot](samplefigure.png)

---

## How to Run the Code
*Provide step-by-step instructions for running the code.  For example, I like to run code from the terminal:*
1. Ensure that you have registered for the [insert name of API] API key.  (You may reference the instructions for doing this.)

2. Ensure that you have installed necessary Python packages. (Again, you may include a reference here to a prior section in the README that provides the instructions.)


2. Open a terminal window.

2. Change directories to where `needs_a_good_name.py` is saved.

3. Type the following command:
	```
	python needs_a_good_name.py
	```

- *NOTE: You are welcome to provide instructions using Anaconda, IPython, or Jupyter notebooks.*

---

## Results from your Analysis
*Last, but not least, you need to demonstrate your results.  You should include figures and/or tables of results.  What worked well?  What could be improved?*
