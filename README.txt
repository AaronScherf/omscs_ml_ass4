Readme for replication of reinforcement learning - Markov Decision Processes (Assignment 4)
Aaron Scherf
ascherf3

The Jupyter Notebook (https://github.com/AaronScherf/omscs_ml_ass4/blob/main/ML_As4_RL.ipynb) contained in the project repository on GitHub is self contained, in that it imports all data and libraries needed to reproduce the results.

No external data sources are required, since the environments are imported from the packages. The full github repository is available at: https://github.com/AaronScherf/omscs_ml_ass4

The notebook installs all required libraries which are not standard in Anaconda or Google Colab via the pip install command.

The libraries required to implement the notebook are all available on a standard Google Colab system, which was used to execute the notebook. They include:
- bettermdptools
- mdptoolbox-hiive
- pymdptoolbox
- gym
- pygame
- matplotlib
- math
- pandas
- time
- sys 
- numpy
- itertools
- seaborn
- gc

The notebook uses a random seed of 42 for all available random number generator inputs, to improve reproducibility.

The notebook can be executed with a "Run all" command to return all of the plots and descriptions used for the report.