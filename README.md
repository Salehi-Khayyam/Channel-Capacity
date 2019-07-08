# Channel-Capacity
A tool for computing channel capacity of concurrent probabilistic programs using genetic algorithm

# About
This tool computes channel capacity of a program writen in the [PRISM language](http://www.prismmodelchecker.org/manual/ThePRISMLanguage/Introduction) based on expected and maximum leakage. It takes as input the properties of modules or threads produced by [PRISM-Leak](https://github.com/alianoroozi/PRISM-Leak). The properties of each module consist of frequencies of secret variables in each module and the probability of traces in the module, without considering the initial probability of the secrets.

# Usage
To compute the channel capacities, run the corresponding program in jupyter-notebook, set the index of the favorite case study in the program, run the notebook, and enjoy! 
