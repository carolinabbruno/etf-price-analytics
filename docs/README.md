# 📈 Stock Price Analytics for European ETFs  

This project captures and processes ** Price data for European ETFs**, using **Azure cloud services** and **Python-based stream processing**.

---

## 🔧 Tools Used  
- **Azure Event Hubs** – Ingest streaming ETF data  
- **Azure Stream Analytics OR Azure Databricks** – Real-time processing  
- **Azure SQL or Synapse Analytics** – Query & reporting layer  
- **Power BI** – Real-time visualizations  

---

## 🗂️ Data Flow Architecture  

1. ETF prices streamed via Python + WebSocket or API  
2. Stream written into **Azure Event Hubs**  
3. **Stream Analytics** transforms and aggregates data (e.g., price avg every minute)  
4. Results saved into **Azure SQL**  
5. **Power BI** dashboard shows price trends & alerts

---

## 📁 Folder Structure  

- `scripts/` – Python scripts to connect to ETF APIs and push to Event Hubs  
- `sql/` – Queries for processed results  
- `docs/` – Architecture diagram, setup guide  
- `notebooks/` – Analysis and experiment logs  
