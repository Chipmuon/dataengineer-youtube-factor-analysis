# dataengineer-youtube-factor-analysis
About Data Engineering YouTube Analysis Project by Chipmuon

## Overview

This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

## Project Goals
1. ETL System — We are getting data in raw format, transforming this data into the proper format
2. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
3. Scalability — As the size of our data increases, we need to make sure our system scales with it
4. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use Azure
5. Reporting — Build a dashboard to get answers to the question we asked earlier

## Services we will be using
## Programming Language - Python
Azure Portal Platform
1. Azure Blob Storage
2. Azure Databricks
3. Azure Data Factory
4. PowerBI

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpg">

## Data Model 
<img src="data_model.jpg">

