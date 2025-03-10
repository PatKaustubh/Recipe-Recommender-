# 🍽️ Recipe Recommender Assignment

## 📌 Overview
Welcome to the **Recipe Recommender Assignment**! Your goal is to develop a **personalized recipe recommender system** that generates recommendations for given `user_id`s. 

### 💡 Why is This Important?
Recommender systems in real-world applications must deliver results **instantly**. Imagine a YouTube recommendations panel taking 20 minutes to load—you’d likely switch platforms. **Prediction speed is often more critical than accuracy in recommender systems.**

### 🔥 Real-World Challenges in Recommender Systems:
- **Scalability**: Handling large datasets efficiently.
- **Prediction Latency**: Recommendations must be generated in real time.
- **Advanced Algorithms**: Leveraging cutting-edge techniques for better performance.
- **Big Data Hardware**: Large-scale clusters are often used for training models.

Since we lack deep learning models or industrial-scale hardware, we will work with **sub-sampled data** and optimize our methods accordingly.

---
## 📊 Dataset Information
The dataset used in this assignment mirrors the structure from the previous project but does **not** include newly created features. If needed, you must **recalculate these features.**

### 🔗 **Downloadable Data Links**
- [📥 Raw Ratings (small)](https://raw-recipes-clean-upgrad.s3.amazonaws.com/raw_ratings_small.csv)
- [📥 Raw Recipes (small)](https://raw-recipes-clean-upgrad.s3.amazonaws.com/raw_recipies_small.csv)
- [📥 Cleaned Recipes](https://raw-recipes-clean-upgrad.s3.amazonaws.com/RAW_recipes_cleaned.csv)
## 🛠️ Methodology & Approach
You are expected to use **Apache Spark** to build the **machine learning model**. The algorithms used will be:

1. **Alternating Least Squares (ALS) Collaborative Filtering** 🔄
2. **K-Nearest Neighbors (KNN) for Similarity-based Recommendations** 🔍 *(Optional for a hybrid recommender)*

