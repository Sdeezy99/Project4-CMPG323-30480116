# Project 4 - UiPath RPA User Acceptance Testing Automation
## Overview
Testing is a critical phase in software development, and it can take various forms, including internal development team testing and user acceptance testing (UAT). UAT, which ensures that the solution produces the expected output, often serves as the "go/no-go" decision point. In this project, we'll focus on automating UAT using Robotic Process Automation (RPA) to streamline repetitive tasks.

Robotic Process Automation involves using technology to mimic human actions, typically related to front-end or user interface automation. RPA is especially valuable for automating repetitive and time-consuming tasks, freeing up human resources for more creative work.

For this project, we'll consider a web application from Project 3, where UAT is necessary before deploying the solution into production. Testers will have a dataset with input and expected output data. They'll input each data record into the web application and verify if the expected output is generated. RPA can automate this repetitive process.

## Prerequisites
Before starting this project, ensure the following:

  - Create a UiPath Automation Cloud account.
  - Download UiPath Studio Community Edition to your computer.
  - Access the web application for which you'll perform UI automation.
  - Retrieve the Excel file containing the test data.
Implementation
We've provided a web application for students to use, which can be accessed at https://cmpg323-ecopowerlogistics.azurewebsites.net/. For this project, focus on adapting the UiPath solution for RPA testing.

# Requirements
The project can be broken down into the following tasks:

## GitHub Administration

Create and configure a GitHub repository named 'CMPG 323 Project 4 - <add your student number>'.
Create a README.md file to describe the project and provide guidance for stakeholders.
Project Progress

Commit and push your solution to source control throughout the project.
Iteratively update the GitHub project to demonstrate your progress.
Project Setup

Clone your GitHub repository.
Install UiPath Studio.
Create a new UiPath process named 'Connected Office Web Application – User Acceptance Testing'.
User Acceptance Testing

Read input data from an Excel file into a data table in UiPath.
Ensure data is correctly processed within UiPath.
UI Automation

For each record in the data table, navigate to the web application's data entry page.
Insert data from the record into the web application's fields.
Submit the data to create a new record.
Navigate to the page where the new record can be viewed.
Record Results

Update the data table to indicate whether testing passed or failed.
Update the Excel spreadsheet with the testing results.
Project Close-out

Deploy the UiPath solution.
Explain in the README.md how to use the report.
Create a reference list of websites and resources used.
