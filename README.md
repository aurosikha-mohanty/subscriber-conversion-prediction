#  Freemium to Premium: Predictive Targeting for XYZ Music

##  Project Overview
This repository presents a predictive modeling solution to help **XYZ Music**, a freemium-based platform, effectively identify users most likely to convert to premium subscribers. By analyzing behavioral, demographic, and engagement data from a past campaign, the model aims to significantly improve conversion efficiency and guide smarter targeting strategies.

---

##  Business Context
- **Client**: XYZ Music
- **Challenge**: Only 3.7% of 40,000 users converted in the last campaign.
- **Objective**: Improve targeting to maximize conversions and marketing ROI.
 
---

##  Workflow Summary

### 1. **Data Exploration**
- Campaign engagement + 6-month adoption labels
- Feature groups: Demographics, Social Signals, Listening Behavior, Temporal Shifts

### 2. **Feature Engineering**
- Created delta-based features (`deltaSongsListened`, `deltaLovedTracks`, etc.)
- Label encoding and outlier handling

### 3. **Modeling & Evaluation**
- Algorithms Tested: Decision Trees, Logistic Regression, XGBoost
- Final Model Optimized for **Recall** and **Business Lift**
- Performance:
  - **7.1% expected conversion** vs. 3.7% baseline
  - **85% recall** on premium adopters
  - Lift: 2× when targeting top 20% ranked users

---

##  Strategic Recommendations

| Segment           | Action |
|------------------|--------|
|  Top 20% Users | Prioritize for campaign targeting to double conversion rates |
|  Threshold Tuning | Optimize cutoff based on marketing budget & risk |
|  Feedback Loop  | Retrain model with each new campaign for compounding improvements |

---


##  Collaborators

- Aurosikha Mohanty  
- Aditya Govind Ravi Krishnan  
- Rita Wang  
- Abhinav Maharana  
- Dhairya Patadia  

---

##  License

This project is made available for **educational and review purposes only**.

You may **view or copy** this repository for reference. However, **modification, redistribution, or reuse** of any part of the content is strictly prohibited without explicit written permission.

© 2024 Group 13. All rights reserved.

