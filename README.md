### 📘 ` `

This repository provides the full Python implementation for the paper **"Explainable Air Quality Management: Adaptive Federated XGBoost Enhanced by SHAP Analysis and Sequential Anomaly Detection."** It presents a scalable, interpretable, and privacy-preserving framework for urban air quality prediction using distributed IoT sensor data.

Key components include:

* **Federated Learning with Adaptive Aggregation:** XGBoost models are trained locally at edge nodes, and aggregated using performance-aware weights to handle non-IID data.
* **SHAP Explainability:** SHapley Additive exPlanations are used to provide both global and instance-level feature importance for AQI predictions.
* **PrefixSpan Anomaly Detection:** A sequential pattern mining algorithm is applied to identify temporal irregularities in pollutant patterns.
* **Real-world Deployment:** Evaluated across 22 districts in Tehran with accuracy reaching **98.64%**, MSE as low as **15.52**, and explainability insights highlighting PM2.5, NO₂, and PM10 as key contributors.

📊 **Dataset Access**
The dataset used in this study, titled *“Anomaly-Aware Air Quality Monitoring with SHAP and PrefixSpan in Federated IoT Networks”*, is publicly available on Kaggle:
🔗 [https://www.kaggle.com/datasets/saghar001/air-quality-prediction-case-study](https://www.kaggle.com/datasets/saghar001/air-quality-prediction-case-study)

🔧 **Code Repository**
The complete codebase is available on GitHub:
🔗 [https://github.com/SagharShafaati/AdaptiveFL-XGB-QuantumXAI](https://github.com/SagharShafaati/AdaptiveFL-XGB-QuantumXAI)
