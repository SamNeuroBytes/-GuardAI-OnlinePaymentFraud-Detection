# 🛡️ GuardAI: Online Payment Fraud Detection & AI Assistant
GuardAI is a hybrid financial security platform that combines traditional Machine Learning for high-precision fraud detection with Generative AI for intelligent user support.

By utilizing the CatBoost algorithm and a custom RAG (Retrieval-Augmented Generation) pipeline, GuardAI provides both security and explainability for modern digital transactions.

# 🚀 Key Features
Real-time Fraud Prediction: Analyzes transactions instantly using a CatBoost model optimized for high-precision (
P
r
e
c
i
s
i
o
n
≈
1.00
).

Intelligent Feature Engineering: Calculates "Balance Inaccuracy" (mismatches between transaction amounts and balance changes) to identify fraudulent patterns.

Context-Aware AI Assistant: A built-in chatbot powered by Google Gemini 2.0 Flash and Agno (Phidata) that answers user queries about transaction fields and security alerts.


Vector Search Knowledge Base: Uses PostgreSQL with pgvector to store and retrieve application documentation for the chatbot.


Modern Web UI: A clean, responsive dashboard built with Flask and Bootstrap 5.


# 🛠️ Technical Stack
Backend: Python (Flask)

Machine Learning: CatBoost, Scikit-learn, Pandas, NumPy

Generative AI: Google Gemini 2.0 Flash, Agno Framework (Phidata)

Database: PostgreSQL + pgvector (Vector Database)

Frontend: Bootstrap 5, Animate.css

# 📊 Dataset
The model is trained on the Online Payments Fraud Detection Dataset from Kaggle.

Source: Kaggle Dataset Link

Size: ~6.3 Million rows (Note: dataset.csv is excluded from this repo due to size; please download it manually for training).

