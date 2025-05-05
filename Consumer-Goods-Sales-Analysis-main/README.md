# Consumer-Goods-Sales-Analysis
Overview
This project focuses on analyzing and visualizing the regional sales across the United States in between 2015-2016. The datasets used are completely fictitious and solely made-up just for data analysis case study.

The repository directory structure is as follows:

Consumer-Goods-Sales-Analysis
├─ 01_SOURCE
├─ 02_ETL
├─ 03_DATA
├─ 04_ANALYSIS
├─ 05_DASHBOARD
├─ 06_RESOURCES

The type of content present in the directories is as follows:

01_SOURCE

This directory contains the the received/downloaded raw data that needs to be cleaned and organized to ease out the data analysis and visualization process.

02_ETL

This directory contains the ETL script that takes the raw dataset(s) as input, transforms it and exports an analysis-ready dataset into the 03_DATA directory.

In this project; we've exported the clean datasets in the form of comma separated flat files into the FLATFILES folder and in the form of SQLite database into the DATABASE folder.

03_DATA

This directory contains the data that can be directly used for exploratory data analysis and data visualization purposes.

In this project; we have two sub-folders under the 03_DATA folder that holds the following:

FLATFILES: comma separated flat files
DATABASE: SQLite Database
Both folders has the exact same data but in two different format.

04_ANALYSIS

This directory contains the python notebooks that analyzes the clean dataset to generate insights.

For analyzing the data with Jupyter Notebook; we have used the clean dataset present in the SQLite database.

05_DASHBOARD

This directory contains the markdown file with an embedded Power BI report link that visualizes the data.

The Power BI dashboard contains slicers, cross-filtering and other advance capabilities that end user can play with to visualize a specific facet of the data or, to get additional insights.

06_RESOURCES

This directory contains images, icons, layouts, etc. that are used in this project.

Prerequisites
The major skills that are required as prerequisite to fully understand this project are as follows:

Basics of Python & Jupyter Notebook
Basics of Power BI
In order to complete the project, I've used the following applications and libraries

Python
Python libraries mentioned in requirements.txt file
Jupyter Notebook
Visual Studio Code
Microsoft Power BI
The choice of applications & their installation might vary based on individual preferences & system settings.

Architecture
The project architecture is quite straight forward and can be explained through the below image:

Process Architecture![process_architecture](https://user-images.githubusercontent.com/106774987/228347248-01279b2e-16f4-49c8-a597-3a70a9d323d2.png)


As shown in the above workflow; we are first performing necessary cleaning and transformation in the received raw dataset using Python and exporting the clean dataset as comma-separated flat files and also as a SQLite database.

Finally; we leverage the clean & analysis-ready dataset for exploratory data analysis (EDA) using Jupyter Notebook and creating an insightful report using Power BI.


Demo![dashboard_pbix](https://user-images.githubusercontent.com/106774987/228347340-8b068670-7835-4365-bddc-0b171ec1ac6d.png)

The interactive Power BI dashboard can be viewed here:
