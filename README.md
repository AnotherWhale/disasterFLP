# disasterFLP

A program to solve disaster facility location problems using Gurobi.

## How it works

- Accepts datasets in csv format, which contains data of deployment centers, medical supplies, patients, and relief shelters
- The data is processed using Gurobi solver to minimize distance of patients from disaster sites to relief shelters with a limited budget

## How to run

1. Install Gurobi
2. Make sure datasets are in the same folder with `disasterFLP.ipynb`
3. Open `disasterFLP.ipynb` using jupyter notebook
4. Run with jupyter notebook
5. The solution output will be shown in the console