# returns-risk-prediction
Predict high-return fashion e-commerce orders to reduce logistics losses

🔹 📌 Problem → Action → Result (for README + Notion)
🧠 Problem
Returns are a major cost for fashion e-commerce brands — due to sizing issues, delayed delivery, or mismatch between product expectations and reality. Predicting high-risk orders before delivery can help reduce unnecessary logistics costs and improve customer satisfaction.

⚙️ Action
Developed a machine learning pipeline using XGBoost to classify orders with high return probability, based on features like order history, product type, price band, location, customer profile, and historical return behavior. Used SHAP for model explainability and MLflow for experiment tracking. Built on Azure ML & deployed a scoring API using FastAPI.

📈 Result
Achieved 87% precision on high-return orders. Enabled operations to proactively flag risky deliveries, change shipping providers, or notify customers. Potential to reduce return-related logistics costs by 15% across 100+ high-SKU products.
