# AI & Machine Learning Pipeline – Spotify Dataset (114K+ Tracks)

This project implements a full Machine Learning pipeline using a large-scale real-world Spotify dataset with over 114,000 tracks. The objective is to demonstrate rigorous data exploration, preprocessing, model comparison, and evaluation using empirical results rather than theoretical discussion.

The project follows formal academic ML requirements and emphasizes experimental justification at every stage.

## Dataset
- **Source:** Spotify Tracks Dataset (Kaggle)
- **Size:** 114,000+ audio tracks
- **Features:** numerical audio features such as energy, valence, tempo, loudness, danceability, etc.
- **Challenges:** scale imbalance, skewed distributions, outliers, and real-world noise
- **License:** As provided on Kaggle  
  (dataset is referenced, not redistributed)

The dataset is well-suited for machine learning due to its size, feature diversity, and non-ideal real-world structure.

## Problem Definition
- **Task Type:** Machine Learning (classification / clustering / regression)
- **Objective:** Analyze and model relationships between Spotify audio features and evaluate how preprocessing and model complexity affect performance
- **Evaluation Focus:** predictive performance, robustness, and trade-offs between baseline and advanced models

## Methodology
### 1. Exploratory Data Analysis (EDA)
- Dataset shape and feature inspection
- Summary statistics
- Missing value analysis
- Distribution analysis (histograms, boxplots)
- Outlier detection
- Feature relationship visualization

### 2. Data Preprocessing
- Handling missing values
- Feature encoding (where applicable)
- Feature scaling (with and without scaling)
- Multiple preprocessing strategies tested and compared
- Explicit justification for all preprocessing decisions

### 3. Baseline Model
- Simple reference model used as a baseline
- Training and evaluation using appropriate metrics
- Interpretation of baseline performance

### 4. Advanced Model
- More complex model with hyperparameter tuning
- Performance comparison against the baseline model
- Analysis of increased model complexity

### 5. Evaluation & Results Comparison
- Quantitative performance metrics
- Tables and plots comparing models
- Experimental demonstration of preprocessing and scaling impact
- Discussion of performance gains and limitations

## Results & Discussion
- Clear comparison between baseline and advanced models
- Empirical evidence supporting model and preprocessing choices
- Identification of limitations and potential improvements

## Deliverables
- Fully executed Jupyter Notebook with visible outputs
- Reproducible experimental pipeline
- Clear structure aligned with machine learning best practices

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
