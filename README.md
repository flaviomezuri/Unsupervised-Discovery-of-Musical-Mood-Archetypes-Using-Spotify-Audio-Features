# Unsupervised-Discovery-of-Musical-Mood-Archetypes-Using-Spotify-Audio-Features

# AI & Machine Learning Pipeline – Spotify Dataset

This project implements a complete Machine Learning pipeline on a real-world Spotify dataset from Kaggle, following academic requirements for data-driven experimentation and model comparison.

The goal is to demonstrate end-to-end understanding of data exploration, preprocessing, model selection, training, evaluation, and interpretation using actual experimental results.

## Dataset
- **Source:** Spotify Tracks Dataset (Kaggle)
- **Samples:** 1,000+ tracks
- **Characteristics:** noisy features, outliers, skewed distributions, and feature scale imbalance
- **License:** As provided on Kaggle (dataset linked, not redistributed)

The dataset is suitable for machine learning due to its numerical audio features (e.g. energy, valence, tempo, loudness) and real-world variability.

## Problem Definition
- **Task:** Machine Learning (classification / clustering / regression)
- **Objective:** Learn patterns in audio features and evaluate model performance under different preprocessing and modeling choices
- **Evaluation focus:** model performance, robustness, and trade-offs between simplicity and complexity

## Methodology
### 1. Exploratory Data Analysis (EDA)
- Dataset shape and feature inspection
- Summary statistics
- Missing value analysis
- Distribution plots (histograms, boxplots)
- Outlier detection
- Feature relationship visualization

### 2. Data Preprocessing
- Missing value handling
- Feature encoding (where applicable)
- Feature scaling (with and without scaling)
- Multiple preprocessing strategies tested and compared
- Justification for all preprocessing decisions

### 3. Baseline Model
- Simple model used as a performance reference
- Training and evaluation using standard metrics
- Interpretation of baseline results

### 4. Advanced Model
- More complex model with hyperparameter tuning
- Performance comparison against baseline
- Discussion of model complexity vs. performance gains

### 5. Evaluation & Comparison
- Quantitative metrics
- Tables and plots for comparison
- Analysis of improvements and limitations

## Results
- Clear performance comparison between baseline and advanced models
- Experimental evidence of preprocessing and scaling impact
- Discussion of strengths, weaknesses, and limitations

## Deliverables
- Executed Jupyter Notebook with visible outputs
- Reproducible code
- Clear experimental structure aligned with ML best practices

## Tools & Technologies
- Python
- NumPy
- Pandas
- scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## Author
Flavio Mëzuri

## License
MIT License
