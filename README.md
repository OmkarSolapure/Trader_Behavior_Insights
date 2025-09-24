📊 Trader Behavior Insights

A Python-based data analysis project that studies trader behavior by combining historical trade data with the Fear & Greed Index.

🔧 Features

Cleans and merges historical trading data with market sentiment data

Computes key statistics: mean, std, min, max of closed PnL

Analyzes Fear & Greed classifications

Generates visualizations:

PnL Over Time

Fear & Greed Score Over Time

PnL Distribution

Fear & Greed Class Distribution

Exports results:

outputs/summary.csv (key stats & sentiment counts)

outputs/merged_data.csv (merged dataset)

figures/ (plots as PNGs)

report/analysis_report.pdf (full PDF report with stats & charts)

📂 Project Structure
Trader_Behavior_Insights/
├── Trader_Behavior_Insights.py   # Main analysis script
├── historical_data.csv           # Trade history dataset
├── fear_greed_index.csv          # Fear & Greed Index dataset
├── outputs/                      # CSV outputs
├── figures/                      # Generated figures
├── report/                       # PDF reports
└── requirements.txt              # Dependencies

🚀 Getting Started

Clone the repo:

git clone https://github.com/yourusername/Trader_Behavior_Insights.git
cd Trader_Behavior_Insights


Install dependencies:

pip install -r requirements.txt


Run analysis:

python Trader_Behavior_Insights.py


Check results in outputs/, figures/, and report/.
