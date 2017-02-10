#Lab 04: For Loops






1 , 1 , 2 , 3 , 5 , 8 , 13 , 21 , 34 , 55 , 89 , 144 , ...  
Often, especially in modern usage, the sequence is extended by one more initial term:  0 , 1 , 1 , 2 , 3 , 5 , 8 , 13 , 21 , 34 , 55 , 89 , 144 , ...  
By definition, the first two numbers in the Fibonacci sequence are either 1 and 1, or 0 and 1, depending on the chosen starting point of the sequence, and each subsequent number is the sum of the previous two.


4.  Obtain the data and metadata files in the Lab04 folder on Sam's Github site for the course.  The data file is "CO2_data_cut_paste.csv", and the meta-data file is "MetaData_CO2_emissions.txt".  **Copy both of these files into your directory for lab04 in your own repo.**  Read through the meta data to understand what the data file is.  Then, do the following:  
	**4a**.  Read the data into RStudio (hints: (1) You will need to set the working directory using `setwd()` or specify the full file path. (2) Use `read.csv()`)  
	**4b**.  For each of the quantities in the data frame you just imported, except for the `Year`, calculate the percent change from year `i-1` to year `i` across all years.  Your results should be stored in a new data frame or matrix.  Your new object should have headers/column names that make sense (you can use the same ones)
	**4c**.  Use `write.csv()` to save your new data frame to a file. The file should be named "YearlyPercentChangesInCO2.csv", and it should be in your Lab04 folder
