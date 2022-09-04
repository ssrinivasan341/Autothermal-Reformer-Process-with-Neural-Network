# Autothermal-Reformer-Process-with-Neural-Network

The following formulations have been taken from the OMLT repository notebook found at: 
https://github.com/cog-imperial/OMLT/blob/main/docs/notebooks/neuralnet/auto-thermal[1]reformer.ipynb. 

This dataset contains process information regarding an auto-thermal reformer process and serves as an 
example of how a neural network could be used to optimize decision making for a chemical processing 
plant. The dataset (“reformer.csv”) is found in the OMLT repository at 
https://github.com/cog[1]imperial/OMLT/tree/main/docs/notebooks/data and is handled using pandas.



The purpose of this group project was to use a Machine Learning model (Neural Networks) to predict the output compositions of hydrogen and nitrogen after passing through the Autothermal Reformer. See first link of Github for more details.

We tested the accuracy of the neural network by modifying its architecture and using different activation functions (sigmoid, tanh, relu, etc.). The model was then fed into pyomo to solve the optimization problem (maximizing hydrogen while constraining nitrogen below a mol fraction of 0.34). 
