## 📊 Dataset
The dataset used in this project is the **S&P500 stock market data**, containing:
- `Timestamp`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`.

### 🔍 Data Preprocessing:
- Tested for **stationarity** using statistical methods.
- Applied **data transformations** to achieve stationarity.
- Conducted **visual analysis** of the price movements.
## 📈 Implemented Models
This project implements various financial models to analyze and simulate stock price movements:

1️⃣ **Random Walk Model**  
   - Simulates stock prices assuming **independent random steps**.  
   - Evaluates the predictability of stock prices.

2️⃣ **Geometric Brownian Motion (GBM)**  
   - Models stock prices with **drift & volatility** components.  
   - Commonly used in **Black-Scholes option pricing**.

3️⃣ **Gaussian Process Regression (GPR)**  
   - Non-parametric model to predict stock prices with **confidence intervals**.  
   - Uses custom **kernel functions** for feature extraction.

4️⃣ **Hidden Markov Model (HMM) with GMM Emissions**  
   - Detects **market regimes** (e.g., bull/bear markets).  
   - Assigns probabilities to hidden market states.

5️⃣ **HMM-Based Trading Strategy**  
   - Uses HMM states to generate **buy/sell signals**.  
   - Backtests performance against historical data.
