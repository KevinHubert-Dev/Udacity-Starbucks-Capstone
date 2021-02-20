# Udacity Machine Learning Nanodegree - Capstone Project
In this repository you will find all files which are part of my udacity "Machine-learning"-Nanodegree capstone project. 
A description of the files in detail can be found below.

## Starbucks Catpstone Project
For my captstone project of the Udacity "Machine Learning"-Nanodegree I've decided to do a project based on data provided by Starbucks and Udacity. This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.

My task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products

## Problem statement
Customers are as individual as their needs. This makes addressing customers directly through marketing campaigns an extremely complex issue. There are various reasons why customers do not respond to offers from companies, a few of which are:
- The customer has not read/received the message - Wrong marketing channel. 
- The offer does not meet the customer's needs 
- The customer is not interested in the offer 
- The customer was approached at the wrong time (e.g. receives money at begin of month and has not money left at the end of the month) 

On the other hand, success through marketing campaigns depends on customers responding to the offers and going through the following steps to do so
1. Receive offer - Customer receives the offer 
2. See / Read Offer - Customer sees/reads the offer 
3. Transaction - Customer interacts with offer 
4. Done - offer fulfilled 
 
As you can see there are several steps required until the offer is fulfilled (Done). Only if all steps are fulfilled then the custom will be happy and we will increase the companies profit

## Project files/folders
Part of the repository and the following files:
- README.md - Repository description
- Starbucks_Capstone_notebook.ipynb - Jupyter notebook contain the whole project logic and code
- proposal.pdf - Project proposal which describe the problem and solution I would like to work on (was created before beginning the project)
- report.pdf - Report of my solution for the captstone project
- figures/ - Folder contain all figures created in the jupyter-notebook
- data/ - Folder containg the data used for the project in *.JSON format

## Project dependencies
To be able to solve the problem I've used the following python libraries
- pandas
- numpy
- json
- matplotlib
- IPython.display
- sklearn (linear_model, metrics, ensemble, preprocessing, model_selection)
- tensorflow 
- keras