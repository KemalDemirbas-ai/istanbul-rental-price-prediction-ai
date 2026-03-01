# 🚀 Project : Istanbul Real Estate Valuation AI

**Technical Status:** End-to-End Pipeline (Web Scraping & Deep Learning)  
**Architecture:** Keras / TensorFlow & Selenium  

This project serves as the "Economic Valuation Intelligence" module of our autonomous AI ecosystem. It is designed to forecast rental house prices in Istanbul's dynamic real estate market using advanced analytical approaches rather than traditional estimations.

### ⚙️ Pipeline Architecture
1. **Autonomous Data Collection:** Scraping live real estate data from Zingat using Selenium and BeautifulSoup.
2. **Feature Engineering:** Processing, scaling, and extracting meaningful features from the raw data.
3. **Neural Engine Training:** Comparing classical Machine Learning models (Linear Regression, Random Forest) with a Deep Learning architecture built using Keras and TensorFlow.

### 📦 Exported Neural Engine
Following strict MLOps practices, the trained deep learning model has not been left strictly as code. It has been serialized and exported as a production-ready artifact (`rental_prediction_model.keras`). While a live web interface (Streamlit) is not implemented for this specific phase, the engine is fully prepared for future API integration and cloud deployment.

---

### 📊 Data Architecture
Due to security, intellectual property, and data governance standards, the raw database (`istanbul_rental_houses.csv`) is not hosted in this repository. The schematic structure of the data ingested by the system is as follows:

| District | Number of Rooms | Square Meters (m2) | Building Age | Estimated Rent (₺) |
| :--- | :--- | :--- | :--- | :--- |
| Kadikoy | 2+1 | 90 | 5 | 35,000 |
| Besiktas | 3+1 | 120 | 10 | 50,000 |

---
*Developed as part of the Mastering Data Science With Deep Learning Architecture.*
