# 🧑‍⚕️ Elderly Care System – SafeHaven  

## 📌 Overview  
SafeHaven is an AI-powered system designed to enhance elderly care and safety.  
The project integrates **three machine learning/deep learning models** to monitor health and detect risks in real-time.  
All models are deployed using **FastAPI**, containerized with **Docker**, and hosted on **Azure** for scalable cloud deployment.  

---

## 🔬 AI Models Included  

### 1. 🩸 Elderly Vital Signs Monitoring  
- Monitors key vital signs (e.g., heart rate, body temperature, oxygen levels).  
- Classifies patient health status into **3 stages** (Normal – Discomfort – Critical).  
- Helps predict risk **before emergencies happen**.  

### 2. 🤸 Activity Classification  
- Uses motion and acceleration data.  
- Machine Learning model that classifies elderly daily activities.  
- Detects abnormal movement patterns.  

### 3. 🚨 Fall Detection  
- Deep Learning model that analyzes video/image sequences.  
- Detects if an elderly person has fallen.  
- Can trigger an **alert system** for caregivers.  

---

## ⚙️ Tech Stack  
- **Languages/Frameworks:** Python, FastAPI, TensorFlow, Scikit-learn  
- **Deployment:** Docker, DockerHub, Azure Cloud  
- **Other Tools:** Pandas, NumPy, Matplotlib  
