Title: Generating AMOEBA simulations with Tinker-HP
Date: 2018-12-03 
Category: Molecular Dynamics
Tags: AMOEBA, Tinker, OpenMM
Slug: simulations-with-tinkerhp
Authors: Monde Sinxi
Summary: AMOBEA simulations with Tinker

## What is TINKER?
[Tinker](https://dasher.wustl.edu/tinker/) is a molecular modelling software developed in Jay Ponder's group that has the ability to run molecular dynamics simulations using the AMOEBA fore field.
Version 8.4 is currently available and the full source code is licenced free of charge to academic research groups.
Plugins for the AMOEBA simulations are avalaible in [OpenMM ](http://openmm.org/), a high perfomance toolkit for molecular simulations that can be used as a library or as an application.
OpenMM is hardware agnostic, which is cool because we can run molecular dynamics simulations on graphics processing unit (GPUs). Highly parallelisable applications such as MD simulations can leverage the architecture of GPUs
to generate longer simulations. This is particularly important for running simulations using the AMOEBA force fields for reasons that we will dicuss below.

## The AMOEBA force field

