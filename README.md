# Exoplanet Detection

This project aims to detect exoplanets using machine learning models trained on publicly available data from various telescopes. Exoplanet detection involves analyzing the brightness time series data of stars and identifying the characteristic dip caused by an exoplanet passing in front of its host star.

## Dataset

We utilize publicly available datasets. These datasets consist of time series data of stellar brightness measurements collected by telescopes such as Kepler Space Telescope. Each data point in the time series represents the brightness of a star at a particular timestamp.

## Methodology

### 1. Data Preprocessing

Before training the machine learning models, we preprocess the data by:

- Removing outliers and noise.
- Normalizing the brightness values to a standard scale.

### 2. Feature Engineering

We extract relevant features from the time series data, including:

- Periodicity of brightness fluctuations.
- Duration and depth of transits caused by exoplanets.
- Other relevant features based on domain knowledge.

### 3. Model Training

We experiment with multiple machine learning models, including but not limited to:

- Support Vector Machines (SVM)
- Random Forest
- XGBoost
- KNN
- Decision Tree

These models are trained on the preprocessed data to learn patterns indicative of exoplanet transits.

### 4. Model Evaluation

We evaluate the performance of each model using metrics such as:

- Accuracy
- Precision
- Recall
- F1-score

The model with the highest performance metrics is selected as the primary exoplanet detection model.

## Usage

To use the trained model for exoplanet detection:

1. **Data Preparation**: Prepare time series data of star brightness measurements.
2. **Preprocessing**: Preprocess the data by removing outliers and normalizing brightness values.
3. **Feature Extraction**: Extract relevant features from the preprocessed data.
4. **Model Inference**: Use the trained model to predict the presence of exoplanets based on the extracted features.

## Results

Our experiments show promising results in exoplanet detection using machine learning models. The selected model achieves [insert performance metrics], demonstrating its efficacy in identifying exoplanets from stellar brightness time series data.

## Future Work

In the future, we plan to:

- Explore more advanced machine learning models for improved detection accuracy.
- Incorporate additional features or data sources to enhance model performance.
- Conduct further analysis on false positives and false negatives to refine the detection process.
