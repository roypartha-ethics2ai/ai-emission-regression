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

## 📊 Visualizations

### Figure 1: AI Model Emissions vs Compute
![Emissions vs Compute](figures/emissions_vs_compute.png)

> Emissions scale predictably with training compute. A log-log scatter of 56 models shows a near-linear trend, validating calls for compute-aware carbon regulation.

### Figure 2: Forecasted AI Emissions (2026–2031)
![Forecasted Emissions](figures/forecasted_emissions_2026_2031.png)

> Projected emissions will triple by 2031 under a 40% annual compute growth rate. Supports ESG thresholds, carbon offsetting, and transparency requirements.

## ✍️ Author

**Partha Roy**  
AI Ethics Researcher | Civic Technologist | Editorial Strategist  
Kolkata, India  
ORCID: https://orcid.org/0009-0002-1893-3637 Email: r.partha7@gmail.com
