# UT-DS-KNIME-Advanced
Data Science with KNIME (Advanced) course - University of Tehran
-----------------------------------------------------
Review Assignment 1: Complete this assignment by Mehr 6, 12 PM.

Task 1: Read cars-85.xlsx including only the following columns: make, fuel_type, cylinders_nr, horse_power, city_mpg, highway_mpg and price.

Task 2: Exclude the cars which their "make" value is "jaguar".

Task 3: Handle the missing values by inputing the rounded average for horse_power and removing the whole row for other columns.

Task 4: Convert cylinder_nr from string numbers to digits.

Task 5: Create a new column named "engine" which contains the values of horse_power, cylinder_nr and fuel_type. Seperate values by an underscore and use uppercased fuel_type.

Task 6: Create a new column which contains the difference between each car's price and the average price of all cars.

Task 7: For each "make" value (which is the brand) show the average of price difference (produced in task 6) and the mode of "engine" (produced in task 5).

-----------------------------------------------------
Review Assignment 2: Complete this assignment by Mehr 16, 12 PM.

Task 1: After task 3 in last assignment, calculate the average mpg (city and highway) for each car.

Task 2: Normalize price and average mpg by Min-Max normalization. Set min to 0 and max to 1.

Task 3: Use K-Means for clustering based on price and average mpg. Set number of clusters to 4.

Task 4: Denormalize price and average mpg using the normalization model built in task 2.

Task 5: Join "body-style" and "drive-wheels" columns from the original dataset (the output of task 1 in review assignment 1) to the current set based on row IDs.

Task 6: Assign different colors to each cluster.

Task 7: Use a scatter plot to visualize data on price and average mpg. In the cluster that contains cars with the highest average mpg, select 3 cars which are a bit seperated from the others and have the highest average mpg values.

Task 8: Filter out the selected cars in the previous task.

Task 9: Filter out the column created in task 7.

Task 10: Devide the dataset into 2 parts (4:1).

Task 11: Use Desicion Tree and Naive Bayes to train 2 classification models (use clusters as classes) and evaluate both of them.
