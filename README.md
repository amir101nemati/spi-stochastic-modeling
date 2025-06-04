# Standardized Precipitation Index Analysis Using Stochastic Modeling

This project analyzes precipitation data in Tehran (2009–2019) using the Standardized Precipitation Index (SPI). The SPI is computed monthly and yearly based on the methodology proposed by Lloyd-Hughes and Saunders. The analysis incorporates statistical modeling and probability distributions to understand rainfall anomalies and drought conditions.

## Key Features
- SPI calculation using gamma distribution fitting
- Time series processing of rainfall data
- Visualization of monthly and annual SPI values
- Application of stochastic methods to climatology

## Stochastic Modeling Components
### 1. Markov Chains
- Transition matrices were estimated to model the probability of switching between wet, normal, and dry months.
- States are defined based on SPI thresholds, forming a discrete Markov Chain.

### 2. Continuous-Time Markov Processes
- Rainfall states are also analyzed over continuous time intervals to assess the duration and transition intensity between conditions.
  
### 3. Hidden Markov Models (HMM)
- Hidden Markov Models are used to identify underlying weather regimes not directly observed from SPI values.
- The forward-backward algorithm and state decoding were applied for analysis.
**Course**: Stochastic Processes  
**Semester**: Fall 2024
