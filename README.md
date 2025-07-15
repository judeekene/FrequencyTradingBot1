# FrequencyTradingBot1
An intelligent algorithmic trading bot built using cAlgo and C#, designed to detect market momentum shifts across multiple timeframes using Cubic Velocity analysis of EMA and MACD indicators.

### 🔍 Strategy Overview
This bot combines price action analysis with velocity-based indicator calculations to identify trend reversals. The strategy:

- Uses **Exponential Moving Average (EMA)** and **MACD Histogram** on configurable timeframes.
- Calculates the **Cubic Velocity** of these indicators to anticipate market momentum.
- Executes buy/sell logic levels.
- Supports dynamic volume allocation or fixed sizing.

### 🧩 Technology Stack
- **cAlgo (cTrader)**  
- **C#**  
- **Custom mathematical modeling** for cubic velocity  
- **Risk management tools** using position control  

### 🛡️ License
Distributed under the MIT License.  
> See `LICENSE` file for more details.

