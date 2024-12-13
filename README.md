# IAU Data Science Project: Malware Detection Using Machine Learning

## Project Overview

The aim of this project is to develop a machine learning model for detecting malware-related activities (MWRA) in mobile device logs. This task involves understanding core data science concepts and applying machine learning techniques to address data-related challenges, create data pipelines, and evaluate predictive models.

The project is structured into three phases:
1. **Exploratory Data Analysis (EDA)** [Exploratory Analysis](https://github.com/DariiaSira/PredictingMWRAwithML--STU-FIIT/blob/main/ExploratoryAnalysis_DataPreprocessing.ipynb)
2. **Data Preprocessing** [Data Preprocessing](https://github.com/DariiaSira/PredictingMWRAwithML--STU-FIIT/blob/main/ExploratoryAnalysis_DataPreprocessing.ipynb)
3. **Machine Learning Model Development and Evaluation** [Machine Learning](https://github.com/DariiaSira/PredictingMWRAwithML--STU-FIIT/blob/main/MachineLearning.ipynb)

Each phase contributes incrementally to creating an effective and reproducible pipeline for malware detection.

---

## Dataset Description

The dataset contains logs of Android mobile devices collected using the [Rapid7 agent](https://www.rapid7.com/). It is preprocessed to some extent for educational purposes. The target variable is `mwra`, which indicates malware-related activity within a given time interval.

### Dataset Characteristics:
- **Source:** Mobile device logs.
- **Target Variable:** `mwra` (Binary classification: presence or absence of malware activity).
- **Attributes:** Various features related to device behavior and application activities.
- **Potential Issues:**
  - Missing values.
  - Skewed distributions.
  - Inconsistent formats.

For more details about the dataset, refer to the [dataset]().

---

## Project Phases

### Phase 1: Exploratory Data Analysis (EDA)
- **Goal:** Understand the data structure and identify potential challenges.
- **Tasks:**
  1. Basic dataset description, including distributions and attribute analysis.
  2. Pairwise analysis of relationships between variables.
  3. Problem identification (e.g., missing values, outliers) and initial resolutions.
  4. Formulate hypotheses about the data and test them statistically.

### Phase 2: Data Preprocessing
- **Goal:** Prepare the data for machine learning applications.
- **Tasks:**
  1. Handle missing values using techniques like mean replacement or interpolation.
  2. Encode non-numeric data for compatibility with machine learning algorithms.
  3. Apply scaling (e.g., Min-Max, StandardScaler) and transformations.
  4. Ensure reproducibility of preprocessing steps.

### Phase 3: Machine Learning
- **Goal:** Train and evaluate models for predicting malware-related activities.
- **Tasks:**
  1. Implement a simple classifier using ID3 with minimum depth 2.
  2. Train additional models using algorithms from `scikit-learn` (tree-based and non-tree-based).
  3. Optimize models using hyperparameter tuning and cross-validation.
  4. Evaluate models based on metrics like accuracy, precision, and recall.
  5. Select and document the best model for deployment.

---

## Deliverables
- **Jupyter Notebooks:** For each phase, containing code, results (e.g., visualizations, statistical analysis), and documentation.
- **Data Pipeline:** A reproducible pipeline for preprocessing and model training.
- **Model Evaluations:** Metrics and justifications for model performance.
- **GitHub Repository:** Complete codebase, organized and documented.

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/username/iau-malware-detection.git
