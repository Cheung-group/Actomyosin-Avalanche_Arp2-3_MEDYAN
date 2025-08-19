# Codes for MEDYAN simulation data analysis & trajectory animation

### Chengxuan Li, August 2025

## MEDYAN software

See https://medyan.org/ for the original software information. Chengxuan used version v3.2 for the simulations in this work.

## analyze script

Chengxuan used Python 3.8 to run AnalyzeTrajectory.py to convert MEDYAN simulation trajectories into arrays easy for analysis in later steps. 

This analyzing file was written by the Papoian group, and the original file is attached in this repo. It was originally prepared for Python 2 (e.g. Python 2.7).

Chengxuan made edits to this file to make it compatable to graph theory analysis as well as Python 3. Therefore there are files like AnalyzeTrajectory_graphtheory.py that are actually used for the analysis in the directory 'analysis' which are mostly for Python version 3.8.

## animate script

See how to visualize MEDYAN simulation trajectories in directory 'animation'. Some other .py files that are modified for other purposes are also attached in this directory. The animation script was also originally written by Papoian group, and modified by Chengxuan for research purpose.