# 📈 Capital Asset Pricing Model (CAPM) Web App

An interactive web-based dashboard built using **Streamlit** to analyze the risk and return characteristics of selected stocks using the **Capital Asset Pricing Model (CAPM)**. This tool helps investors and finance students visualize financial data, calculate beta values, and estimate expected returns based on market movements.

---

## 🚀 Features

- 📊 Visualize and compare multiple stock prices over time.
- ⚖️ Normalize stock prices for comparative analysis.
- 📅 Calculate **daily returns** of selected stocks.
- 🧮 Perform regression to compute **Beta** and **Alpha** values.
- 📈 Estimate **expected returns** using the CAPM formula.
- 🔍 Analyze historical S&P 500 data as a market benchmark.

---

## 📚 What is CAPM?

The **Capital Asset Pricing Model (CAPM)** is a fundamental concept in finance that explains how securities are priced based on their risk compared to the overall market. It helps in understanding:

- How much return an investor should expect for taking a certain level of risk.
- The relationship between **systematic risk** (Beta) and **expected return**.
- Whether a stock is overvalued or undervalued compared to its risk.

### CAPM Formula:
```
Expected Return = Risk-Free Rate + Beta × (Market Return - Risk-Free Rate)
```

---

## 🌐 Applications of the Project

This project is ideal for:

- 🧑‍🎓 **Finance Students & Researchers**: Understand and apply CAPM with real-world stock data.
- 💼 **Investors & Analysts**: Analyze the risk profile of a stock using its beta and estimate returns.
- 📊 **Educators & Trainers**: Demonstrate financial concepts interactively in lectures or workshops.
- 🧪 **Quantitative Finance Projects**: Extend it with other risk/return models or portfolio optimization.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – UI for building the web dashboard
- **Pandas** – Data handling and transformation
- **Plotly** – Interactive financial visualizations
- **yFinance** – Fetch historical stock price data
- **pandas_datareader** – Get S&P 500 index from FRED

---

## 📂 Project Structure

```
.
├── app.py                  # Main Streamlit app
├── capm_function.py        # Custom module for utility functions
├── requirements.txt        # List of Python packages used
├── README.md               # This file
└── screenshots/            # Folder for images to include in documentation
```

---

## 🔧 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/capm-streamlit-app.git
   cd capm-streamlit-app
   ```

2. **(Optional) Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
   ```

3. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**
   ```bash
   streamlit run app.py
   ```



## 📝 Future Improvements

- Add user-defined risk-free rate input
- Display alpha vs beta scatter plot
- Export results to Excel or PDF
- Add multiple benchmarks (e.g., Nasdaq, Dow Jones)
- Portfolio CAPM analysis

---

## 📬 Contact

If you find this useful or have ideas for improvements, feel free to:

- ⭐ Star the repository
- 🛠️ Fork and contribute
- 🐛 Open an issue for suggestions or bugs

---
