# OSRS Player Segmentation

This project explores player archetypes in Old School RuneScape using public Hiscores data and unsupervised machine learning.

## Project Goal

The goal of this project is to discover hidden player groups based on their skill levels and progression patterns.

## Main Research Question

Can meaningful Old School RuneScape player archetypes be identified using clustering methods on Hiscores data?

## Planned Methods

- Data collection from OSRS Hiscores
- Data cleaning and preprocessing
- Feature engineering
- K-Means clustering
- Cluster evaluation with Elbow Method and Silhouette Score
- PCA-based visualization
- Interpretation of player archetypes

## Tech Stack

- Python
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- requests

## Repository Structure

```text
osrs-player-segmentation/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
├── images/
├── README.md
├── requirements.txt
└── .gitignore