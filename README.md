# Smart-Predictive-Modeling-for-Rental-Property-Prices

Problem Statement: In real estate, determining precise rental prices is vital for landlords, tenants, and property managers. This project tackles the challenge by creating a data-driven model to predict residential rental prices. The aim is to provide accurate insights that empower stakeholders in making informed decisions, optimizing pricing strategies, and enhancing overall market

NAME : RAMYA KRISHNAN A

BATCH: DW75DW76

DOMAIN : DATA SCIENCE

DEMO VIDEO URL :https://www.linkedin.com/posts/ramyakrishnan19_excited-to-share-a-glimpse-of-my-latest-project-activity-7168129414369595392-Y7Gv?utm_source=share&utm_medium=member_desktop

Linked in URL : www.linkedin.com/in/ramyakrishnan19

# Libraries for preprocessing
    import pandas as pd
    import numpy as np
    import json
    from sklearn.preprocessing import OrdinalEncoder
    import matplotlib.pyplot as plt
    import seaborn as sns
    from datetime import date
    import mysql.connector
    import plotly.express as px
    import streamlit as st
    from streamlit_option_menu import option_menu

# Libraries for ML Process
    
    from sklearn.preprocessing import OrdinalEncoder
    from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
    from sklearn.tree import DecisionTreeRegressor
    from sklearn.ensemble import ExtraTreesRegressor
    from sklearn.ensemble import RandomForestRegressor
    from sklearn.model_selection import train_test_split, GridSearchCV
    import pickle


# Overview

This repository contains a predictive modeling project aimed at accurately forecasting rental prices for residential properties. Leveraging historical rental data and property attributes, the project focuses on providing insights for landlords, tenants, and property management companies.

# Project Highlights

## Data-Driven Insights:

Identified key factors influencing rental prices through a thorough analysis.

Developed a reliable RandomForest Regressor model for accurate predictions.

## Database Management:

Implemented SQL functionalities for effective data organization.

Created, migrated, and dropped tables for maintaining a structured database.

# Predictive Modeling

## Model Selection:

Utilized DecisionTree, ExtraTree, and RandomForest Regressor models.

RandomForest Regressor selected based on superior R2 scores.

## Model Deployment:

Trained model deployed for real-time rent predictions.

Pickle file used for efficient model storage and retrieval.

# Home

## User-Friendly Interface:

The home section serves as the starting point, offering a user-friendly interface to navigate through various functionalities seamlessly.

It provides an overview of the application and guides users to explore different features conveniently.

<img width="1440" alt="Screenshot 2024-02-25 at 12 41 54 PM" src="https://github.com/Ramya19rk/Smart-Predictive-Modeling-for-Rental-Property-Prices/assets/145639838/bac8a6ba-8bff-46e6-af74-4fcc051a503e">


# Migrate to SQL

## Features include Migration to SQL:

Users can easily manage their data by creating, migrating, or dropping tables in a SQL database.

This feature ensures that the application operates with structured and organized data, optimizing the overall data management process.

<img width="1440" alt="Screenshot 2024-02-25 at 12 42 17 PM" src="https://github.com/Ramya19rk/Smart-Predictive-Modeling-for-Rental-Property-Prices/assets/145639838/979ea442-6cb4-465d-b747-4bb68379cbfe">


# Prediction

## Rent Prediction:

Users have the ability to predict rental prices for residential properties by inputting various details such as activation date, latitude, longitude, and other property features.

The application leverages a trained RandomForest Regressor model to provide accurate and reliable rent predictions.

<img width="1440" alt="Screenshot 2024-02-25 at 12 42 32 PM" src="https://github.com/Ramya19rk/Smart-Predictive-Modeling-for-Rental-Property-Prices/assets/145639838/7d436fd5-0ec4-4005-9139-255356378844">


# Data Analysis

## Data Analysis Charts:

This section offers users a visual exploration of the dataset through various charts, enhancing the understanding of trends and patterns in rental data.

Users can choose from different types of charts such as Bar, Line, Pie, and Scatter to gain insights into different aspects of the rental property market.

<img width="1440" alt="Screenshot 2024-02-25 at 12 43 10 PM" src="https://github.com/Ramya19rk/Smart-Predictive-Modeling-for-Rental-Property-Prices/assets/145639838/487f3a23-c3a0-4c0e-9b34-53145629f242">
<img width="1440" alt="Screenshot 2024-02-25 at 12 43 03 PM" src="https://github.com/Ramya19rk/Smart-Predictive-Modeling-for-Rental-Property-Prices/assets/145639838/adbf465b-c4d2-4d29-815d-348975524639">
<img width="1440" alt="Screenshot 2024-02-25 at 12 42 56 PM" src="https://github.com/Ramya19rk/Smart-Predictive-Modeling-for-Rental-Property-Prices/assets/145639838/87d5efa7-0003-45f6-9210-ff2795f0f892">
<img width="1440" alt="Screenshot 2024-02-25 at 12 42 49 PM" src="https://github.com/Ramya19rk/Smart-Predictive-Modeling-for-Rental-Property-Prices/assets/145639838/89c597bf-055b-4f23-a78e-85e22ccdb5cc">


# Exit

The exit section provides a graceful way for users to conclude their interaction with the application.

Users receive a thank-you message, creating a positive conclusion to their engagement with the Smart Predictive Modeling application.

<img width="1440" alt="Screenshot 2024-02-25 at 12 43 25 PM" src="https://github.com/Ramya19rk/Smart-Predictive-Modeling-for-Rental-Property-Prices/assets/145639838/84c00823-186a-4ebc-89fc-15471f5523d9">








