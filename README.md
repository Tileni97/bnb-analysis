# Binance Coin (BNB) Market Analysis  
**Objective**: Identify trading signals and user behavior patterns using Binance's data infrastructure, demonstrating skills directly applicable to Binance's Data Analyst role.  

## 🔍 Methodology  
1. **Data Collection**:  
   - Used Binance API (`python-binance`) to fetch OHLCV data (Jan 2024–Apr 2025).  
   - Automated data validation and cleaning (handling missing values, type conversion).  

2. **Analysis**:  
   - **Technical Indicators**: VWAP, SMA/EMA, Bollinger Bands, RSI, OBV.  
   - **Volatility Modeling**: Rolling 30-day volatility and anomaly detection.  

3. **Visualization**:  
   - **Power BI Dashboard**: Interactive filters for time periods and metrics.  
   - **Python**: Matplotlib/Seaborn for correlation heatmaps and trend decomposition.  

## 📊 Key Findings & Business Impact  
### **1. Price-Volume Divergence (Feb–Mar 2024)**  
- *Finding*: Volume spikes preceded price rallies by 24–48 hours.  
- *Binance Impact*: Could inform **liquidity provisioning** or **trading incentive programs** during low-volume periods.  

### **2. Low Liquidity Periods (2025)**  
- *Finding*: Declining price with stagnant volume suggests reduced trader interest.  
- *Binance Impact*: Flag for **marketing campaigns** (e.g., BNB staking promotions) to reactivate users.  

### **3. Volatility Clustering**  
- *Finding*: High volatility correlated with macroeconomic events (e.g., Fed rate hikes).  
- *Binance Impact*: Basis for **risk management models** (e.g., adjusting margin requirements).  

## 🛠️ Tools Used  
- **Python**: `pandas`, `matplotlib`, `python-binance`, `ta` (technical analysis library).  
- **Power BI**: Dynamic dashboards with slicers for real-time scenario testing.  
- **Binance API**: Direct integration with Binance’s data infrastructure.  

![Dashboard](data/processed/dashboard_preview.png)  

## 🔮 Next Steps  
- Integrate **order book data** to analyze market depth.  
- Build a **real-time alert system** for anomalous volume/volatility.  



