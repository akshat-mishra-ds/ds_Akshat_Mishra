# 📊 Data Science Assignment – Trader Behavior vs Market Sentiment  

## 👤 Candidate  
Akshat Mishra  

---

## 📂 Repository Structure  
ds_<your_name>/
├── notebook_1.ipynb               # Main Google Colab notebook (EDA, analysis, results)
├── csv_files/                     # Intermediate data outputs
│ ├── daily_aggregates.csv
│ └── per_account_summary.csv
├── outputs/                        # Visual outputs (charts & plots)
│ ├── distribution_pnl.png
│ ├── pnl_by_sentiment_boxplot.png
│ └── daily_profitable_ratio.png
├── ds_report.pdf                   # Final summarized report
└── README.md                       # Project overview & setup instructions

---

## 🔗 Google Colab Links  

- [Notebook 1 (EDA + Analysis)]([https://colab.research.google.com/drive/<YOUR_NOTEBOOK1_LINK>](https://colab.research.google.com/drive/1wLDFrMNVpG-o0cyJfkU4nj9Q4aqaTkt7?usp=sharing))

---

## 📖 Project Overview  

This project explores the relationship between **trader behavior** and **market sentiment (Fear vs Greed)** using two datasets:  
1. **Bitcoin Market Sentiment Dataset** – sentiment values & classifications (2018–2025).  
2. **Historical Trader Data (Hyperliquid)** – ~211k trades across 7 trading days (2023–2025).  

---

## 📊 Key Objectives  
- Analyze how **trading profitability, volume, and risk** vary under different market sentiments.  
- Compare **Greed vs Fear** conditions using statistical testing (Mann–Whitney U).  
- Identify **top/bottom performing accounts** and their behavior across sentiment regimes.  
- Provide **actionable recommendations** for risk management strategies.  

---

## 🛠️ Tools Used  
- **Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)**  
- **Google Colab** (for notebooks)  
- **GitHub** (for submission & version control)  
- **ReportLab** (for PDF generation)  

---

## 📌 Deliverables  
- **notebook_1.ipynb** → Full EDA, data processing, analysis, plots.  
- **csv_files/** → Aggregated results (`daily_aggregates.csv`, `per_account_summary.csv`).  
- **outputs/** → Saved visualizations.  
- **ds_report.pdf** → Summarized business insights, findings, and recommendations.  

---

## 🚀 Insights & Recommendations (Summary)  
- **Fear days** → Lower win rates, higher trade volume → reduce exposure.  
- **Greed/Extreme Greed days** → Higher profitability but also higher volatility → monitor leverage & exposure closely.  
- **Accounts** → A small subset of traders consistently profitable; many accounts persistently negative.  
- **Next steps** → Add leverage/margin data, expand continuous trade coverage, build predictive models.  

---

## 📌 Notes  
- This repo follows the **standardized submission format** required by Web3 Trading Team.  
- All code is reproducible via the linked Google Colab notebooks.  
- Folders (`csv_files/`, `outputs/`) are included with generated files.
