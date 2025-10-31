# ai-emission-regression
Regression analysis and emissions forecast using OpenCarbonEval data. Models how AI emissions scale with compute and projects growth under a 40% annual rate. Supports ESG thresholds, carbon-aware regulation, and ethical audits in AI governance.

# Carbon-Conscious AI: Emissions Forecasting from Compute Scaling

This repository presents a reproducible regression analysis and emissions forecast using the OpenCarbonEval dataset (Tsinghua University, 2024). It models how carbon emissions from large AI models scale with training compute and projects future emissions under a 40% annual compute growth assumption.

## 📊 Contents

- `emissions_analysis.py`: Python script for regression modeling and emissions forecasting  
- `figures/`: Visualizations of actual vs. projected emissions  
- `data/`: Source dataset (linked below)  
- `LICENSE`: MIT license for open use  

## 📈 Methodology

- **Data Source**: [OpenCarbonEval GitHub – model_emission.csv](https://github.com/answers111/OpenCarbonEval/blob/main/data/model_emission.csv)  
- **Libraries Used**: `pandas`, `numpy`, `statsmodels`, `matplotlib`  
- **Model**: Log-log linear regression using training compute (FLOP), kgCO₂/kWh, and TDP as predictors  
- **Forecast**: Emissions projected from 2026 to 2031 assuming 40% annual compute growth  

## 📌 Key Findings

- Emissions scale nearly linearly with compute on a log-log scale  
- At current growth rates, AI emissions could triple by 2031  
- Supports ESG thresholds, compute-aware regulation, and ethical audits  

## 🧭 Use Cases

- Academic research on AI sustainability  
- Policy proposals for carbon-conscious AI governance  
- Editorial commentary on emissions transparency and compute taxation  

## 📜 License

This project is licensed under the MIT License. See `LICENSE` for details.

## ✍️ Author

**Partha Roy**  
AI Ethics Researcher | Civic Technologist | Editorial Strategist  
Kolkata, India  

