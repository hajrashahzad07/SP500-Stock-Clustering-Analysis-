# S&P 500 Stock Clustering Analysis

## Project Overview
Market analysis and segmentation of S&P 500 stocks using agglomerative and k-means clustering based on Beta, Annual Volatility, and Daily Return metrics for portfolio diversification.

## Analysis Period
January 1, 2022 - January 1, 2025

## Notebook Contents
The `SP500_Stock_Clustering_Analysis.ipynb` notebook contains all five tasks:

### Task 1: Data Loading
- Extracted S&P 500 tickers from Wikipedia
- Loaded daily market performance data using yfinance (2022-2025)
- Cleaned and removed invalid data

### Task 2: Metrics Calculation
- Daily Return calculation
- Beta calculation (stock vs market correlation)
- Annual Volatility calculation

### Task 3: Agglomerative Clustering
- Clustered stocks based on Beta metrics
- Identified optimal number of clusters
- Analyzed cluster profiles

### Task 4: K-Means Clustering
- Clustered stocks based on Beta and Annual Volatility
- Determined optimal K value
- Compared with agglomerative results

### Task 5: Results Analysis
- Visualized business value of clusters
- Developed portfolio diversification strategies
- Created investment recommendations for different investor types

## Key Findings
- **3 distinct risk clusters identified**:
  - Cluster 0 (Balanced): 49.5% - Beta 1.01, Moderate Risk
  - Cluster 1 (Aggressive): 14.5% - Beta 1.65, High Risk/High Return
  - Cluster 2 (Defensive): 36.0% - Beta 0.53, Low Risk

- **Portfolio strategies developed**:
  - Conservative: 11.45% expected return, 0.354 volatility
  - Balanced: 12.21% expected return, 0.379 volatility
  - Aggressive: 10.82% expected return, 0.323 volatility

## Technologies Used
- Python 3.8+
- pandas, numpy
- yfinance, YahooFinancials
- scikit-learn (AgglomerativeClustering, KMeans)
- matplotlib, seaborn

## Author
[Hajra Shahzad ]
[University of Westminster]
[Course Code: 6BUIS017W]

┌─────────────────────────────────────────────────────────────┐
│                     CODE REPOSITORY                          │
├─────────────────────────────────────────────────────────────┤
│  The complete Python code and analysis is available at:     │
│                                                              │
│  https://github.com/yourusername/repository-name            │
│                                                              │
│  File: SP500_Stock_Clustering_Analysis.ipynb                │
└─────────────────────────────────────────────────────────────┘
