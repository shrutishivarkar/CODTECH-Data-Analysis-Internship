# TASK-4: SENTIMENT ANALYSIS USING NLP
## Internship Project – CODTECH

---

## OBJECTIVE
Perform sentiment analysis on textual data to classify user opinions as Negative, Neutral, or Positive, helping organizations understand customer feedback, brand perception, and user behavior.

---

## DATASET
Tweet/review dataset containing:
* text → user message
* sentiment → label (negative, neutral, positive)
* Additional demographic and time-related attributes

---

## ANALYSIS PERFORMED

### Data Preprocessing
* Removed URLs, numbers, punctuation, and special characters
* Converted text to lowercase
* Handled missing values safely

### Feature Engineering
* Transformed text into numerical vectors using TF-IDF

### Model Training
* Algorithm used: Logistic Regression
* Train–test split: 80% / 20%

### Model Evaluation
* Accuracy achieved: 64%
* Neutral class predicted most accurately
* Positive and Negative classes moderately classified

---

## KEY INSIGHTS
* Neutral sentiment dominates the dataset.
* Positive and negative texts often share similar words, causing overlap.
* TF-IDF effectively captures important word patterns.
* The model can support customer feedback analysis, product reviews, and brand monitoring.

---

## TOOLS USED
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## DELIVERABLES
* Sentiment Analysis Jupyter Notebook
* Confusion Matrix & Evaluation Results
* Dataset file
* Project README documentation
