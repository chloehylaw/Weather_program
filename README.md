# Weather program

## Create a C program that uses a two-dimensional array in a wheather program.

This program will find the total rainfall for each year, the average yearly rainfall, and the average rainfall for each month.

The input will be a 2D array with hard-coded values for rainfall amounts for the past 5 years.
- The array should have 5 rows and 12 columns
- Rainfall amounts can be floating point numbers

Sample output

YEAR | RAINFALL (inches)
------------ | -------------
2010 | 32.4
2011 | 37.9
2012 | 49.8
2013 | 44.0
2014 | 32.9

The yearly average is 39.4 inches.

MONTHLY AVERAGES:

Jan Feb Mar Apr May Jun Jul Aug Sep Oct Nov Dec

7.3 7.3 4.9 3.0 2.3 0.6 1.2 0.3 0.5 1.7 3.6 6.7

## TODO
- Initialize your 2D array with hard-coded rainfall amounts
- Remember to iterate through a 2D array you will need a nested loop
- The key to this solution will be to visualize a 2D array and understan dhow to iterate though one, via a nested loop
- As you are iterating, you can keep a running total (outer loop iterate by year, inner loop iterate by month) to get the total rainfall for all yearas
- To get the average monthly rainfalls, iterate through the 2D array by having the outer loop go through each month and the inner loop go through each year
