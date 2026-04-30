AI-Assisted Ransomware Detection & Response Framework (BTRDF)

A Blue Team cybersecurity project focused on improving ransomware detection, response, and recovery using Artificial Neural Networks (ANN) and native Windows security tools, including Microsoft Defender and Microsoft Sentinel.

Overview

The Blue Team Ransomware Defense Framework (BTRDF) is designed to enhance traditional ransomware detection by combining structured defensive strategies with ANN-based anomaly detection.

This project demonstrates how existing security tools can be orchestrated with machine learning techniques to improve:

Early detection of ransomware activity
Automated response actions
System recovery strategies

The framework is tested within a controlled virtual lab environment simulating real-world ransomware attack scenarios.

Key Features
ANN-Based Anomaly Detection
Identifies suspicious system behavior using machine learning–driven pattern recognition
SIEM & EDR Integration
Utilizes Microsoft Defender and Microsoft Sentinel for telemetry collection and analysis
Simulated Attack Environment
Virtual lab designed to replicate ransomware behavior and defensive monitoring
Automated Response Actions
Includes simulated containment actions such as system isolation and process termination
Risk Scoring & Threat Classification
Assigns severity levels based on detected activity patterns
Tech Stack
Languages: Python
Security Tools: Microsoft Defender, Microsoft Sentinel
Environment: Windows 11, Virtualized lab (VMware)
Concepts:
SIEM monitoring
Incident response
Anomaly detection
Threat modeling
Project Structure (Optional – update if you add files later)
/btrdf-project
│── data/                # Simulated telemetry data
│── models/              # ANN model(s)
│── scripts/             # Detection & processing logic
│── results/             # Output logs and evaluation results
│── README.md
Results (In Progress)

The system is currently undergoing structured testing and evaluation within a controlled virtual environment.

Metrics being analyzed include:

Detection accuracy
False positive and false negative rates
Response time and recovery time
Comparative performance against baseline detection methods

Preliminary findings indicate a tradeoff between detection sensitivity and false positive rates, highlighting the challenges of tuning anomaly-based detection models.

Final results and full analysis will be added upon completion of testing.

Project Status

🚧 In Progress — Final evaluation and documentation underway

Disclaimer

This project is for educational and research purposes only.
All testing is conducted in a controlled lab environment. No real systems or data are targeted.

Author

Valerie Alexander
Cybersecurity Student — SUNY Brockport
GitHub: https://github.com/jambo1026
- Comparative performance against baseline detection methods

Final results and analysis will be added upon completion of testing.

## Author
Valerie Alexander
