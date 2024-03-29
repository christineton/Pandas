## Pandas Practice Activities

## Pandas DataFrame Basics

- Running python
	- Anaconda, Python, IPython, and Jupyter notebooks
	- Installing packages
	- `conda` environments

- Loading your first dataset
- Looking at columns, rows, and cells
- Subsetting columns
- Subsetting rows
- Subsetting both columns and rows
- Boolean subsetting
- Grouped and aggregated calculations
- Export/save data

exercise: load the tips dataset and filter rows by gender and total bill amount.


## Tidy data

Knowing what is a "clean" and "tidy" dataset will help look for common data problems and give an idea on what our final dataset should look like. Once the data is tidy, it can be easily transformed to other shapes needed for analysis. Understanding what kinds of data manipulation steps are needed will help with the "how" to do it, i.e., it is language agnostic, and won't matter what language you use.  This section goes through Hadley Wickham's "Tidy Data" paper.

- What is tidy data
- Fixing common data problems
- Columns containing values, not variables
- Columns containing multiple variables
- Variables in both rows and columns
- Multiple observational units in a table (normalization)

exercise: tidy two small datasets used in the R for Data Science book tidy data example


## Applying Functions

Sometimes we need a more complex method to tidy our data. Other times, we need to perform more complex tasks on our data. Here we'll cover how to write functions in Python and how to apply them to our data. This way, if a method does not exist to perform the task we want, or if we want to combine multiple tasks together, we can write our own custom functions to process our data.

- Writing a Python function
- Applying functions
- Vectorized functions

exercise: use the ebola dataset from the tidy section, and instead of using the .str. accessor, write a function to parse out the string.

## Dummy variables and models

Conclusion: Getting ready for modeling

We clean data so we can do something with it.
A common task is to fit some statistical model on our data.
One last processing task will be to convert our categorical variables into "dummy variables" for a model.
The goal of the last section is to how how pandas fits into the larger data science ecosystem.

- dummy variables
- linear regression in sklearn

exercise: fit a model on the titanic datset