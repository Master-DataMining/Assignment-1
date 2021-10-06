## Data Cleaning - Assignment-1

### Goal
Implement steps required to perform data cleaning and preprocessing and visualization of the given noisy dataset

### Data Cleaning
It is a process that is used to fix and remove incorrect, corrupted, incorrectly formatted, duplicate, null values within a dataset. If the data is not proper, that makes the model complex and result in an inappropriate result.

### Data Preprocessing
It is a process that is used to manipulate and for dropping the features that is not important for the accuracy and for better performance.

Step 1: Download the dataset from kaggle and upload it on Google Drive or Github.

Step 2: Import all the required libraries and read csv input file from the drive or github.

Step 2: Calculating the missing values and plotting them in the bar graph.

Step 4: Dropping the null values and the values that are invalid, NAN or empty.

Step 5: Getting the unique count of values for each columns

Step 6: Dropping the unnecessary features that is not making more sense but just adding redundancy in the dataset.

Step 7: Renaming the columns with a better name that makes more sense.

Step 8: Dropping the rows where the number of available days are 0.

Step 9: Dropping the rows where the property name is invalid and less than 5 characters.

Step 10: Dropping the rows where the host name of the person listing the AirBnb property is less than 3 characters. On separation, found that the names given were invalid.

Step 11: Removing propeties where the price of a "Private room" room type is less than 20, as it inaccurate value for an avg price in NYC listing.

Step 12: Removing propeties where the price of a "Entire home/apt" room type is less than 50, as it inaccurate value for an avg price in NYC listing.

Step 13: Data Exploration and visualization.

Step 14: Plot the heat map intensity for the locations per the price of the properties.

Step 15: Plot the graph that shows the Boroughs in New York City. The number is 5 and unique.

Step 16: Applied Linear Regresson with Scikit learn library for predicting the prices based on the number of nights.

Step 17: Training the model based on the number of stays and price to predict price of properties on AirBnb listings and thus calculating how popular the airbnb property is in that borough.
