# Predicting Tourism Trends in India

# Overview
This project analyzes tourism trends in India using historical data on traffic volume, weather conditions, and special events. The goal is to develop predictive models that help understand how these factors influence tourism patterns.

# Files in Repository
• predicting_tourism_trends.ipynb - Contains the code for data analysis and predictive modeling.
• tourism.csv - The dataset used for this project. This dataset is sourced from Kaggle.

# Introduction
The dataset includes monthly records for different states in India throughout 2024, covering:
• Foreign Tourist Arrivals (FTAs)
• Domestic Tourist Arrivals (DTAs)
• Weather conditions
• Special events (e.g., festivals)
By analyzing these factors, the project provides insights into tourism trends that can aid city planning, resource management, and infrastructure development.

# Problem Statement
Analyzing historical tourism patterns to predict the impact of weather conditions and special events on future tourism trends in India, aiding in effective planning and management.

# Approach
1. Data Analysis
   • Exploring historical data on FTAs, DTAs, weather, and events.
   • Visualizing trends and patterns.
2. Data Preprocessing
   • Handling missing values and outliers.
   • Encoding categorical variables.
3. Model Building
   • Linear Regression for predicting numerical traffic levels.
   • Random Forest Classifier for categorizing traffic levels into Low, Medium, and High.
4. GUI Development
   • Creating a Tkinter-based interface for predictions.

# Methodology
1. Data Preprocessing
   • Identified and handled missing values.
   • Encoded categorical variables using Label Encoding.
2. Feature Selection
   • Selected key features (FTAs, DTAs, Weather) for modeling.
   • Target variable: Traffic Level.
3. Data Splitting
   • Training set: 80%
   • Testing set: 20%
4. Visualization
   • Used plots to analyze feature distributions.
5. Model Training
   • Linear Regression for numerical traffic predictions.
   • Random Forest Classifier for categorical predictions.
6. GUI Development
   • Created an interactive Tkinter-based interface.

# Conclusion
• Weather conditions and events significantly influence tourism trends.
• Rainy weather increases congestion, while festivals boost traffic in urban regions.
• These insights can help urban planners and tourism departments anticipate and manage visitor flow.

