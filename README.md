# IE0005 Mini Project – What’s Cooking? Cuisine Classification

This repository contains a **team-based mini project** for **IE0005: Introduction to Data Science & Artificial Intelligence**.

The project uses the Kaggle **“What’s Cooking?”** dataset to build and evaluate machine learning models for **cuisine classification** based on recipe ingredients.

---

## Contributors

This project was completed as a team-based mini project for IE0005.

- **Lily Ng Shia Li**
- **Malvin** ([@malvinjuju](https://github.com/malvinjuju))
- **Ilakkiyaa**
- **Samantha**

---

## Project Overview

The goal of this project is to predict the cuisine of a recipe using its list of ingredients.  
We explore the dataset, perform data cleaning and feature extraction, and apply multiple machine learning models to compare performance.

### Models implemented
- Decision Tree
- K-Nearest Neighbors (KNN)
- Random Forest

---

## Repository Structure

```
IE0005-MiniProject/
├── notebooks/
│   ├── IE0005MiniProjectDataCleaning.ipynb
│   ├── IE0005MiniProjectExplolatoryAnalysis.ipynb
│   ├── MiniProject_KNN.ipynb
│   ├── MiniProject_Code (2).ipynb        # Random Forest
│   ├── MiniProject_Dairy.ipynb           # Decision Tree
│   ├── MiniProject_Peanut.ipynb
│   ├── MiniProject_Seafood.ipynb
│   └── MiniProject_eggs.ipynb
├── IE0005 Mini Project.pdf               # Slides / Report
├── README.md
└── .gitignore

```
---

## Dataset (Not Included)

This is a **public repository**, so the dataset files are **not included**.

We use the Kaggle dataset:

**What’s Cooking?**  
https://www.kaggle.com/c/whats-cooking

### How to set up the dataset locally

1. Download `train.json` from Kaggle.
2. Create a folder called `data/` in the project root.
3. Place `train.json` inside the folder:

```
IE0005-MiniProject/
└── data/
    └── train.json
```

> The `data/` folder is ignored by Git to prevent accidental uploads of dataset files.

---

## Requirements

Install the required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn

