# Kickstarter-Analysis
Performing analysis on Kickstarter data to uncover trends

## Table of Contents
- [1.0 Introduction](#Introduction)
  * 1.1 Purpose
  * 1.2 Tools
- [2.0 Analysis and Challanges](#Analysis-and-Challenges)
  * 2.1 Theater Outcomes by Launch Date
  * 2.2 Outcomes Based on Goals
- [3.0 Results](#Results)
  * 3.1 Theater Outcomes by Launch Date
  * 3.2 Outcomes Based on Goals
- [4.0 Resources](#Resources)

## 1.0 Introduction

### 1.1 Purpose
Louise wants to analyise how plays how different campaigns compared to their launch date and goals.
The purpose of this analysis is to be able to identify the amount of plays that were successful, failed, or canceled based off of the launch date and year.  As well as how the plays performed based off the goal. These two analyses can provide a clear insight to the date and goal to set in order to have more successful plays. 

### 1.2 Tools
- Excel
  - Pivot Tables
  - Line Chart

## 2.0 Analysis and Challenges
### 2.1 Theater Outcomes by Launch Date
The analysis for “Theater Outcomes by Launch Date” was created by first editing the time stamps from Unix to a short date, and then creating a pivot table to aggregate the data.  By translating the Unix time stamp to short date using the following formula: 

`=((("Unix Date"/60)/60)/24)+DATE(1970,1,1)`. 
A pivot table was created to display the outcome of the theaters based off of the month that they were launched. 
![alt text](Resources/Pivot_Table.png)

### 2.2 Outcomes Based on Goals

## 3.0 Results
### 3.1 Theater Outcomes by Launch Date

### 3.2 Outcomes Based on Goals

## 4.0 Resources
exceljet.net - learn how to write a countifs statement
