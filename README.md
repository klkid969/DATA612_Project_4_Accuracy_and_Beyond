# DATA 612 – Project 4: Accuracy and Beyond

**Author:** Kevin Martin  
**Course:** DATA 612 – Recommender Systems  
**Program:** Master of Science in Data Science  
**Institution:** CUNY School of Professional Studies

## Project Overview

The goal of this project is to compare two recommender system approaches while looking beyond prediction accuracy. In previous projects, I focused on building recommender systems and evaluating how accurately they predicted user ratings. For this project, I wanted to take the next step by comparing Item-Based Collaborative Filtering and SVD Matrix Factorization while also considering how user experience can influence recommendation quality.

To keep the comparison consistent, I continued using the synthetic movie ratings dataset developed in the previous projects. This allowed me to focus on evaluating the recommendation algorithms rather than introducing differences caused by a new dataset.

## Project Objectives

- Build an Item-Based Collaborative Filtering recommender.
- Build an SVD Matrix Factorization recommender.
- Compare recommendation accuracy between the two approaches.
- Explore novelty as a user-experience recommendation goal.
- Discuss the tradeoff between prediction accuracy and user experience.
- Explain why some recommender system improvements require online evaluation rather than offline metrics alone.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Repository Contents

- `DATA612_Project4.ipynb` – Complete Jupyter Notebook containing the analysis, code, visualizations, and interpretations.
- `DATA612_Project4.pdf` – PDF version of the completed notebook.

## What I Learned

One of the biggest lessons from this project is that the most accurate recommender system is not always the one that provides the best experience for the user. Comparing multiple recommendation approaches and considering user-experience goals such as novelty helped me better understand that recommender systems are designed to balance several objectives rather than optimize a single metric.
