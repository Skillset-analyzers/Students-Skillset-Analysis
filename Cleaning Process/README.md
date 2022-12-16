## Cleaning of Dataset

The data is collected and it may contains many null values that needs to be treated for the further processing.
There are also many data that is needed to be dropped in order to hide identity of the user from whom data is collected.

  * The functions that are used for data visualization are head, tail, describe, info, isnull
  * Dropping the columns which are not required. Function used:
    df.drop('Coulmn Name', inplace= True, axis=1)
  * Only one column (6. Active in developer Communities) contains null values
  * Visualization of those null values using heat map ( Most graphs can't be plotted due the the string values)
  * Setting the null values to string "No". Function used:
    df['Coulmn name'].fillna("No", inplace="True")
    
The further processing of the data will be done using the cleaned csv file.
