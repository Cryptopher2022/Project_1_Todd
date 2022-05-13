# Project 1
The purpose of this project was to create a daily information source for non-professional investors.  The source would be emailed to them or texted (or both) providing useful information that might be used the coming day for trading purposes.  

This was a collaborative effort so we broke this into four separate blocks:

1. *Pull the data from a reliable source daily or in real time.*

2. *Write the functions (as explained below).*

3. *Graph the output in useful visualizations to provide easy to digest data for the user base.*

4. *Pull all pieces together and write the email/text bot that would send out the data.*


This repository holds the first two of the items above.  While the code was being written for an API that pulled the data in and populate a dataframe for the second block of code.  To expedite parallel efforts, block one was delivered in CSV format.  

This block of code and the 5 different versions of it are the following functions:

1. *Select a date range to analyze in days.  Up to 5 years of past data plus the data available up to the current day.  For example, the user could choose 365 days or any number of days up to 5 times 365.*

2. *Next, the user would be prompted to select a "rolling window" which would be the time period of the simple moving average (SMA).*

3. *The data set(s) are then modified to fit that total range and the SMA is now set.*

1. *Preparations of the data were performed on the dataframes to remove any empty cells and also columns of data that were not used in the final calculations.*

2. *Finally, the dataframe were provided for each stock or crypto selected by the user for evaluation.*



From this point, the data was handed off to the block three author for preparation and presentation as visualizations.  

CURRENT STATUS:  To facilitate getting the code base ready, the user input was hard coded and only one cryptocurrency was used, Bitcoin (BTC).  

The functions work and they were broken down by function into functions() to facilitate calling them when needed instead of having an unimaginabely long code set.  The run() function was being debugged when time ran out.  


ADDITIONAL WORK TO BE DONE:  Our group of collaborators was close and with another week we would have this code set performing as was scoped from the outset.  

## Technologies

The project, ultimately, would be a *.py (Python) code script that would run in a program like VS Code or the like.  

This current status of the project was completed almost entirely in Jupyter Notebook.  

The README.md was modified in VS Code.  

There were main libraries used in this project:

import os
import numpy as np 
import pandas as pd 
import yfinance as yf
import requests
import alpaca_trade_api as tradeapi
import hvplot.pandas 
import questionary
import fire
pandas
Path from pathlib


This program was written and will run on Windows 10.  

---

## Installation Guide

In this section, you should include detailed installation notes containing code blocks and screenshots.

From the Command Line in Git Bash, navigate your directory to the location of the file package.  Then, type "Jupyter Notebook" to launch the application used to write and run this program.  It's outside of the scope of this README.md file to explain the installation of Jupyter Notebook.  A screenshot of the Command Line in Git Bash is shown here:  ![Git Bash](./images/VSCode_Git_Bash.png)

From Jupyter Notebook, navigate to the directory where the program is found and click on the program: "crypto_arbitrage.ipynb" as shown here in Jupyter Notebook:  ![Jupyter Notebook](./images/Jupyter_Notebook.png)

---

## Usage

There is a PPT that shows the visualizations that result from this code set.  That is found within this repository.  
    

---

## Contributors

This was done by Christopher Todd Garner, Catherine Logan and Jaime Villafuerte.  

---

## License

Feel free to use this program and happy hunting for arbitrage profits.  Add some for loops or the like and optimal profits can be achieved.  
