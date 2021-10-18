========================================
|| Randomized Optimization Assignment ||
========================================

Yi Shuen Lim
ylim68 | 903647878

GitHub Link: https://github.com/yishuen/cs7641-assignment2

For the discrete optimization problems, code was implemented through mlrose-hiive in a Jupyter Notebook titled notebook.ipynb. 

For the neural network, the data used in included in the repo as cc_fraud.csv. The neural network was optimized using the Jython ABAGAIL library, with source code stored in the "runner" folder, sourced from Chad Maron at: 
https://github.com/cmaron/CS-7641-assignments. 

Outputs used for visualizations and analysis are in the "NN_OUTPUT" folder, and code for visualizations is in Part 2 of notebook.ipynb.

To run the neural network experiments, cd into the runner folder and then run:

- jython NN-Backprop.py
- jython NN_RHC.py
- jython NN-SA.py
- jython NN_GA.py