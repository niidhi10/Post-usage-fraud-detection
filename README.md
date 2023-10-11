# Post-Usage-Fraud-Detection-System
## Brief Abstract
In the evolving landscape of online retail, a troubling trend has emerged – customers placing orders for products, utilizing them, and subsequently returning them. This practice, termed 'Post-Usage Return Fraud,' involves customers acquiring items for specific needs, often single-use, and orchestrating returns by citing product defects or dissatisfaction. Our project aims to tackle this challenge by developing a machine-learning framework that effectively identifies fraudulent return requests from legitimate ones.
## High-Level Architecture
The chosen approach to address this issue is the Bagging Random Forest technique. Bagging Random Forest is an ensemble learning method that combines multiple decision trees, each trained on different data subsets (Bagging). This technique introduces feature randomness by considering only random feature subsets at each tree split (Random Forest). The final prediction is derived through voting (classification) or averaging (regression) of individual tree outputs. This approach mitigates overfitting, enhances accuracy, and strengthens model robustness.
![image](https://github.com/niidhi10/Post-usage-fraud-detection/assets/99705717/fc9aaf5d-9623-472a-9fbd-84db1a8ea221)
![image](https://github.com/niidhi10/Post-usage-fraud-detection/assets/99705717/1b369e2c-ee8b-49c4-a145-b6f63a843598)
## Dataset Overview
The dataset comprises detailed order information from a retail company, encompassing buyer details, product specifics, shop information, order numbers, and order statuses.
## Fraud Detection Mechanism 
The machine learning model will identify potential fraud by detecting anomalous spikes in returns from specific customers or a disproportionately high volume of returns to particular stores, indicating potential fraudulent activities at those locations.

---
*Note: This project was created as a part of a Hackathon and was originally uploaded by me and my team on [this](https://github.com/gitteamno56/team_56) repository.*
