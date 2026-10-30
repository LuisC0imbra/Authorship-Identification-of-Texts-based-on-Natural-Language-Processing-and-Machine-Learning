# NLP-Based Authorship Identification Using Machine Learning & Deep Learning

### Master's Dissertation Project | Grade: 18/20

A Python-based Natural Language Processing (NLP) and Machine Learning project focused on identifying the authorship of short texts through linguistic patterns and writing styles.

Developed as part of my **Master's Degree in Data Analysis and Decision Support Systems** at Coimbra Business School (ISCAC), Polytechnic Institute of Coimbra.

**Final Dissertation Grade: 18/20**

## Project Overview

The primary objective of this research was to develop and evaluate Machine Learning and Deep Learning approaches capable of identifying the author of a given text based on distinctive linguistic and stylistic characteristics.

Using a dataset of tweets from multiple authors, the project explores how NLP preprocessing, feature extraction, and supervised classification algorithms can be combined to predict text authorship.

The research follows the **Knowledge Discovery in Databases (KDD)** methodology, covering data preparation, exploratory analysis, model development, experimentation, and performance evaluation.

## Dataset

The project uses a Twitter-based authorship identification dataset containing text samples from multiple authors.

**Dataset File:** `authors.tsv`

The dataset contains author identifiers and their corresponding tweets, enabling the analysis of distinctive linguistic patterns and writing styles.

The original dataset was processed using Python and Pandas, including:

- Importing the TSV dataset using `pd.read_csv()` with tab separation.
- Renaming and restructuring columns into `Author_Name` and `Tweet`.
- Removing unnecessary columns and handling missing values.
- Cleaning URLs, hashtags, punctuation, special characters, and numeric values.
- Normalizing text through lowercasing and whitespace removal.
- Applying stopword removal depending on the experimental configuration.

The same dataset was used across all experiments to ensure consistent model comparisons.

## Technologies & Libraries

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** Scikit-learn, XGBoost
- **Deep Learning:** TensorFlow, Keras
- **Natural Language Processing:** NLTK
- **Text Representation:** TF-IDF, Count Vectorization, Word and Character-Level Features
- **Development Environment:** Jupyter Notebook, Google Colab

## Machine Learning Models

The following classification algorithms were evaluated:

- Naive Bayes (NB)
- Random Forest (RF)
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Logistic Regression (LR)
- Passive-Aggressive Classifier (PAC)
- Extreme Gradient Boosting (XGBoost)

### Deep Learning Models

- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)

## Methodology

**1. Data Collection & Exploration**

Analysis of a Twitter dataset containing textual samples from different authors, identifying patterns and characteristics relevant to authorship classification.

**2. Natural Language Processing**

Implementation and evaluation of text preprocessing techniques, including:

- Tokenization
- Text normalization and noise removal
- Stopword removal
- Word-level and character-level representations
- Text vectorization and feature extraction

**3. Model Development**

Training and comparison of traditional Machine Learning classifiers and Deep Learning architectures to identify authors based on their writing patterns.

**4. Experimental Evaluation**

Multiple experiments were conducted to investigate the impact of different modeling decisions:

- Baseline Machine Learning and Deep Learning performance
- Word-level versus character-level representations
- 15-fold cross-validation
- Impact of stopword removal
- Impact of excluding a specific author from the dataset
- Alternative 70/30 training and testing split

Models were evaluated using accuracy, precision, recall, and F1-score.

## Key Findings

The research demonstrated that traditional Machine Learning techniques can achieve competitive results in authorship identification tasks involving short, informal texts.

The **Passive-Aggressive Classifier (PAC)** emerged as the most effective approach in the experiments, demonstrating strong performance in distinguishing authors based on their writing styles.

The results also highlighted the importance of preprocessing strategies, feature representation, and model evaluation in developing reliable NLP classification systems.

## Repository Structure

```text
NLP-Authorship-Identification/
│
├── Notebook/
│   └── Machine_Learning_Author_Identification.ipynb
│
├── Dataset/
│   └── authors.tsv
│
└── README.md
```

## Academic Information

- **Institution:** Coimbra Business School (ISCAC) — Polytechnic Institute of Coimbra
- **Degree:** Master's in Data Analysis and Decision Support Systems
- **Year:** 2025
- **Dissertation Grade:** 18/20
- **Dissertation Title:** *Authorship Identification of Texts based on Natural Language Processing and Machine Learning*

---
