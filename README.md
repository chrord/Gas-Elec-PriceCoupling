# Readme -- Exploiting Flexibility in Coupled Electricity and Natural Gas Markets: A Price-Based Approach (PowerTech 2017)
In this repository, we provide:
   1. Detailed mathematical description of transforming the original bilevel model in a Mixed-Integer Linear Program (MILP) and the linearization of cost-neutrality constraint.
   2. Supplementary figures for the results.
   3. The GAMS code of the proposed priced-based approach dispatch model.

## Electronic companion
This document provides supplemental material relative to the mathematical formulation of the problem and additional figures relative to the results.

## GAMS code and CSV files
The GAMS code corresponds the proposed priced-based approach dispatch model and the CSV files load data related to the electricity and natural gas demand, as well as wind power scenarios. Various results are printed after model's simulation and included in the LST file that GAMS generates. The value of BigM needs to be tuned when solving the model in order to ensure that complementarities hold. The simulations to generate the results used in the paper were performed with GAMS 24.5.6 and CPLEX 12.6.2.
