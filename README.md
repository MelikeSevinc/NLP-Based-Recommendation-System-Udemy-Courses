# NLP-Based-Recommendation-System-Udemy-Courses
This project demonstrates an NLP-based recommendation system designed to suggest Udemy courses based on user preferences. The system leverages **TF-IDF** and **BERT embeddings** for course similarity calculations.

## Project Steps

### 1. Data Loading
The Udemy course dataset is loaded into a pandas DataFrame for analysis.

### 2. Exploratory Data Analysis (EDA)
- **Missing Values:** Identified and handled.
- **Category Distribution:** Visualized the distribution of courses across categories.
- **Level Analysis:** Analyzed the instructional levels to identify dominant levels.

### 3. Preprocessing
- Cleaned textual data for better processing.
- Vectorized course objectives and descriptions using **TF-IDF**.
- Generated **BERT embeddings** for semantic understanding.

### 4. Similarity Calculation
- Calculated pairwise **cosine similarity** between courses based on:
  - **TF-IDF vectors**.
  - **BERT embeddings**.

## Recommendation Algorithm
1. User inputs a course title.
2. Similarity scores are calculated using **cosine similarity** for:
   - **TF-IDF vectors**.
   - **BERT embeddings**.
3. Results are filtered by user-selected **category** and **instructional level**.
