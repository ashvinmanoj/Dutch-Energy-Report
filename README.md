# Dutch-Energy

## Table of contents

- [Installation](#installation)
- [Project motivation](#project-motivation)
- [File descriptions](#file-descriptions)
- [Results](#results)
- [Author](#Author)
- [Thanks](#thanks)

## Installation

The code can be executed using Anaconda with Python ver 3.x 

## Project motivation
This project is part of Udacity Data Science nanodegree , it is the Capstone project. The data set Dutch Energy was obtained
on the following link: https://www.kaggle.com/lucabasa/dutch-energy
The direction I took in this report is to deeply investigate the data, find insight trends and infomrtion by prepare the data perform Data Eneigneering ,analysis and predicitve modeling. 
The findings are published in a report part of this repository

## File descriptions
The project consists of 3 files:
1. Readme.md (this file)
2. Energy Dutch.ipynb (the python Notebook)
3. Dataset to be downloade from the https://www.kaggle.com/lucabasa/dutch-energy and saved in same directory as the python notebook. Important: Ensure the downloaded zip file is named: dutch-energy.zip

## Results

I looked at 10 years worth of data for the Netherland 3 Energy network
administrators, Enexis, Liander and Stedin.
1.  Enexis by far is the market leader when it comes to number of connections and total consumption per year for both Electricity and Gas.
2. Liander customer base are the country pioneers in term of self electricity production and feeding the reaming to the grid. 
3. The number of smart meters installed nationally, all 3 network administrators are very closely equal in both energy Electricity and Gas , meaning that Liander and Stedin are doing great work in the spread of smart meters since there market
share of total connection is below Enexis.
4. At city level, my analysis show that as expected big cities Amsterdam, Hague and Gronningen are top energy consumers. In term of smart meters installation, Amsterdam big consumer base relate to the peak of smart meter installation where as other cities such as Rotterdam are leader in smart meter installation.
5. Self production in cities have taken off between 2012 and 2013, and maintained a steady increase. This may due to some legislation passed in the Netherland or technology improvement. 
6. A positive correlation (as expected) between energy produced by consumers and overall energy consumed for the year 2018.
7. 2 simple ML algorithms have been applied – Linear Regression and Random Forest. Both showed a very similar RMSE of about 400 while the mean of the predictive value is 5314

## Author

Walid Naous - Aeronautical Engineer |Data Scientist|Project Manager
https://github.com/nwalid

## Thanks

Thanks to [Udacity](https://eu.udacity.com/) and their outstanding staff
