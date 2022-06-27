# Modelling XPS - ODE Constrained Optimisation

This github repository contained the PDE constrained optimisation calculation used in the paper  "New Insights into the Kinetics of Metal|Electrolyte Interphase Growth in Solid-State-Batteries via an Operando XPS Analysis - Part II Modelling"

# Introduction
Understanding the interfacial dynamics of batteries is crucial to control degradation and increase electrochemical performance and cycling life. If the chemical potential of a negative electrode material lies outside of the stability window of an electrolyte (either solid or liquid), a decomposition layer (interphase) will form at the interface. To better understand and control degradation at interfaces in batteries, theoretical models describing the rate of formation of these interphases are required. Yet, experimental data which could support these models are challenging to obtain considering that the decomposition reaction is dynamic in nature and occurs at a deeply buried interface making it inaccessible to quantitative non-destructive techniques such as X-ray photoelectron spectroscopy (XPS) which has a limited depth of analysis. We demonstrated that the rate of plating and interphase formation can be accurately described by adapting the theory of coupled ion-electron transfer (10.26434/chemrxiv-2022-hd73j). Models are fitted using experimental data from the first part of this study (10.26434/chemrxiv-2022-jpnxq). The following Julia notebook uses PDE constained optimisation to leanr the parameters whciih determine the rate of electroplating directly from operando XPS data. 



