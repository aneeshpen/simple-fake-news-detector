
# Fake News Detection 📰🔍

A machine learning mini project that detects whether a news article is fake or real using the **Passive Aggressive Classifier** and **TF-IDF Vectorization**.

---

## Features
- Classifies news articles as `FAKE` or `REAL`.
- Achieved an accuracy of **94%** on the dataset.
- Implements **TF-IDF Vectorizer** for text feature extraction.
- Hyperparameter tuning to optimize model performance.

---

## Dataset
The dataset used for this project is `news.csv`. It contains:
- `text`: The main content of the news article.
- `label`: `FAKE` or `REAL`.

**Note:** The dataset is included in the repository or can be downloaded from [here](https://data-flair.training/blogs/advanced-python-project-detecting-fake-news/).

---

## Workflow
1. **Data Preprocessing**:
   - Removed unnecessary columns (`Unnamed`, `title`).
   - Split data into training and testing sets.

2. **Text Vectorization**:
   - Used `TfidfVectorizer` to convert text data into numerical form.

3. **Model Training**:
   - Used `PassiveAggressiveClassifier` to train the model.
   - Tuned hyperparameters like `max_iter`, `C`, and `tol`.

4. **Model Evaluation**:
   - Achieved **94% accuracy**.
   - Confusion Matrix:
     ```
     [[613,  38],
      [ 34, 582]]
     ```

---
