# 🛡️ AI-Enhanced Intrusion Detection System (IDS)  
### *Cybersecurity Threat Detection Using Machine Learning*

---

## 📌 Project Description

In an increasingly interconnected digital landscape, the security of organizational networks and sensitive data is of paramount importance. This project focuses on the development of an **AI-Enhanced Intrusion Detection System** that leverages machine learning to detect, classify, and respond to network intrusions with high accuracy.

By combining advanced **Random Forest Classification** with cybersecurity domain knowledge, the system empowers organizations to proactively combat evolving threats.

---

## 🖼️ **Demo Screenshots**

### 🔹 Home Page  

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1dXUPq0OiRTV-h09iJhoJWNhBYuqw6VjY" width="800" alt="Home Page Screenshot">
</p>

### 🔹 Classification Result  
<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1fgDNk36_GoGV3AdLgkA0_0z7ZEo7gtcz" width="800" alt="Classification Results Screenshot">
</p>


---

## 🛠️ **Technologies Used**

- **Python 3.10+**
- **Flask (Backend Web Framework)**
- **HTML / CSS (Frontend UI)**
- **Pandas / NumPy (Data Manipulation)**
- **Scikit-learn (Machine Learning)**
- **Imbalanced-learn (SMOTE for Class Balancing)**
- **Joblib (Model Serialization)**

---

## 🧠 **Model Details**

The Intrusion Detection System uses a **Random Forest Classifier** trained on a preprocessed and balanced network intrusion dataset. The model is enhanced with **SMOTE** to handle class imbalance.

The final model is saved as:

```bash
random_forest_model_4_features.joblib
```

---

## 🗂️ **Project Directory Structure**

```
CYBER-AI-ENHANCED-INTRUSION-DETECTION/
├── CYBER_PROJECT/
│ ├── templates/
│ │ └── index.html                             # Web interface template
│ └── app.py                                   # Flask application entry point
├── random_forest_model_4_features.joblib      # Trained ML model
├── web_attacks_balanced.csv                   # Preprocessed dataset
├── requirment.txt                             # Python dependencies
├── Untitled.ipynb                             # Data analysis / experimentation notebook
└── README.md                                  # Project documentation
```

---

## ⚙️ **Installation & Setup**

### 📦 Using Conda (Recommended)

```bash
conda create -n cyber_ids python=3.10
conda activate cyber_ids
git clone https://github.com/your-username/cyber-ai-ids.git
cd cyber-ai-ids
pip install -r requirment.txt
```

### 🐍 Using Python venv

```bash
python -m venv ids_env

# Windows:
ids_env\Scripts\activate

# macOS/Linux:
source ids_env/bin/activate

pip install -r requirment.txt
```

> **Note:** Make sure to install **Flask** and **scikit-learn** separately if not included in the requirements.

---

## 🚀 **Running the Application**

```bash
cd Flask
python app.py
```

Open your browser and go to:  
👉 `http://localhost:5000`

---

## 📁 **Dataset Overview**

The web_attacks_balanced.csv dataset includes labeled network traffic data categorized into different types of intrusions and normal behavior.

---

## 🔮 **Future Enhancements**

- Add real-time network traffic capture and classification
- Enable email/SMS alerts for high-risk threats
- Integrate logs into a security dashboard
- Add more ML models like XGBoost and Neural Networks

---

## ✅ **Conclusion**

This project showcases how artificial intelligence and machine learning can be effectively applied to cybersecurity for real-time intrusion detection and network threat mitigation. With high accuracy and automation, this AI-powered IDS reduces response time and enhances the overall security posture of an organization.


