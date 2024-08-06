# Video Game Sales Analysis

This repository contains a comprehensive analysis of video game sales evolution across different regions and the dominance of platforms, genres, and publishers over time. Interactive visualizations created in PowerBI are used to provide a detailed view of the video game market from 1980 to 2016.

## Contents

1. [Introduction](#introduction)
2. [Dataset Selection](#dataset-selection)
3. [Dashboard Creation](#dashboard-creation)
   - [General Dashboard](#general-dashboard)
   - [Sales Evolution Dashboard](#sales-evolution-dashboard)
   - [Platforms and Publishers Dashboard](#platforms-and-publishers-dashboard)

## Introduction

The analysis focuses on answering key questions about video game sales using PowerBI. The dashboards created address the following questions:

- What is the proportion of sales by region or genre within a given range of years?
- What is the total sales by region or globally within a given range of years?
- What is the evolution of sales numbers in each region?
- How does the proportion of sales numbers evolve over time?
- What dominance do different platforms have over the years?
- What market share do different video game publishers maintain?

## Dataset Selection

A dataset from Kaggle related to video games that have sold more than 100,000 copies from 1980 to 2016 is used. The dataset includes sales data for regions including Europe, North America, Japan, and other regions. The data is in CSV format.

- **Dataset URL**: [Kaggle - Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)

**Dataset Columns**:

- `Rank`: Ranking based on the number of video game sales.
- `Name`: Name of the video game.
- `Platform`: Platform of the video game.
- `Year`: Release year of the video game.
- `Genre`: Genre of the video game.
- `Publisher`: Publisher of the video game.
- `NA_Sales`: Sales in North America (in millions).
- `EU_Sales`: Sales in Europe (in millions).
- `JP_Sales`: Sales in Japan (in millions).
- `Other_Sales`: Sales in other regions (in millions).
- `Global_Sales`: Global sales (in millions).

## Dashboard Creation

The visualizations in PowerBI are divided into three sections:

### General Dashboard

- **Description**: Provides an overview of video game sales.
- **Features**:
  - Filters for name, genre, platform, publisher, and release year.
  - Pie charts showing the proportion of sales by region and genre.
  - Table with detailed information on games and sales.

### Sales Evolution Dashboard

- **Description**: Focuses on the evolution of sales by region and platform over time.
- **Features**:
  - KPIs representing sales by region and globally.
  - Line chart showing the sales evolution from 1980 to 2016.
  - Stacked bar chart illustrating the total sales by year and the proportion of sales by region.

### Platforms and Publishers Dashboard

- **Description**: Analyzes the dominance of platforms and publishers over the years.
- **Features**:
  - Filters for selecting genre and year range.
  - Stacked bar chart showing the dominance of platforms over the years.
  - Tree map representing the market share of publishers.
---

Explore the analysis and discover trends in the video game market!
