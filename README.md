# Restaurant Recommendation System using Similarity Measures

This project builds a **Restaurant Recommendation System** using Python and three popular similarity/distance techniques:

- **Cosine Similarity**
- **Manhattan Distance**
- **Euclidean Distance**

The system recommends restaurants similar to a selected restaurant based on features such as cuisine, average cost, price range, aggregate rating, and votes.

---

## Project Overview

In this project:

- A restaurant dataset is loaded
- Important columns are selected
- Cuisine values are converted into machine-readable format
- Features are scaled
- Similarity and distance matrices are created
- Top similar restaurants are recommended

This project is useful for:

- Machine Learning beginners
- Recommendation system projects
- College mini projects
- Python practice projects

---

## Similarity / Distance Methods Used

### 1. Cosine Similarity
Measures how similar two restaurants are based on the angle between their feature vectors.

### 2. Manhattan Distance
Measures the total absolute difference between restaurant features.

### 3. Euclidean Distance
Measures the straight-line distance between restaurant feature vectors.

---

## Features Used

The following columns are used from the dataset:

- Restaurant Name
- City
- Cuisines
- Average Cost for two
- Price range
- Aggregate rating
- Votes

---

## Project Workflow

1. Download the dataset
2. Load the CSV file
3. Select important columns
4. Remove missing values
5. Convert cuisines into list format
6. Apply one-hot encoding on cuisines
7. Build final feature table
8. Scale the features using MinMaxScaler
9. Calculate:
   - Cosine Similarity
   - Euclidean Distance
   - Manhattan Distance
10. Recommend top similar restaurants

---

## Tech Stack

- Python
- Pandas
- Scikit-learn
- KaggleHub

---

## Installation

Clone the repository:

```bash
git clone https://github.com/SineNitish/restaurant-recommendation-system-similarity.git
cd restaurant-recommendation-system-similarity
