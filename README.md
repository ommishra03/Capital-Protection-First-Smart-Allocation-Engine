# AI-Driven Portfolio Optimization Using Reinforcement Learning

## Overview
This project implements a Reinforcement Learning (RL) approach for optimizing stock portfolios using algorithms such as **PPO (Proximal Policy Optimization)**, **DDPG (Deep Deterministic Policy Gradient)**, and **A2C (Advantage Actor-Critic)**. The goal is to design a portfolio management system that dynamically allocates assets to maximize returns based on historical financial data.

---

## Features
- **Data Preprocessing:**
  - Cleans and prepares financial data for each stock ticker.
  - Applies moving averages, volatility calculations, Sharpe ratio computation, and momentum measurement.
  - Scales the processed data for better learning efficiency.

- **Environment Design (PortfolioEnv):**
  - Uses Gym's `Env` class to build a custom environment for portfolio optimization.
  - Takes a list of tickers and historical financial data as input.
  - Defines observation and action spaces for Reinforcement Learning agents.

- **Model Training:**
  - Implements PPO, DDPG, and A2C algorithms using Stable-Baselines3.
  - Trains the agents with `env.learn()` method for 50,000 timesteps.

- **Evaluation:**
  - Evaluates the models over multiple episodes and compares their performance.
  - Provides graphical visualization of performance metrics.

- **User Interaction:**
  - Allows users to input their portfolio allocation.
  - Provides suggestions for improvement based on model predictions.
  - Rates user allocation from 1 to 10 based on similarity with model suggestions.

---

## Installation
1. Clone the repository:
```bash
[git clone <repository-url>](https://github.com/ommishra03/AI-Driven-Portfolio-Optimization-Using-Reinforcement-Learning)
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Ensure required packages are installed:
```bash
pip install shimmy>=2.0
pip install stable-baselines3
```

---

## Usage
1. Prepare the CSV file with the following columns:
   - `Ticker`, `Report Date`, `Publish Date`, `Restated Date`, `Revenue`, `Shares (Basic)`, `Shares (Diluted)`, etc.
2. Update the `file_path` variable with the path to your dataset.
3. Run the Python script to train models and evaluate performance.
4. Enter your portfolio allocation when prompted to receive suggestions.

---

## Example Output
- **Average Reward Comparison:**
```
PPO Average Reward: <value>
DDPG Average Reward: <value>
A2C Average Reward: <value>
```
- **User's Current Allocation:**
```
AAPL: 30.00%
GOOG: 20.00%
MSFT: 50.00%
```
- **Model's Suggested Allocation:**
```
AAPL: 25.00%
GOOG: 35.00%
MSFT: 40.00%
```
- **Your Portfolio Rating:** `8.5/10`

---

## Future Improvements
- Implementing additional algorithms like SAC (Soft Actor-Critic) and TRPO (Trust Region Policy Optimization).
- Adding more financial metrics and features.
- Incorporating live data for real-time portfolio optimization.

---

## Contact Information
- **LinkedIn:** [Om Mishra](https://www.linkedin.com/in/om-mishra-a62991289)
- **Email:** [Mail](ommishar1729@gmail.com) 
- **Phone Number:** [Contact](9140476686)

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

