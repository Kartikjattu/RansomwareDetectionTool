# RansomwareDetectionTool
An AI-powered ransomware detection and monitoring system built using Python and Machine Learning. The system monitors processes, detects malicious file behavior, performs signature-based and ML-based detection, and quarantines suspicious files in real-time.

## 📌 Project Overview
This project is an AI-powered ransomware detection system developed using Python and Machine Learning.  
It monitors system activities, detects ransomware behavior using signature-based and ML-based detection techniques, and quarantines suspicious files.
## 🚀 Features
- ✅ Real-time Process Monitoring
- ✅ Signature-based Detection
- ✅ Machine Learning Detection Model
- ✅ File Hash Checking
- ✅ Quarantine System
- ✅ Logging System (SQLite Database)
- ✅ Web Interface (Flask)
- ✅ Dataset-based Model Training
## 🛠️ Technologies Used
- Python
- Flask
- Machine Learning (Scikit-learn)
- SQLite Database
- HTML & CSS
- Pandas & NumPy
## 📂 Project Structure
RansomwareDetectionTool/
│
├── app.py
├── monitor.py
├── process_monitor.py
├── signature_detector.py
├── ml_model.py
├── database.py
├── quarantine.py
├── utils.py
│
├── dataset/
│   └── ransomware_dataset.csv
│
├── templates/
│   ├── index.html
│   └── logs.html
│
├── static/
│   └── style.css
│
├── ransomware_model.pkl
├── ransomware_logs.db
├── ransomware_hash_db.txt
├── requirements.txt
└── README.md
## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/your-username/AI-Ransomware-Detection-Tool.git
cd AI-Ransomware-Detection-Tool
### 2️⃣ Install Dependencies
pip install -r requirements.txt
### 3️⃣ Run the Application
bash
python app.py

## 🧠 How It Works
1. Monitors running processes
2. Checks file hashes against known ransomware database
3. Uses ML model to predict suspicious behavior
4. Logs activity in SQLite database
5. Quarantines detected threats
## 📊 Dataset
The dataset used for training the model is located in:
dataset/ransomware_dataset.csv
## 🎯 Future Improvements
- Deep Learning based detection
- Cloud-based monitoring
- Email alert system
- Advanced behavior analysis
## 👨‍💻 Author
Final Year Project  
B.Tech / BCA / MCA Cyber Security / Computer Science
## 📜 License
This project is for educational purposes only.
