# Exploiting Flexibility in Coupled Electricity and Natural Gas Markets: A Price-Based Approach

This repository contains the supplementary material for the paper "Exploiting Flexibility in Coupled Electricity and Natural Gas Markets: A Price-Based Approach" to be published in the proceedings of IEEE PES PowerTech 2017. This is joint work by Christos Ordoudis, Stefanos Delikaraoglou, Pierre Pinson and Jalal Kazempour. The authors are partly funded by the Danish
Strategic Research Council (DSF) through projects “5s-Future Electricity Markets”, No. 12-132636/DSF and “CITIES”, No. 1305-00027B/DSF.

In this repository, we provide:
   1. Detailed mathematical description of transforming the original bilevel model in a Mixed-Integer Linear Program (MILP) and the linearization of cost-neutrality constraint.
   2. Supplementary figures and tables for the results.
   3. The GAMS code of the proposed priced-based approach dispatch model.

## Electronic companion
This document provides supplemental material relative to the mathematical formulation of the problem and additional figures and tables for the results.

## GAMS code and CSV files
The GAMS code corresponds to the proposed priced-based dispatch model (P-B) and the CSV files load data related to the electricity and natural gas demand, as well as wind power scenarios. Various results are printed after the model's simulation and included in the LST file that GAMS generates. The value of parameter BigM needs to be tuned when solving the model in order to ensure that complementarity conditions hold. The simulations to generate the results of the paper were performed with GAMS 24.5.6 and CPLEX 12.6.2.
