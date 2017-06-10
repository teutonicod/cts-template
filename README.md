# cts-template

R package for Clinical Trial Simulation


Overview

This project consists in the development of a R package containing tools for Clinical Trial Simulation (CTS). The main objective of this tool is to provide support in running CTS once that a final model is available. This model can be written in R or NONMEM; in this last case, the package allow to run NONMEM to perform the simulations directly from R.

This package was initially developed within the PK/PD Platform of TI Pharma, in collaboration with the Division of Pharmacology at Leiden/Amsterdam Center for Drug Research (LACDR).

Template structure

This package represent a practical implementation of a general framework build to perform CTS. This framework is composed by different tasks, which are implemented as functions within the package. The major tasks included in the simulation process are the followings:

Patient and Study simulation
Format of the dataset for NONMEM runs
Execution of NONMEM for the simulation step
Summary of the results
For each of this specific task, there is at least an high-level function which can perform it. The general idea is that combining together all these tasks it is possible to perform the global CTS exercise.

R Packages Required

MASS
tcltk
tcltk2
lattice
MStoolkit
