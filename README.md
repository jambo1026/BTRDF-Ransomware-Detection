AI-Assisted Ransomware Detection Framework (BTRDF)
Overview

This project presents the Blue Team Ransomware Defense Framework (BTRDF), a simulation-based system that integrates Artificial Neural Network (ANN)-assisted detection with existing Windows security tools (Microsoft Defender & Microsoft Sentinel) to improve ransomware detection, response, and recovery.

Rather than replacing existing tools, this framework enhances their effectiveness by structuring detection outputs into a unified workflow and supporting decision-making through AI-driven analysis.

 Objectives
Improve ransomware detection using ANN-based behavioral analysis
Reduce alert fatigue through threshold tuning and structured analysis
Integrate detection, response, and recovery into a unified framework
Demonstrate practical application through a real-time dashboard
 Key Features
ANN-based anomaly detection using system activity (file modifications, process activity)
Simulation of ransomware behavior in a controlled environment
Real-time dashboard for threat monitoring and analysis
Risk classification and automated response actions
FFRecovery simulation for recovery processes
Performance metrics tracking (accuracy, false positive rate, response time)
 How It Works
Simulated system activity is generated (normal and ransomware behavior)
Data is processed by the ANN model
The model outputs a prediction score (0–1)
A classification threshold determines if activity is suspicious
The BTRDF framework executes:
Detection
Analysis
Response
Recovery
 Results Summary
ANN significantly improved detection sensitivity compared to baseline methods
Default threshold (0.5) resulted in high false positive rates (~70%)
Overall accuracy reached approximately 80%
Threshold tuning improved classification balance and reduced unnecessary alerts
Demonstrates the tradeoff between detection accuracy and alert volume
 System Demonstration

(Add your screenshots in the screenshots/ folder and they will display here)

![Dashboard](screenshots/dashboard.png)
![Threat Analysis](screenshots/threat_analysis.png)
![Live Log](screenshots/live_log.png)
![Performance Chart](screenshots/chart.png)
Performance Metrics
Accuracy: ~80%
False Positive Rate: ~70% (default threshold)
Real-time analysis: ~0.13 seconds
Response time: ~2–2.5 seconds
Recovery time: ~2–3.5 seconds
Technologies Used
Python (Flask)
TensorFlow / Keras
NumPy
HTML/CSS (frontend dashboard)
VMware (virtual lab environment)
Microsoft Defender & Microsoft Sentinel (simulated integration)
 Project Structure
BTRDF-Ransomware-Detection/
│
├── app.py
├── model/
├── data/
├── templates/
│   └── index.html
├── static/
├── screenshots/
├── docs/
│   ├── paper.pdf
│   └── poster.pdf
├── requirements.txt
└── README.md
 Future Work
Integration with real-world datasets and telemetry
Advanced models (LSTM, deep learning architectures)
Dynamic threshold tuning
Direct integration with SIEM/EDR platforms
Automated response playbooks
Documentation
Research Paper: docs/paper.pdf
Poster: docs/poster.pdf
 Author

Valerie Alexander
Cybersecurity Student – SUNY Brockport
GitHub: https://github.com/jambo1026
