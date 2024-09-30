# Amazon Product Recommendation System

## Project Overview
This project aims to build a product recommendation system for Amazon using both **collaborative filtering** and **content-based filtering** algorithms. The system is designed to enhance the customer experience by providing personalized product recommendations, thereby increasing customer satisfaction and driving sales.

The project utilizes various machine learning algorithms to create recommendations based on user behavior and product attributes.

### Key Features:
- **Collaborative Filtering** (User-based and Item-based): Recommends products based on the interaction between users and items.
- **Content-Based Filtering**: Recommends products by analyzing similarities between product attributes.
- **Matrix Factorization**: Used to decompose the user-item interaction matrix to predict missing interactions.
- **K-Nearest Neighbors (KNN)**: Used to find similar users or products.
- **Hybrid Model**: Combines both collaborative and content-based filtering for enhanced recommendations.

---

## Dataset

The dataset used for this project is available on Kaggle and contains Amazon product reviews. You can download the dataset using the following link:

[Amazon Product Reviews Dataset](https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews)

### Dataset Details:

- **Total Records**: 568,454
- **Total Columns**: 10
- **Domain**: amazon.com
- **File Extension**: CSV

#### Available Fields:
- **Id**: Unique identifier for each review.
- **ProductId**: Unique identifier for each product.
- **UserId**: Unique identifier for each user.
- **ProfileName**: Name of the user who wrote the review.
- **HelpfulnessNumerator**: Number of users who found the review helpful.
- **HelpfulnessDenominator**: Total number of users who rated the helpfulness of the review.
- **Score**: The rating given by the user (1 to 5 stars).
- **Time**: Time the review was written (in UNIX timestamp).
- **Summary**: A brief summary of the review.
- **Text**: The full text of the review.

---

## Tools & Technologies

The following tools and libraries were used to develop the recommendation system:

- **Programming Language**: Python
- **Libraries**:
  - `scikit-learn`: For building machine learning models and performing feature engineering.
  - `PyTorch`: For deep learning models and matrix factorization.
  - `Surprise`: For implementing collaborative filtering and matrix factorization.
  - `Pandas`: For data manipulation and analysis.
  - `NumPy`: For numerical operations.
  - `Matplotlib` and `Seaborn`: For data visualization.

---

## Recommendation Algorithms

### 1. Collaborative Filtering
- **User-based Filtering**: Recommends products to a user based on what similar users have liked.
- **Item-based Filtering**: Recommends products similar to those the user has liked before.

### 2. Content-Based Filtering
- Recommends products by comparing attributes (e.g., product descriptions, reviews) to what the user has liked.

### 3. Matrix Factorization
- Uses techniques like Singular Value Decomposition (SVD) to factorize the user-item interaction matrix and predict ratings for unseen items.

### 4. K-Nearest Neighbors (KNN)
- Finds products or users that are similar to a given user or product based on similarity metrics.


