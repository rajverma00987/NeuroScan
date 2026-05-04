# 🧠 Alzheimer's Prediction

A deep learning–based project for **early detection of Alzheimer's Disease (AD)** using MRI image data and explainable AI (XAI) techniques.  
The system predicts the cognitive condition of a patient and classifies them into stages for better understanding and medical interpretation.

---

## 📋 Project Overview
Alzheimer’s Disease is a progressive neurodegenerative disorder that affects memory and cognition.  
This project builds an intelligent model that predicts the stage of Alzheimer’s and provides **explainable visual insights** to help clinicians interpret model decisions.

---

## 🚀 Key Features
- 🧩 **Deep Learning Model** for MRI-based Alzheimer’s classification  
- 🔍 **Explainable AI (XAI)** visualization for each prediction  
- 🌐 **Web Interface** for easy patient image upload and results display  
- 🧠 **Four-Class Prediction:**
  - **Alzheimer’s Disease (AD)**
  - **Cognitively Normal (CN)**
  - **Early Mild Cognitive Impairment (EMCI)**
  - **Late Mild Cognitive Impairment (LMCI)**
- 📦 Organized modules for training, inference, and deployment

---


---

## ⚙️ Installation & Setup

### Prerequisites
- Python 3.8+
- Node.js (latest LTS)
- pip and npm installed

### Steps
```bash
# Clone the repository
git clone https://github.com/ketanjain113/Alzimers-Prediction.git
cd Alzimers-Prediction

# Backend setup
cd node_server
npm install

# Model setup
cd ../Model
pip install -r requirements.txt
```

---

## 🧪 Usage

- Launch the website.
- Upload a patient MRI image.
- View the predicted class (AD, CN, EMCI, LMCI).
- Examine the XAI explanation map to understand which regions influenced the model’s decision.

---

## 📊 Model Insights

Trained on labeled MRI scans (Alzheimer's vs control) using TensorFlow/Keras with transfer learning from medical imaging backbone

--- 

## 🤝 Contributing

Contributions are welcome!
If you’d like to improve model accuracy, UI/UX, or documentation:

- Fork this repo
- Create a new branch (feature-name)
- Commit your changes
- Open a Pull Request

---

## 💬 Contact

Author: Raj verma For questions or collaboration, please open an issue or contact via GitHub.
