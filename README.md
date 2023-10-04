# Plot-boundary-delineation
If you have numerous plots and need to automatically delineate their boundaries, using this tool would be beneficial.

![image](https://github.com/AliBgisrs/Plot-boundary-delineation/assets/109620013/ed4633c0-e560-4d51-8c9a-195ca4312ca9)

Sometimes, you have an image displaying numerous plots, and you need to delineate the boundary of each plot for further analysis. Manually delineating plot boundaries is a labor-intensive and time-consuming process. Therefore, if you are an ArcGIS user with the same goal, using this tool is recommended.

To use this tool, you need to have the following information:

Longitude (x): This is a 6-digit number (in UTM metric) representing the longitude of the starting point. Ensure that you use at least two decimal places when assigning the x (For example, 328622.94).

Latitude (y): This is a 7-digit number (in UTM metric) representing the latitude of the starting point. Make sure to use at least two decimal places when assigning the y (For example, 5339001.64).

The tool begins creating boundaries from the points with the introduced longitude and latitude. Therefore, ensure that you input the coordinates of the points related to the lowest-left plot.

![image](https://github.com/AliBgisrs/Plot-boundary-delineation/assets/109620013/0d747fe2-b606-4960-91a2-6a902ccdd9a2)


Output Directory: Specify a specific folder where you want to save the results.

Plot Width and Height: These are the dimensions of the plots. Use a ruler to measure the dimensions of the plots and assign those numbers to this section.

Number of Rows and Columns: Indicate the number of rows and columns of the plots in your image.

Offset Distance East: This is the distance between a plot and its eastern neighbor plot in meters.

Offset Distance North: This is the distance between a plot and its northern neighbor plot in meters.
![image](https://github.com/AliBgisrs/Plot-boundary-delineation/assets/109620013/efa21285-b7c6-4c41-bd9b-d2fcf2c27a27)

![image](https://github.com/AliBgisrs/Plot-boundary-delineation/assets/109620013/6839f8a8-ac22-403c-ae82-d1e9026cfcd9)

Acknowledgments

[I would like to express my sincere appreciation to my supervisor, Dr. Paulo Flores, from North Dakota State University (NDSU), for providing invaluable support and guidance throughout the development of this script. His expertise and encouragement have been instrumental in making this project possible].

Contact

[Aliasghar.bazrafkan@ndus.edu]
