# Predicting Financial Well-Being

## Project Members
* Matt Calvert
* Jeff DuBois

## Project Overview
The Consumer Financial Protection Bureau (CFPB) conducted an online survey in 2017 to measure the financial well-being survey of adults in the United States. The survey included the CFPB Financial Well-Being Scale as well as several measures that are believed to influence an individual's level of financial well-being. The goal of this project is to use machine learning to predict financial well-being.

## Process, Analysis and Conclusions
Please see fwb_presentation.pdf in this repository or view online at https://docs.google.com/presentation/d/1EHjmNc1Jq2CAwYgpCHPjASHgLx8IWo1Dv6HUI0rpbNg/edit?usp=sharing.

## Data Source and Resources
* Data Source: https://catalog.data.gov/dataset/financial-well-being-in-america-2017
* Financial Well-Being in America 2017 Report: https://files.consumerfinance.gov/f/documents/201709_cfpb_financial-well-being-in-America.pdf
* Financial Well-being Scale Users Guides: https://www.consumerfinance.gov/data-research/research-reports/financial-well-being-scale/
* Financial Well-being Survey Codebook: https://files.consumerfinance.gov/f/documents/cfpb_nfwbs-puf-codebook.pdf

## Data Repository
This repository contains the following folders and files:
1. data - Folder with processed datasets for analysis.
2. images - Folder with images of decision trees and random forests.
3. resources - Folder with CSV file from data.gov and pdfs of CFPB's resources.
4. data_analysis_1.ipynb, data_analysis_2.ipynb, data_analysis_3.ipynb - Jupyter notebook to analze the two processed datasets. Note the 3rd analysis file modified the 2nd dataset by dropping 5 columns.
5. data_exploration_1.ipynb, data_exploration_2.ipynb - Jupyter notebooks to create the two preprocessed datasets.
6. database_schema.sql - SQL code to creating and review a PostgreSQL database from the CSV file.
7. dataset_info - Spreadsheet created with information on each data variable. This along the CFPB's codebook and report were critical to understanding and analyzing the data.
8. project_presentation.pdf - PDF of Google slideshow referenced above. 
9. README.md - This file.
