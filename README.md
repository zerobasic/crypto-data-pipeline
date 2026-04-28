# 🚀 End-to-End Data Pipeline with API Ingestion, Transformation & Analytics Dashboard

Production-style data pipeline using Python, PostgreSQL and API ingestion

---

## 📌 Overview

This project demonstrates a production-style data pipeline that ingests data from an external API, processes it, stores it in a database, and visualizes insights through a dashboard.

The goal of this project is to showcase practical Data Engineering skills such as data ingestion, transformation, storage, and analysis.

---

## 🧠 Architecture

```
API → Python (ETL Pipeline) → PostgreSQL → Dashboard (Streamlit)
```

---

## ⚙️ Tech Stack

* Python
* pandas
* PostgreSQL
* SQLAlchemy
* requests
* Streamlit
* Docker (optional)

---

## 🔄 Features

* Automated data ingestion from external API
* Data cleaning and transformation
* Storage in relational database
* Analytical queries using SQL
* Interactive dashboard for visualization
* Logging and error handling
* Modular and scalable code structure

---

## 📊 Example Insights

* Price trends over time
* Top performing assets
* Volatility analysis

---

## 📁 Project Structure

```
src/
 ├── ingestion/
 ├── processing/
 ├── storage/
 ├── pipeline/

dashboard/
tests/
config/
```

---

## 🚀 How to Run

### 1. Clone repository

```
git clone https://github.com/zerobasic/crypto-data-pipeline.git
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run pipeline

```
python src/pipeline/run_pipeline.py
```

### 4. Start dashboard

```
streamlit run dashboard/app.py
```

---

## 🧪 Tests

```
pytest tests/
```

---

## 🎯 Future Improvements

* Cloud integration (AWS / Azure)
* Real-time data streaming
* Machine learning predictions

---

## 👨‍💻 Author

Heiko Mehlfeld
