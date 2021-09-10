# Linear_Regression_with_Kaggle_Dataset
Experimenting with Linear Regression and Gradient Descent

In the Jupyter Notebook, each block of code is referred to as a 'code cell' or just 'cell'.

To execute simple_linear_regression_notebook.ipynb, do the following:
  1) Download the notebook and the corresponding dataset (Linear Regression - Sheet1.csv), and store them in the same directory.
  2) Open the .ipynb file in Jupyter notebook
  3) **Change the value of 'filename' variable (in the second code cell) to 'Linear Regression - Sheet1.csv'. (Don't need to keep the entire file path, if the csv file is in the same directory as the notebook.)**
  4) **Remove the first cell that lists files in the '/kaggle/input' directory. (Not needed)**
  5) Start running the code from the next cell onwards (i.e., **from the cell that reads the input data and visualizes it with a scatter plot**), until the cell where the cost curve is being plotted. Run that cell and observe the cost curve.
  6) Find the value of epoch for which the cost is the lowest. Then, below that graph; the parameters obtained at the end of each epoch are listed. For example, if the epoch number is 40, then below the graph, you'll see the following: 40: [0.004081464062096033, 0.6729699403269718]
  7) Copy the list of parameters i.e., [0.004081464062096033, 0.6729699403269718] (in this example) (Note: You should copy the parameters for the corresponding epoch, at which the **value of cost is the lowest**)
  8) Then, paste it in the 'parameters1=' line on the two cells below it (**don't paste it in the same cell from whose output you copied!**).
  9) Run the two cells below the cost curve, to see the graphs of performance against validation set and the entire dataset. If the graph is exactly like the way it is shown in the notebook here, your model fits the data perfectly.
