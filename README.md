# balatro-run-python
# 🎴 Balatro Data & Strategy Project  

## 📌 Overview  
This project analyses **Balatro**, the roguelike deck-building poker game, by combining **Python**, **data analysis**, and **visualisation**.  
The project demonstrates the full workflow of:  
- Collecting and cleaning gameplay data,  
- Running simulations with Python,  
- Producing charts and heatmaps,  
- Writing structured reports with documented insights.  

The goal is to show how analytics can be applied to gaming strategy and highlight transferable skills for **data science and analytics roles**.  

---

## 🗂 Project Structure  

### 🔹 Code  
- `Balatro_Run_Simulator.ipynb` – Jupyter Notebook with full analysis pipeline and simulation logic.  
- `requirements.txt` – Python dependencies for reproducibility.  

### 🔹 Data  
- `balatro_run_history.csv` – Dataset of recorded Balatro runs (deck, jokers, multipliers, chips, outcomes).  

### 🔹 Documentation  
- `Balatro_Report.docx` – Full project write-up with insights.  
- `Balatro_Abstract.docx` – Concise summary of aims, methods, and findings.  
- `README_Balatro_Project.txt` – Original project notes.  

### 🔹 Visuals (in `figs/`)  
- `totals_hist.png` – Histogram of total scores across runs.  
- `label_counts.png` – Distribution of run outcomes.  
- `chips_vs_mult.png` – Scatter plot showing chips vs. multiplier effect.  
- `cm_heatmap.png` – Confusion matrix heatmap for model validation.  
- `feature_importances.png` – Feature importance plot from ML models.  

### 🔹 Screenshots  
- `dataset_head.png` – Snapshot of dataset structure.  

---

## ⚙️ Tools Used  
- **Python** – Data analysis, simulations, machine learning.  
- **Pandas, NumPy** – Data wrangling and cleaning.  
- **Matplotlib, Seaborn** – Visualisations and plots.  
- **Scikit-learn** – Feature importance, confusion matrix, model evaluation.  
- **Excel / Word** – Supporting analysis and documentation.  

---

## 🔑 Key Skills Demonstrated  
- Data Cleaning & Pre-processing (CSV → DataFrames).  
- Exploratory Data Analysis (EDA) with Python.  
- Statistical Visualisation (histograms, scatter plots, heatmaps).  
- Feature Importance & Model Evaluation.  
- Technical Reporting (abstract + full report).  
- Reproducible Analysis (requirements.txt).  

---

## 📊 Sample Insights  
- Decks like **Plasma** can deliver high scores but depend on multiplier-driven jokers.  
- Chip vs. multiplier trade-offs are central to consistent success.  
- Feature importance analysis shows which run variables most strongly predict outcomes.  
- Confusion matrix highlights strengths and weaknesses in predictive models.  

---

## 🚀 How to Use  
1. Clone this repository.  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
