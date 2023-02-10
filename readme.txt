Given the housing data set of properties (properties.csv) and on that are sales (sales.csv), 
write a function that takes a single property from properties.csv as lat,long and calculates the nearest 10 properties that sold from (sales.csv).

Properties is around 1,000,000 lines
and sales is around 10,000 lines.

Just sample sales.csv to create properties.csv (100 properties).

def find_closest_sales(n_closest, sales_df, property_lat, property_lon):
  --> dataframe of n closest sales
 

