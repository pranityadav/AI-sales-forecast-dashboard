# 📊 AI-Powered Sales Forecast Dashboard

This is a data analytics project built with **Python, pandas, numpy, scikit-learn, and Streamlit**, aimed at predicting future sales using historical data. The dashboard provides interactive visualizations and simple machine learning forecasts.

> 🔗 GitHub Repo: https://github.com/pranityadav/AI-sales-forecast-dashboard

---

## 🚀 Features

- Upload your own sales CSV file
- Visualize historical sales trends
- Forecast future sales using Linear Regression
- Interactive slider to adjust forecast range
- Clean, beginner-friendly UI built with Streamlit

---

## 📁 Project Structure
AI-sales-forecast-dashboard/
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
├── config/
│   └── settings.py
├── data/
│   ├── sample_data.csv
│   └── README.md
├── src/
│   ├── __init__.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── linear_model.py
│   │   └── tree_models.py
│   ├── utils/
│   │   ├── __init__.py
│   │   ├── data_processor.py
│   │   └── visualizations.py
│   └── pages/
│       ├── __init__.py
│       ├── home.py
│       └── forecast.py
└── tests/
    └── test_models.py
---

## 🧠 Technologies Used

- Python 3.x
- pandas, numpy
- scikit-learn
- Streamlit
- matplotlib

---

## 📈 How It Works

1. Upload a sales dataset (CSV with `date` and `sales` columns)
2. Dashboard displays raw data and sales trend
3. Model fits the past data using Linear Regression
4. Forecasts future sales for a user-selected range (e.g., 30 days)
5. Forecast and actual data are plotted together

---

## 📸 Screenshot
<img width="1018" height="527" alt="Screenshot 2025-07-24 at 2 48 14 PM" src="https://github.com/user-attachments/assets/a0803542-bc04-4eb0-8362-752e0922fa48" />

<img width="996" height="729" alt="Screenshot 2025-07-24 at 2 43 09 PM" src="https://github.com/user-attachments/assets/75749047-2520-484b-ad66-2edac596b430" />

<img width="1033" height="517" alt="Screenshot 2025-07-24 at 2 47 36 PM" src="https://github.com/user-attachments/assets/bc9a920e-f145-486c-98cb-e97e73265c4d" />

<img width="1067" height="529" alt="Screenshot 2025-07-24 at 2 47 53 PM" src="https://github.com/user-attachments/assets/72527f0d-3ff3-42ca-bb5e-e038891d3373" />


You can place a screenshot in the `screenshots/` folder and embed it like this:
---

## 🛠️ How to Run

1. Clone this repo:
```bash
git clone https://github.com/pranityadav/AI-sales-forecast-dashboard.git
cd AI-sales-forecast-dashboard
