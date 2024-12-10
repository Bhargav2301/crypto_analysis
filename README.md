# Cryptocurrency Analysis Project

## Problem Statement

The cryptocurrency market is highly volatile and complex, presenting challenges for making informed decisions. This project provides a comprehensive analysis and clustering of cryptocurrency data to understand market trends, identify patterns, and make data-driven investment decisions.

## Project Overview

Involves the analysis of historical cryptocurrency data, focusing on price trends, volatility, and clustering. By leveraging statistical techniques and machine learning, insights into the behavior of different cryptocurrencies over time are provided.

## Objectives

- Analyze historical price data of various cryptocurrencies.
- Preprocess and clean the data for accurate analysis.
- Apply clustering techniques to identify patterns and group similar cryptocurrencies.
- Provide an interactive Shiny app for exploring the data and results.

## Data Analysis and Preprocessing

### Steps Involved

1. **Data Collection**: 
   - Gather historical price data for multiple cryptocurrencies from CSV files.

2. **Data Cleaning**:
   - Convert date columns to Date type.
   - Ensure numerical columns are correctly formatted.
   - Handle missing values by removing incomplete records.

3. **Feature Engineering**:
   - Calculate daily returns to measure price changes.
   - Compute moving averages and volatility to capture trends and fluctuations.

4. **Normalization**:
   - Normalize features to ensure comparability across different scales.

5. **Dimensionality Reduction**:
   - Apply Principal Component Analysis (PCA) to reduce feature dimensions while retaining variance.

6. **Clustering**:
   - Use K-Means clustering to group cryptocurrencies based on their behavior.
   - Determine the optimal number of clusters using the Elbow Method.

## Observations from Clustering

- **Cluster Characteristics**: 
  - Cryptocurrencies are grouped into clusters based on similar price movements and volatility.
  - Each cluster represents a distinct market behavior, helping identify stable and volatile coins.

- **Market Insights**:
  - Clustering reveals patterns that may not be apparent from individual analysis.
  - Insights can be used to diversify portfolios and manage risk.

## Interactive Shiny App

The Shiny app provides an interactive platform for exploring the data and clustering results. Users can:

- Select specific cryptocurrencies and time frames.
- Visualize price trends and cluster memberships.
- Analyze summary statistics for selected variables.

## Deployment

The application is deployed on shinyapps.io and can be accessed at [https://projectsdm2.shinyapps.io/crypto-analysis/](https://projectsdm2.shinyapps.io/crypto-analysis/).

## Conclusion

This project provides valuable insights into the cryptocurrency market, aiding in making informed decisions. By analyzing historical data and applying clustering techniques, patterns and trends that can guide investment strategies are uncovered.

For more information, refer to the project documentation and explore the Shiny app.

## Adding to GitHub

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Bhargav2301/crypto_analysis.git
   cd crypto_analysis
   ```

2. **Add Project Files**:
   - Copy project files into the cloned repository directory.

3. **Commit and Push Changes**:
   ```bash
   git add .
   git commit -m "Add cryptocurrency analysis project"
   git push origin main
   ```

4. **Verify on GitHub**:
   - Go to the GitHub repository at [https://github.com/Bhargav2301/crypto_analysis](https://github.com/Bhargav2301/crypto_analysis) to verify the changes.