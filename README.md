# Project_1_Todd
UPDATE:  The link inside the repository to the new and older versions of the Jupyter Lab code is:

https://github.com/Cryptopher2022/Project_1_Todd/blob/main/Todd's_code_SMA/From_git_hub/Proj_JV_prac-adf6d7cfb2e60e1d8fe359226315f4162a8bdc20/Jaime_/BTC_ETH_SP500_NASD-Copy1.ipynb

This is the repository of my work for Project 1

Block 1: Jaime's code - pulling data from data sources and putting them into CSV files.
Block 2: Todd's code - Taking those CSV's and massaging the dataframes so that they do the following:
  a. Only have the number of data points in the requested time interval
  b. removing all but the closing data, leaving the timestamp and "Closing" prices
  c. plotting that data in a simple line graph
Block 3: Visualizations

Additional modifications to Block 2 and merging the code in Block 1

Here's the current state of the project from what I'm calling "Block 2."  My code pulls the CSV files provided by Jaime "Block 1" and puts it into a usable format to build a simple moving average (SMA).  This was uploaded on May 7, 2022 (after our TA session - Saturday) at 2:43 p.m. central time.  

From this point, I will work toward creating functions that do the heavy lifting so they can be called by one main program.  
I will push up that code block to this repository after that's done.  Second activity will be to merge Jaime's code with my code.  

# Project_1_Todd
This is an UPDATED checklist of items remaining (as of 9:35 p.m. Sunday May 8, 2022):

1. Questionary for SMA input of from User (HAVING DIFFICULTY GETTING QUESTIONARY TO WORK):
    a. Timeframe in days (code built but not working at the moment)
    b. SMA window in days (code built but not working at the moment)
    c. Assets to evaluate are fixed for Phase 1
        iii for Phase 1 - BTC*, ETH*, S&P500, Nasdaq
2. A list of the assets to be evaluated in series
    a. BTC and ETH (if time allows, I'll build the functions to evaluate S&P500 and Nasdaq also)
4. Put all code blocks into functions to call from main *.py code base.


UPDATE:
I've spent most of the day breaking the code blocks down into functions.  This has proven quite a challenge, candidly.  At this point, I think we should proceed with the CSV's that Jaime pulled down (although expanded - see REQUEST below) and there will be a fixed set of assets from which to evaluate.  There are now three copies of the main file: BTC_ETH_SP500_NASDAQ.ipynb - a copy 1 and a copy 2.  I'm currently working on copy 2.  The main one works and is giving me the output intended.  Breaking them down and adding automation (Questionary) and passing that throughout the functions is taking some time.  However, if the folks working on the visualizations want to grab meaningful data sets, the first program is working well.  There are graphs contained in the body of the Jupyter Notebook so you can see from where the data is pulled.  I think what needs to be done is to combine the two datasets together (the output) so they can be overlayed in one graphic.  But, that's someone else's choice.  I'll stay in my lane and focus on this piece.  

REQUEST:  Jaime - can you pull down a set of data for BTC, ETH, S&P500 and Nasdaq that goes back 5 years?  This will make the "variable" time range and the rolling period (simple moving average - SMA) more meaninfgul.  I will drop the updated CSV's into my code base.  
