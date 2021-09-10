# Linear_Regression_with_Kaggle_Dataset
Experimenting with Linear Regression and Gradient Descent

To execute simple_linear_regression_notebook.ipynb, do the following:
  1) Download the notebook and the corresponding dataset (Linear Regression - Sheet1.csv), and store them in the same directory.
  2) Open the .ipynb file in Jupyter notebook
  3) Change the value of 'filename' variable to 'Linear Regression - Sheet1.csv'. (Don't need to keep the entire file path, if the csv file is in the same directory as the notebook.)
  4) Remove the first cell that lists files in the '/kaggle/input' directory. (Not needed)
  5) Start running the code from the next cell onwards, until the cell where the cost curve is being plotted. Run that cell and observe the cost curve.
  6) Find the value of epoch for which the cost is the lowest. Then, below that graph; the parameters for epoch are listed. For example, if the epoch number is 40, then below the graph, you'll see the following: 40: [0.004081464062096033, 0.6729699403269718]
  7) Copy the list of parameters i.e., [0.004081464062096033, 0.6729699403269718] (in this example)
  8) Then, paste it in the 'parameters1=' line on the two cells below it (don't paste it in the same cell from where you copied!).
  9) Run the two cells below the cost curve, to see the graph. If the graph is exactly like the way it is shown in the notebook here, your model fits the data perfectly.
