# Data-Analytics-Project-1

<<<<<<< HEAD
Mortgage Loans, Treasury Yields and Real Estate  

Team Members: 
Erica Lovell 
Dmitriy Bachkala 
Jaxon Keller 
Graciela Aguayo  

Project Description: 
- Analyze the relationship between home prices, mortgage rates, treasury yield rate, and loan performance.
- What causational relationships exist between these variables? 

Mortgage Rates vs. Treasury Yields (Erica)
    Datasets:  
      - Federal Housing Finance Agency; Terms on Conventional Single Family Mortgages, Fixed-Rate 30-YEAR And 15-Year Non-Jumbo Loans; 1990-2019
      - US Department of the Treasury; Annual Daily Treasury Par Yield Curve Rates, 2006-2010
      
    To prepare the Treasury Yield data for analysis, there was a fair amount of cleanup involved. The process started with five individual datasets, one for each year.
    The cleanup process included:
      - Generating a monthly average rate within each dataset
      - Merge the 5 datasets into one
      - Utilize concat to combine the 5 columns of data into one vertical column
      - Convert month to two digits with zfill
      - Create new column with combined month & year
    This provided a clean dataset ready to be compared against mortgage rates.

    The mortgage rate preparation process was much easier, as it began with only one dataset. 
    The cleanup process was simply: 
     - Convert month to two digits with zfill
     - Create new column with combined month & year
    The resulting dataset mirrored that of the Treasury yields for compatible comparisons. 

    Comparisons
     - Visually there is a strong visual correlation between the two datasets before the Great Financial Crisis. 
     - However, a ttest demonstrated that even with the weaker correlation during the Great Financial Crisis, this period of data still maintained a the pvalue of 3.417893260344795e-20.

Relationship between federal fund rates and mortgage performances (Jaxon) 

Trends and fluctuations in mortage rates and home prices throughout the years 2006-2011? (Dmitriy) 

How have home prices trended in all 50 states? (Graciela)

Conclusions: 
 - There is a strong causational relationship between Treasury yield rates and mortgages rates. Even though this relationship weakens during times of great financial upheaval, there is still a strong overall correlation between these two datasets.
 - Throughout the years 2005 - 2010, the United States average HPI change shows us that prices of homes through 2005 - 2007 increased but as soon as we hit 2008, house prices started to decrease. This shows us that the best time for buyers was 2009-2010 and the best time for sellers was 2005-2006. 
=======
Cell one. Importing necessary modules for the code to run appropriately.

AVERAGE MORTGAGE RATES

Cell two. Specifying the CSV file path to pull the data, reading in the CSV file into a DataFrame. Making the display show all the columns (optional). Printing the DataFrame.

Cell three. Extracting only the relevant columns and filtering the years for 2006-2010. Combining the Year and Month columns to create a new column. Convert the new "Month-Year" column to a datetime format. Calculate the average monthly contract interest rate.

Cell four. Plotting the mortgage rates. Adding the labels and titles. Displaying the plot.

AVERAGE HOME PRICE

Cell five. Extracting only the relevant columns and filtering the years for 2006-2010. Converting Year and Month into integers. Combining the Year and Month columns, then converting the new column "Month-Year" into datetime format. Calculating monthly average home prices.

Cell six. Plotting the home price. Adding the labels and titles. Displaying the plot.
>>>>>>> 433f20bfca4367fae6ecd149aa1afa6e8cf0087b
