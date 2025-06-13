# 🛡️ Phishing Detection Using Deep Learning

This project focuses on detecting phishing emails and URLs using a deep learning-based hybrid model combining **CNN** and **LSTM** architectures. The system was built during an R&D collaboration with **CyberGuard360**, where I contributed to model development and deployment as part of their team.

> 🔗 [Live Demo (Deployed Site)](https://phishguard360.vercel.app/)  
> 🔗 [Model on Hugging Face](https://huggingface.co/Phishguard/PhishGuard)

---

## 🧠 Model Architecture

- **CNN (Convolutional Neural Network)**:  
  Extracts local n-gram patterns from email content and URLs.

- **LSTM (Long Short-Term Memory)**:  
  Captures long-term dependencies and contextual features for better phishing detection.

---

## 🧪 Key Feature Analyses

### 📧 Email Phishing Detection:
- **Header Analysis**:  
  Inspects `From`, `Reply-To`, and `Received` fields to identify spoofing attempts.
- **Textual Analysis**:  
  Applies deep learning to detect suspicious phrases and patterns in the email body.

### 🌐 URL Phishing Detection:
1. **Lexical Analysis**:  
   Features include:
   - URL length
   - Use of symbols (e.g., `@`, `-`)
   - Keyword presence (e.g., "secure", "account", "login")
   - Subdomain count

2. **Host-Based Analysis**:  
   Analyzes:
   - Domain age and WHOIS info
   - SSL certificate details
   - IP reputation and DNS info

---

## 🏗️ Project Source

> 🎯 [PhishGuard Model Repository on Hugging Face](https://huggingface.co/Phishguard/PhishGuard)

---

## 👩‍💻 Contributions

As a part of the R&D team at **CyberGuard360**, my contributions included:
- Integrating CNN + LSTM models for phishing classification
- Feature engineering for both email and URL datasets
- Assisting with deployment and frontend communication with the model API

---

## 🚀 Deployment

> 🌐 [Phishing Detection App](https://phishguard360.vercel.app/)  
A user-friendly web interface that accepts URLs for real-time phishing detection.

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Natural Language Processing (NLP)
- Deep Learning (CNN + LSTM)
- Vercel (Frontend deployment)
- Hugging Face (Model hosting)

---

## 📁 File
Research ppt-phishing detection.pptx


