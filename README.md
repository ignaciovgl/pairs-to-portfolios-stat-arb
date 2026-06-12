# 📉 From Pairs to Portfolios: A Guide to Cointegration & Statistical Arbitrage

[![Paper](https://img.shields.io/badge/Read_Paper-PDF-red.svg)](#)
[![Topic: Quant Finance](https://img.shields.io/badge/Topic-Quantitative_Finance-blue.svg)](#)
[![Platform: WorldQuant Brain](https://img.shields.io/badge/Platform-WorldQuant_Brain-purple.svg)](#)

Welcome to the research repository for **"From Pairs to Portfolios: A Guide to Cointegration and Statistical Arbitrage,"** co-authored by Ignacio Vigil Cardenal and Gonzalo García Suárez de Lezo (December 2025). 

This article was developed to bridge the gap between rigorous econometric theory and practical algorithmic trading. It moves beyond retail technical analysis to establish a fundamentally sound, academic approach to market-neutral trading.

## 📄 Abstract

In the current landscape of quantitative finance, the distinction between correlation and cointegration is frequently misunderstood, leading to fragile trading strategies that fail during periods of high market volatility. 

This paper deconstructs the mathematical foundations of mean-reverting portfolios. Starting with the intuitive "Drunk and the Dog" analogy to distinguish spurious correlation from true economic tethering, the research progresses through the algebra of stationarity, the mechanics of pairs trading, and the implementation of basket strategies using Vector Error Correction Models (VECMs). We conclude by translating the Ornstein-Uhlenbeck process into actionable Z-score signals for execution on platforms like WorldQuant Brain.

## 🧠 Key Concepts Explored

* **Correlation vs. Cointegration:** Mathematical proof of why "assets moving together" is insufficient for robust arbitrage.
* **Stationarity Testing:** Implementing Augmented Dickey-Fuller (ADF) and interpreting unit roots.
* **Cointegration Frameworks:** * Engle-Granger Two-Step Method for simple pairs.
  * Johansen Test for multivariate basket strategies.
* **Vector Error Correction Models (VECM):** Capturing short-term dynamics and long-term equilibrium in multi-asset portfolios.
* **Signal Generation:** Modeling the Ornstein-Uhlenbeck process to derive optimal Z-score entry and exit thresholds.

## 📂 Repository Structure

* `paper/`
  * [`From_Pairs_to_Portfolios__A_Guide_to_Cointegration_and_Statistical_Arbitrage.pdf`](From_Pairs_to_Portfolios_A_Guide_to_Cointegration_and_Statistical_Arbitrage%20.pdf) - *The full publication.*
* `src/` *(Optional: Add your implementation code here)*
  * `stationarity_tests.py` - *Scripts for ADF and Johansen tests.*
  * `vecm_modeling.py` - *Matrix operations and VECM implementation.*
  * `brain_alphas.txt` - *WorldQuant Brain expressions derived from the research.*

## 🚀 How to Read

You can read the full paper directly on GitHub by navigating to the `paper/` directory and opening the PDF, or by downloading it locally. 

## 👨‍💻 Authors

**Ignacio Vigil Cardenal** *BSc Mathematics and Statistics, University of Warwick* Passionate about statistical arbitrage, systematic investment strategies, and quantitative risk management.  
[LinkedIn Profile](https://www.linkedin.com/in/ignacio-vigil-cardenal) | [GitHub Profile](https://github.com/yourusername)

**Gonzalo García Suárez de Lezo** *Co-Author*
