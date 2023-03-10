European Leadership Univercity(NL)

M4 - W1 Assignment: Visualising the Right Way:
1) Create a plot using Matplotlib

-Create a numpy array x with 1000 values ranging from -10 to 10. Create another numpy array y with 1000 values ranging from -10 to 10.
-Define a function z_func that takes in two arguments x and y and returns a numpy array of the same shape as x and y. The function should use the equation z = sin(sqrt(x^2 + y^2)) / sqrt(x^2 + y^2). Use x and y as inputs to the z_func function to create a numpy array z.
-Use matplotlib to create a 2D scatter plot of x and y. Use the scatter() function to create the plot, and set the c parameter to z to color the markers based on the value of z. 
-Use the cmap parameter to specify the colormap to use, and set it to 'coolwarm'. Add a colorbar to the plot using the colorbar() function. Set the title of the plot to "Advanced Scatter Plot", and set the x and y axis labels to "X-axis" and "Y-axis", respectively.

Save the plot as a PNG image named "advanced_scatter_plot.png" with a resolution of 300 DPI.


2) We take data visualisation seriously.  With every single one, we as data scientists, try our best to visualise the numbers accurately and in a way that best supports our goals. But sometimes we get it wrong. We can do better in future if we learn from our mistakes . Now, take a look at the two visualisations below about public opinion on Britain's decision to leave the EU. The one on the left represents a not-so-good visualisation while the right one does a better job.

https://elu.instructure.com/courses/150/files/2332/preview

Now your task is the following: 

1- First, explain thoroughly which one you think is better; the left or the right. And why!  

2- Reproduce both of them using Matplotlib. Do your best making them the exact copies.  

3- Submit your visualisations including the explanation in step 1 as Jupyter notebook