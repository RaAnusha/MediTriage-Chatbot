🧠 MediTriage Chatbot
A conversational AI chatbot that performs preliminary triage of user-reported symptoms, classifies urgency levels, and provides basic healthcare guidance. It leverages transformer-based models (BERT or FLAN-T5) to understand natural language input and offer reliable triage results — not for diagnosis, but to assist healthcare decision-making.

🚀 Features
Conversational UI: Streamlit-powered interface for easy symptom reporting.

Transformer-Based Triage: Uses fine-tuned BERT or FLAN-T5 for intent classification and triage prediction.

Symptom-to-Triage Logic: Classifies input into one of four levels — Non-Urgent, Urgent, Emergency, Futile.

Care Recommendations: Suggests whether to self-manage, visit urgent care, or call emergency services.

Lightweight Deployment: Designed for quick prototyping and demonstration using Streamlit.

Ethics-Aware: Built with awareness of data privacy and responsible AI use.

🗂️ Project Structure
bash


MediTriage-Chatbot/
├── meditriage_app.py              # Streamlit UI script
├── meditriage_model_utils.py     # Model loading and prediction logic
├── requirements.txt
└── README.md
📦 Prerequisites
Python 3.9+

Streamlit

Transformers (HuggingFace)

Torch

joblib

Install required dependencies:

bash
pip install -r requirements.txt
⚙️ How to Run the Streamlit App
Clone the repository:

bash
git clone https://github.com/your-username/MediTriage-Chatbot.git
cd MediTriage-Chatbot

Launch the app locally:

bash
streamlit run meditriage_app.py
The chatbot will run at http://localhost:8501

🧠 Model and Data Info
Model: Fine-tuned BERT-based classifier

Training Data: Labeled symptom descriptions mapped to triage levels (simulated dataset)


📜 Disclaimer
This project is a prototype for academic purposes and not a substitute for professional medical advice, diagnosis, or treatment. In case of emergency, always consult a medical professional or call emergency services.

📚 Credits
HuggingFace Transformers

Streamlit

PyTorch

Scikit-learn / Joblib
