# 📦 Samantradat: Smartphone Manufacturing Transactions Dataset

## 📖 Description
This dataset contains 100,000 synthetic manufacturing transaction records representing smartphone assembly operations within a factory environment. The dataset was generated through domain modeling based on analysis of a real smartphone assembly workflow demonstrated in a factory tour video by GadgetIn on YouTube. It simulates event-level manufacturing processes including assembly, testing, calibration, packaging, and repair. The dataset is intended for educational, research, and data experimentation purposes in manufacturing analytics, process mining, and machine learning.

---

## 📊 Data Dictionary

| Column | Description |
|--------|------------|
| transaction_id | Unique transaction identifier |
| timestamp | Event timestamp of manufacturing process |
| factory_id | Factory identifier (synthetic) |
| production_line | Assembly line identifier |
| station_id | Workstation identifier |
| operator_id | Anonymized operator ID |
| device_id | Unique device traceability ID |
| model | Smartphone model name |
| process_type | Process category (assembly, test, calibration, packaging, repair) |
| component | Component being processed |
| action | Action performed (install, test, connect, etc.) |
| machine_id | Machine or equipment identifier |
| result | Process result (OK / NG / REWORK) |
| defect_code | Defect category (if applicable) |
| cycle_time_sec | Process duration in seconds |
| material_batch | Material batch identifier |

---

## 🎥 Source Inspiration
Business process reference derived from smartphone assembly workflow observation in factory tour video by [https://www.youtube.com/watch?v=U76imVp-OgQ]GadgetIn (YouTube – Realme 12 Pro+ assembly process).

---

## ⚠️ Disclaimer
This dataset is fully synthetic and does not represent any real company, factory, or proprietary production data. It was created solely for educational and analytical experimentation purposes.