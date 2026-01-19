# Football Scouting System – Player Similarity Analysis

## Overview
The Football Scouting System is a data-driven project designed to identify similar football players based on match performance and physical attributes. The system supports scouting and recruitment decisions by comparing players using statistical similarity rather than subjective judgment.

This project uses unsupervised learning techniques, specifically cosine similarity, to measure how closely players resemble each other across multiple performance metrics.

---

## Problem Statement
Traditional football scouting often relies on manual observation and subjective analysis. This project aims to:
- Reduce bias in player comparison
- Enable data-driven talent identification
- Provide a scalable method to compare players across leagues and positions

---

## Approach
1. Data Collection  
   - Player match statistics and physical attributes

2. Data Preprocessing  
   - Handling missing values  
   - Feature selection  
   - Normalization of numerical features  

3. Feature Engineering  
   - Aggregation of performance metrics  
   - Scaling to ensure fair similarity comparison  

4. Similarity Computation  
   - Applied cosine similarity to compute player likeness  
   - Ranked players based on similarity scores  

5. Result Interpretation  
   - Identified players with similar playing styles and performance profiles  

---

## Technologies Used
- Programming Language: Python  
- Libraries:  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Matplotlib  
  - Seaborn  

---

## Key Features
- Unsupervised player similarity analysis
- Normalized and feature-engineered player metrics
- Scalable framework for scouting use cases
- Data-driven support for recruitment decisions

---

