# Swiggy_Recommentation
# Restaurant Recommendation System

## 📌 Project Overview

This project is a **Restaurant Recommendation System** that helps users discover restaurants based on their preferences such as **city**, **cuisine**, **cost**, and **rating**. Using **clustering** or **similarity-based methods**, the system provides personalized restaurant suggestions through an interactive **Streamlit web application**.

---

## 🎯 Objectives

- Clean and preprocess restaurant data from a CSV file.
- Encode categorical features using One-Hot Encoding.
- Build a recommendation engine using clustering or similarity techniques.
- Develop a user-friendly Streamlit application to display recommendations.

---

## 💼 Business Use Cases

- **Personalized Recommendations**: Guide users to restaurants aligned with their preferences.
- **Enhanced Customer Experience**: Simplify decision-making for users.
- **Market Insights**: Understand user behavior for targeted marketing.
- **Operational Efficiency**: Help restaurants align offerings with customer demand.

---

## 🧠 Approach

### 1. Data Understanding and Cleaning
- Drop duplicate entries.
- Handle missing values appropriately.
- Save cleaned dataset to `cleaned_data.csv`.

### 2. Data Preprocessing
- Apply One-Hot Encoding to `name`, `city`, and `cuisine`.
- Save encoder as `encoder.pkl`.
- Create numerical dataset `encoded_data.csv`.
- Maintain index alignment with `cleaned_data.csv`.

### 3. Recommendation Methodology
- Use **K-Means Clustering** or **Cosine Similarity** to group similar restaurants.
- Input user preferences and compute top recommendations.
- Map result indices from `encoded_data.csv` to `cleaned_data.csv`.

### 4. Streamlit Web Application
- Accept user input for `city`, `cuisine`, `rating`, and `cost`.
- Display top restaurant recommendations in a clean and intuitive UI.

---
## 🛠️ Technologies Used

- Python
- Pandas, NumPy, Scikit-learn
- Streamlit
- Pickle

---
📈 Results
Cleaned Dataset: Missing values and duplicates removed.

Encoded Dataset: Ready for ML processing with One-Hot Encoding.

Streamlit App: Real-time personalized restaurant suggestions.

Recommendation Engine: Based on clustering or similarity measures.
