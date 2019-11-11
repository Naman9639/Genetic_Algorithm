# NeuralGenetic
This project optimizes the **artificial neural network (ANN)** parameters using the **genetic algorithm (GA)** for the classification of the Fruits360 dataset. The implementation is from scratch using **NumPy**.  

This project consists of 3 main Python files which are **ANN.py**, **GA.py**, and **Example_GA_ANN.py** which is the main file from which the other files are imported and called. This file uses 2 supplementary files which are the previously extracted dataset features stored into a file named **dataset_features.pkl**. The second file is the class labels for all samples which are stored into a file named **outputs.pkl**.

The **Example_GA_ANN.py** file reads the features and the class labels files, filters the features based on the standard deviation, creates the ANN architecture, generates the initial solutions, loops through a number of generations by calculating the fitness values for all solutions, selecting best parents, applying crossover and mutation, and finally creating the new population.


## Read more about GA
Before going further in this project, I recommend reading about the GA and its implementation in Python from scratch.

* **Introduction to Optimization with Genetic Algorithm**  
https://www.kdnuggets.com/2018/03/introduction-optimization-with-genetic-algorithm.html  
https://towardsdatascience.com/introduction-to-optimization-with-genetic-algorithm-2f5001d9964b  

* **Genetic Algorithm (GA) Optimization - Step-by-Step Example**  
https://www.slideshare.net/AhmedGadFCIT/genetic-algorithm-ga-optimization-stepbystep-example

* **Genetic Algorithm Implementation in Python**  
https://www.kdnuggets.com/2018/07/genetic-algorithm-implementation-python.html  
https://towardsdatascience.com/genetic-algorithm-implementation-in-python-5ab67bb124a6  
