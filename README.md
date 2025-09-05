# ACIT4610---Mandatory-1
# **ACIT 4610 – Mid-Term Portfolio Project 1**
## Vehicle Routing Problem (VRP) with a Quantum-Inspired Genetic Algorithm

This repository solves small/medium/large Vehicle Routing Problem (VRP) instances using Genetic Algorithm (GA) with a “quantum-inspired” split representation (permutation + route cuts). It then evaluates solution quality, convergence, runtime, and consistency across multiple runs and parameter sets.

## Content
* Folder(Drafts)    _# Individual drafts created_
    * GA_Medium_kladd.ipynb
    * Large.ipynb
    * Small_karo.ipynb
    * VRP - Small Group Susrita.ipynb

* README.md
* MAIN CODE.ipynb
* MAIN_CODE_BHF.ipynb

## Requirements
* Python 3.8+
* Libraries:
    * numpy
    * pandas
    * matplotlib
    * seaborn (optional but used)
    * ipython (for display styling)
Install (local):


> pip install numpy pandas matplotlib seaborn ipython



## Quick start
1. Ensure costumers.csv is in the same folder as the MAIN_CODE
2. In the notebook, make sure you load with a relative path that works for you:


``
df = pd.read_csv("customers.csv")  # not "/customers.csv"
df = pd.read_csv("./customers.csv")
df = pd.read_csv("data/customers.csv")
df = pd.read_csv("/content/customers.csv")
``