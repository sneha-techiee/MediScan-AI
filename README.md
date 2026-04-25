# MediScan-AI

🚀 MediScan AI – Symptom-Based Disease Prediction System
🧠 Overview

MediScan AI is a machine learning-powered web application that predicts probable diseases based on user-reported symptoms. It provides confidence scores to assist users in making informed healthcare decisions.

⚠️ This system is for educational and informational purposes only and does not replace professional medical advice.

💡 Motivation

Healthcare accessibility remains a major challenge, especially in developing regions. MediScan AI aims to:

Provide quick preliminary health insights
Reduce unnecessary hospital visits
Assist in early detection of diseases
🎯 Features
🔍 Symptom-based disease prediction
📊 Confidence scores for each prediction
⚡ FastAPI-powered backend
🌐 Interactive web interface
🧠 Random Forest ML model (94% accuracy)
🔗 REST API for integration
🏗️ Tech Stack

Frontend

HTML, CSS, JavaScript

Backend

FastAPI (Python)

Machine Learning

Scikit-learn (Random Forest)

Database (optional)

JSON / Local storage
⚙️ System Architecture
User → Frontend → FastAPI → ML Model → Prediction → UI Display
📊 Dataset Details
Diseases: 15
Symptoms: 54
Samples: ~980
Accuracy: 94.2%
🧪 API Endpoints
Endpoint	Method	Description
/api/symptoms	GET	List all symptoms
/api/diseases	GET	List diseases
/api/predict	POST	Get prediction
🚀 Installation & Setup
# Clone repo
git clone https://github.com/your-username/MediScan-AI.git

# Navigate
cd MediScan-AI

# Install dependencies
pip install -r requirements.txt

# Run server
uvicorn main:app --reload
🧠 Model Details
Algorithm: Random Forest
Trees: 200
Max Depth: 15
Accuracy: 94.2%
📸 Future Improvements
🔬 Add more diseases & real datasets
📱 Mobile app version
🧾 Medical report upload
🤖 Deep learning integration
🌍 Multi-language support
🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

📜 License

This project is licensed under the MIT License.

👩‍💻 Author

Sneha Rajpoot
🔗 LinkedIn: https://www.linkedin.com/in/sneha-rajpoot-792105318/
