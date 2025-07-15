# 🤖 AI-Driven Portfolio Optimization Using Reinforcement Learning

A data-driven financial portfolio optimizer powered by Reinforcement Learning (RL) agents like PPO, DDPG, and A2C. This project uses historical financial metrics and engineered indicators to simulate a trading environment, train intelligent agents, and provide actionable investment advice with ratings and suggestions for portfolio improvement.

---

## 📌 Features

- 📊 **Financial Data Preprocessing** using revenue, volatility, Sharpe ratio & momentum
- 🧠 **Custom Gym Environment** simulating multi-asset investment decisions
- ⚙️ **RL Algorithms**: PPO, DDPG, and A2C from Stable-Baselines3
- 📈 **Performance Evaluation** across multiple episodes and agents
- 🎯 **Personalized Portfolio Advisor**: Compares user allocations to RL-suggested allocations with similarity scoring
- 📉 **Visualizations**: Plotting performance and reward curves

---

## 🚀 Technologies Used

| Category        | Tools & Libraries                             |
|-----------------|------------------------------------------------|
| RL Algorithms   | PPO, DDPG, A2C (`stable-baselines3`)           |
| Environment     | `OpenAI Gym`, Custom PortfolioEnv              |
| Data Processing | `pandas`, `numpy`, `sklearn`, `matplotlib`     |
| Optimization    | Momentum, Moving Averages, Sharpe Ratio        |
| Deployment      | Google Colab (Notebook format)                 |

---

## 🔧 Installation

1. **Clone the repository**
    ```bash
       git clone https://github.com/ommishra03/AI-Driven-Portfolio-Optimization-Using-Reinforcement-Learning.git
       cd AI-Driven-Portfolio-Optimization-Using-Reinforcement-Learning
    ```
   
    Install dependencies
    
        pip install stable-baselines3
        pip install "shimmy>=2.0"

Prepare the dataset
        
    Add your Portfolio_management.csv file in the root directory.
    
    The dataset must include financial columns like Revenue, Net Income, etc.
    
    Run the notebook
    
    Open AI-Driven Portfolio Optimization Using Reinforcement Learning.ipynb in Google Colab or Jupyter.

📥 Input

    CSV file with historical financial data for multiple stocks (Portfolio_management.csv)
    
    Required columns include: Revenue, Ticker, Report Date, etc.
    
    User-provided current portfolio allocations (as percentages)

📤 Output

    🤖 Trained RL models (PPO, DDPG, A2C)
    
    📉 Performance curves of each RL agent
    
    🎯 Portfolio advice with similarity rating (out of 10)
    
    📌 Suggestions on which stock allocations to increase or reduce

📚 About the Author

    👨‍🎓 Om Mishra
    📍 Third-year Student, Chandigarh University
    🏆 Reliance Foundation Scholar
    🧠 Mentor at Reliance Foundation (C, C++, DSA, Python)
    🌐 Blockchain & AI Enthusiast (Solidity, Ethereum, React, ML)
    🎮 Hackathon Finalist (NASA Space App Challenge, NITs, BITS)
    📢 Rebuilt math curriculum at an ed-tech startup
    🧑‍🏫 Taught merchant navy aspirants

🔗 [Connect on LinkedIn](https://www.linkedin.com/in/om-mishra-a62991289)

✨ Acknowledgements

    🧠 Stable Baselines3
    
    📊 scikit-learn for scaling
    
    📚 OpenAI Gym for RL environment structure
    
    🧪 Google Colab for notebook execution

📜 License
This project is open-source and available under the MIT License.

📧 Contact
For feedback or collaboration: ommishra1729@gmail.com

---

Let me know if you'd like this in a downloadable `.md` format or want help generating a `requirements.txt` based on this code.


