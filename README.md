# Project 3 -- NHTS & NGSIM Data Analysis and IDM Simulation
Jacob Lamoureux | CIVE 202

---

## Overview
This repository contains Python code to load, visualize, and analyze two transportation datasets -- the National Household Travel Survey (NHTS) and the Next Generation Simulation (NGSIM) dataset. It also includes a simulation of vehicle following behavior using the Intelligent Driver Model (IDM).

---

## Repository Contents
- Jacob_Lamoureux_Project_3_Final_Code.ipynb -- main Jupyter notebook containing all code
- NHTS.csv -- household vehicle and travel survey data
- NGSIM.csv -- time-series vehicle trajectory data for leader-follower vehicle pairs
- Annotated Code Document.docx

---

## Requirements
Make sure you have Python installed along with the following packages before running the notebook:

pip install pandas numpy matplotlib seaborn jupyter

---

## How to Use
1. Download this repository and make sure all files are in the same folder
2. Open a terminal in that folder and run: jupyter notebook
3. Open Jacob_Lamoureux_Project_3_Final_Code.ipynb
4. Run the cells from top to bottom 
5. In Cell 5 you can change trajectorynumber to any value between 1 and 16 to look at a different vehicle pair
6. The IDM simulation in Cells 7 through 10 will use whatever trajectory number you picked

---

## Notes
- All CSV files need to be in the same folder as the notebook or the imports will not work
- The IDM parameters in Cell 8 can be changed to test different driving behaviors
