# Hidden-Markov-model-used-in-stocks
A brief study of Hidden Markov model applied in stocks

In this study, we apply a Hidden Markov Model (HMM) to analyze the price behavior of PETR4.SA (Petrobras ON) from 2020 to 2024 and LREN3.SA from 2011 to 2021. By using historical daily closing prices, we calculate the logarithmic returns and train an HMM with two hidden states.

The HMM (Hidden Markov Model) attempts to find hidden states that best explain the sequence of observed returns.

These states reflect changes in the statistical regime of the asset (for example, a change in the average return or volatility), but do not necessarily represent direct increases (uptrend) or decreases (dowtrend) in the price.

The data of LREN3 are evaluated at: https://figshare.com/articles/dataset/Macroeconomic_indices_used_in_predictive_model_for_retail_sector_in_Brazil/22674859

DOI: 10.6084/m9.figshare.22674865
