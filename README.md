# IPL Data Analysis and 2025 Winner Prediction

## 📋 Overview

This project presents a comprehensive analysis of the Indian Premier League (IPL) cricket data from its inception in 2008 through the 2024 season. Using statistical methods and machine learning techniques, we explore team and player performances, conduct seasonal analyses, and develop a predictive model to forecast the winner of the 2025 IPL season.

## 🎯 Problem Statement

Cricket is the most popular sport in India, with the IPL being its most celebrated professional Twenty20 cricket league. This project aims to:

1. Perform comprehensive exploratory data analysis on historical IPL data (2008-2024)
2. Uncover key insights, trends, and patterns in team and player performances
3. Develop an ensemble machine learning model to predict the 2025 IPL winner
4. Demonstrate the application of advanced data science techniques to sports analytics

## 📊 Dataset

The analysis uses the BrainDead IPL Complete Dataset (2008-2024), which consists of two CSV files:

- **matches.csv**: Contains match summaries of 1,095 face-offs (17 seasons)
- **deliveries.csv**: Contains ball-by-ball details with 1,426,312 delivery entries

## 🔍 Analysis Approach

### 1️⃣ Data Cleaning and Feature Engineering
- Missing value treatment
- Outlier detection and handling
- Feature creation and transformation

### 2️⃣ Exploratory Data Analysis (EDA)

#### 🏏 Team Performance Analysis
- Matches played and winning percentages
- Run rate and economy rate analysis
- Highest and lowest scores
- Boundary statistics (4s and 6s)
- Powerplay and death overs performance

#### 👤 Player Performance Analysis
- Top run-scorers and their metrics
- Batting average vs. strike rate analysis
- Performance metrics for consistent players (>50 matches)
- Top wicket-takers
- Highest individual scores
- Man of the Match awards distribution
- K-Means clustering of players (Batsman, Bowler, All-Rounder)
- Specialized batting analysis (top scorers by run type)

#### 📅 Seasonal Analysis
- Run trends across seasons
- High-scoring matches per season
- Team scoring evolution
- Orange Cap and Purple Cap holder performance
- Top bowlers per season

### 3️⃣ Feature Extraction
- Key feature identification from match data
- Crucial insights extraction from ball-by-ball data

### 4️⃣ Prediction Model
- Ensemble model combining multiple classifiers
- Neural network experimentation
- Feature importance analysis
- Cross-validation and performance evaluation

## 📈 Key Findings

*(Note: Replace these placeholder points with your actual findings after analysis)*

1. Team A has the highest win percentage (65.3%) across all IPL seasons
2. Player X holds the record for most runs with an impressive average of 42.5
3. Season Y saw the highest number of 200+ scores (15)
4. The batting strike rate has increased by approximately 15% since the first season
5. Home advantage plays a significant role, with 60% of matches won by home teams

## 🏆 2025 IPL Winner Prediction

*(Replace with your actual prediction and confidence level)*

Based on our ensemble model, **Team Z** is predicted to win the 2025 IPL season with a probability of 32.7%.

## 🛠️ Tools and Technologies

- **Programming Language**: Python
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn, XGBoost
- **Deep Learning**: TensorFlow/Keras (for neural network experimentation)
- **Development Environment**: Jupyter Notebook/Google Colab
## 📊 Sample Visualizations

## ⚙️ Setup and Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ipl-data-analysis.git
   cd ipl-data-analysis
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```

## 📝 Usage

1. Start with the data cleaning notebook to prepare your dataset
2. Proceed through the analysis notebooks in sequence
3. Examine the prediction model notebook for the 2025 IPL winner forecast
4. Refer to the presentation for a comprehensive summary of findings

## 🔮 Future Work

- Incorporate player auction data for more comprehensive team strength analysis
- Develop a match-by-match prediction system
- Include weather and pitch condition data for more accurate predictions
- Create an interactive dashboard for real-time IPL analysis

## 📚 References

1. IPL Official Website - [https://www.iplt20.com/](https://www.iplt20.com/)
2. BrainDead IPL Complete Dataset (2008-2024)

*Note: This project is created for educational purposes only. All data used is publicly available.*
