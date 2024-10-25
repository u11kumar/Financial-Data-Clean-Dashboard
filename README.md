# Financial-Data-Clean-Dashboard

# Excel Data Cleaning and Visualization with SQL, Streamlit, and Plotly

This project demonstrates how to clean, analyze, and visualize an Excel dataset by embedding SQL queries into a Python environment. Using Streamlit and DuckDB, the project builds an interactive dashboard with Plotly for data visualization, providing a seamless, user-friendly interface for data insights.

Project is live on [here](https://finacial-dashboard.streamlit.app/)

First download the dataset from the repo and then upload on the site.

## Table of Contents

- [Overview](#overview)
- [Project](#project)
- [Features](#features)
- [Technologies Used](#technologies-used)

## Overview

The main goal of this project is to clean and visualize data from an Excel sheet using SQL commands embedded in a Python environment. This is achieved through three key steps:

1. **Load an Excel File**: Users upload an Excel workbook, which is then loaded into a Pandas DataFrame and displayed within a Streamlit app for a live preview.
2. **Data Formatting with SQL**: Using DuckDB, the data in the DataFrame is formatted and analyzed through SQL commands.
3. **Interactive Visualization**: The cleaned and analyzed data is visualized with Plotly, and the Streamlit app is built with a sidebar, horizontal layout, and expanders for easy navigation and exploration.

## Project

A dashboard using streamlit and cleaning and making chat and visuals from it.

## Features

- **Streamlit File Upload**: Allows users to upload an Excel file, which is then read into a Pandas DataFrame for further processing.
- **SQL Data Manipulation**: DuckDB SQL commands are used directly on the DataFrame for data transformation and cleaning.
- **Interactive Data Visualization**: Plotly charts, including scatter plots and bar charts, display the cleaned data with interactive elements.
- **Streamlit Layout**: Custom layout with horizontal sections, sidebar, and expandable sections for a streamlined user experience.

## Technologies Used

- [Streamlit](https://streamlit.io/): For building the interactive dashboard and managing file uploads.
- [Pandas](https://pandas.pydata.org/): For handling and manipulating the data from Excel files.
- [DuckDB](https://duckdb.org/): For executing SQL queries on DataFrames.
- [Plotly](https://plotly.com/python/): For interactive data visualization.
- Python libraries: `random` for generating sample data.
