AI-Assisted Ransomware Detection & Response Framework (BTRDF)

A Blue Team–focused ransomware detection and response framework that integrates Artificial Neural Network (ANN)–based anomaly detection with real-time system telemetry to improve threat detection, automated response, and recovery strategies using Microsoft Defender and Microsoft Sentinel.

Overview

The Blue Team Ransomware Defense Framework (BTRDF) is designed to enhance traditional endpoint detection by combining structured defensive workflows with ANN-based anomaly detection.

This project simulates ransomware activity within a controlled virtual lab and processes system telemetry (e.g., file modifications and process behavior) through a custom Python pipeline. The framework evaluates system behavior, assigns a risk score, and triggers simulated response and recovery actions.

The goal is to demonstrate how machine learning can augment existing Windows security tools to improve detection accuracy and response efficiency.

Key Features
Telemetry-Based Activity Analysis
Monitors system behavior such as file modification volume and process activity
ANN-Based Detection Model
Utilizes a trained Artificial Neural Network to generate a prediction score indicating likelihood of ransomware activity
Risk Scoring & Classification
Assigns severity levels (e.g., Low, Medium, High) based on model output
Automated Response Actions
Simulates defensive actions such as system isolation and process termination
Recovery Simulation (FFRecovery)
Demonstrates file restoration workflow following detected ransomware activity
SIEM & EDR Integration (Conceptual + Telemetry Alignment)
Aligns detection logic with capabilities of Microsoft Defender and Microsoft Sentinel
Tech Stack
Languages: Python
Security Tools: Microsoft Defender, Microsoft Sentinel
Environment: Windows 11, Virtualized lab (VMware)
Core Concepts:
SIEM monitoring & alert analysis
Endpoint telemetry analysis
Incident response workflows
Anomaly detection (ANN)
Detection Pipeline (Conceptual Flow)
Collect system activity metrics
File modifications
Process activity
Process telemetry through ANN model
Generate prediction score
Classify risk level
Trigger response action
Isolate system
Kill suspicious process
Execute recovery simulation
Restore files (FFRecovery model)
Sample Output
{
  "activity": {
    "file_modifications": 831,
    "process_activity": 34
  },
  "prediction_score": 0.8338,
  "risk_level": "High",
  "response_action": "Isolate System & Kill Process",
  "recovery_action": "Restore files using FFRecovery simulation",
  "suspicious": true
}
Results (In Progress)

The framework is currently undergoing structured testing across multiple simulated ransomware scenarios.

Metrics being evaluated:

Detection accuracy
False positive / false negative rates
Response effectiveness
Recovery time simulation

Preliminary observations indicate high detection sensitivity, with increased false positive rates—highlighting the importance of tuning ANN-based anomaly detection models in security environments.

Final results and performance analysis will be included upon completion of testing.

Project Status

🚧 In Progress — Final evaluation and manuscript development underway

Disclaimer

This project is for educational and research purposes only.
All simulations are conducted in a controlled virtual environment. No real systems or data are targeted.

Author

Valerie Alexander
Cybersecurity Student — SUNY Brockport
GitHub: https://github.com/jambo1026
