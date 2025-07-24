# Data-Cleaning-Layoffs-
## Overview
This project focuses on cleaning and exploring a dataset of layoffs that occured from 2020 till 2023

## Data Source
Data from https://github.com/AlexTheAnalyst/MySQL-YouTube-Series/blob/2fafcfb55511e089ab19aa1d5d542f138f68991a/layoffs.csv

## Data Cleaning Steps Performed
- Removed duplicates 
- Standardized the data 
- Null values or blank values
- Removed any columns
  
## Exploratory Analysis Performed
After cleaning, I used SQL queries to uncover trends and summarize layoffs:

## Basic Inspection
- Selected all data to verify structure
- Identified the maximum values of total and percentage laid off
- Filtered companies that laid off 100% of their workforce

## High-Impact Layoffs
- Sorted fully laid-off companies by amount of funding raised to understand which high-funded companies had full layoffs

## Company-Level Analysis
- Aggregated total layoffs per company
- Identified top companies by total layoffs

## Industry & Geography
- Summarized layoffs by:
  - Industry
  - Country

## Time-Based Trends
- Found the earliest and latest dates of layoffs
- Summarized layoffs:
  - By year
  - By month
- Created a **rolling total** of monthly layoffs using window functions

## Yearly Top 5 Companies by Layoffs
- Grouped layoffs per company per year
- Used `DENSE_RANK()` to rank and select the top 5 companies with the most layoffs per year

## Tools Used
- SQL

## Files
- layoffs.csv: Raw data
- layoffs_cleaned.csv: Cleaned dataset
- Data Cleaning Project SQL scripts used for cleaning the data
- Exploratory Data Analysis.sql: SQL scripts used for exploring the data


