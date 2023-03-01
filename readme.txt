Given the housing data set of properties (properties.csv) and on that are sales (sales.csv), 
write a function that takes a single property from properties.csv as lat,long and calculates the nearest 10 properties that sold from (sales.csv).

properties is around 1,000,000 lines
and sales is around 10,000 lines.


def find_closest_sales(n_closest, sales_df, property_lat, property_lon):
  --> dataframe of n closest sales
 

