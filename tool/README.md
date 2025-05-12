
# AI-Enhanced Breach and Attack Simulation Tools

## Problem Statement

Cyberattacks are growing in frequency and sophistication, putting organizations at constant risk. Traditional security testing methods (like manual penetration testing) are resource-intensive, infrequent, and often miss new attack techniques.

There is a need for an automated, continuous, and realistic way to test and validate security defenses.

This tool simulates real-world cyberattacks, generates synthetic security logs mapped to the MITRE ATT&CK framework, and leverages AI for anomaly detection and incident narrative generation. It enables security teams, students, and researchers to proactively identify gaps in their defenses—all without risking real systems or sensitive data.

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/neha27-28/AI-Enhanced-Breach-and-Attack-Simulation-Tools.git
cd AI-Enhanced-Breach-and-Attack-Simulation-Tools
```

### 2. Install Dependencies

Make sure you have Python 3.9+ installed.  
Install required packages:

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App

```bash
streamlit run app.py
```

---

## Photos for Reference

### 1. Architecture or Flowchart

**Architecture:**

![flowchart](image.png)

**Detailed Flowchart:**

![detailed flowchart](image-1.png)

### 2. Dashboard

![module ss](image-2.png)  
![module ss](image-3.png)  
![module ss](image-4.png)  
![module ss](image-5.png)

*The images are present in the source code folder under the image section*
---

## Python File Overview

- `mitre_mapping.py`:  
  Maps security events to MITRE ATT&CK tactics and techniques.

- `attack_scenarios.py`:  
  Contains predefined attack chains (e.g., Credential Theft, Ransomware).

- `log_generator.py`:  
  Generates synthetic logs from attack scenarios, with MITRE mapping and contextual details.

- `breach_narrator.py`:  
  Uses an AI language model to generate a human-readable narrative of the simulated attack.

- `anomaly_detector.py`:  
  Applies machine learning (Isolation Forest) to detect anomalies in the generated logs.

---

## Features

- Predefined attack scenarios (Credential Theft, Ransomware, Phishing, etc.)
- Synthetic log generation with MITRE ATT&CK mapping
- AI-powered breach narration
- Anomaly detection using machine learning
- Interactive Streamlit dashboard for analysis and visualization

---

## Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you would like to change.

---

## Contact

For questions, suggestions, or demo requests, please contact:  
**nehakasera1823@gmail.com**
