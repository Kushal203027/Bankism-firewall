🛡️ Bankism AI — Enterprise Financial Defense System

Real-Time Multi-Vector Defensive Firewall & Prompt Injection Shield for Autonomous Financial Workflows

🚀 Overview

Bankism AI is a next-generation security command center engineered to protect autonomous banking systems, APIs, and financial AI agents from modern multi-vector attacks. While traditional network firewalls inspect IP packets and standard WAFs look for basic SQL signatures, Bankism AI inspects natural language prompts, transaction payloads, and behavioral velocities simultaneously in real time.

Designed for high-impact hackathon presentation, Bankism combines rigorous cybersecurity heuristics with an immersive, high-tech dark-mode UI to deliver instantaneous threat mitigation and transparent audit logging.

🎯 The Problem Statement

As financial institutions rapidly adopt autonomous AI agents and automated microservices to process wire transfers, invoice settlements, and customer support, they expose themselves to entirely new categories of vulnerabilities:

Adversarial Prompt Injections: Attackers bypass guardrails using jailbreak payloads (SYSTEM OVERRIDE: IGNORE ALL SAFETY RULES) to execute unauthorized fund transfers.

Multi-Vector Payloads: Blended attacks combining SQL/XSS code injection with financial transaction parameters.

Account Takeover & Velocity Fraud: Rapid-fire micro-transactions designed to exhaust limits before fraud detection triggers.

The Solution: An inline, real-time defensive proxy layer that intercepts requests, calculates a composite risk index, and neutralizes threats before they ever reach core banking ledgers.

⚡ Key Features

🛡️ Multi-Vector Inspection Engine: Scans raw request streams for prompt overrides, malicious code injection, and velocity anomalies.

🕹️ Interactive Live Attack Bench: Allows judges and security operators to test pre-configured adversarial attack vectors with one click.

📊 Composite Risk Gauge: Dynamic Plotly visualization calculating real-time threat indices (0–100 scale) against configurable action thresholds.

⚡ Automated Decision Gateway: Instantaneous blocking or authorization logic with clear telemetry feedback.

📜 Live Defensive Audit Trail: Enterprise-grade telemetry logging timestamps, attack vectors, source origins, and firewall actions.

🛠️ Tech Stack

Core Logic: Python

Web Framework & UI: Streamlit (Custom Cybersecurity Dark Theme)

Data Processing: Pandas, NumPy

Visualizations: Plotly (Interactive Risk Gauges & Analytics)

Version Control & Hosting: Git, GitHub, Streamlit Community Cloud

⚙️ Local Setup & Installation

If you wish to run or evaluate Bankism AI locally on your machine, follow these simple steps:

Clone the Repository:

git clone https://github.com/Kushal203027/Bankism-firewall.git
cd Bankism-firewall


Create and Activate a Virtual Environment:

python -m venv venv
# On Windows:
.\venv\Scripts\Activate.ps1
# On macOS/Linux:
source venv/bin/activate


Install Dependencies:

pip install -r requirements.txt


Launch the Application:

streamlit run app.py


📊 Architecture Workflow
      
      [Incoming User Prompt / API Payload] 
                      │
                     ▼
    [Bankism Inline Defensive Engine] ──(Heuristic & Regex Pattern Scan)
                      │
                      ▼
    [Composite Risk Index Calculation] (0 - 100 Threat Score)
                      │
            ┌─────────┴─────────┐
            ▼                   ▼
     [Risk >= Threshold]    [Risk < Threshold]
           │                      │
           ▼                      ▼
    ⛔ BLOCKED (Alert)      ✅ PASSED (Forward to Ledger)
            │                   │
            └─────────┬─────────┘
                      │
                      ▼
           [Live Audit Trail Logged]  


🏆 Live Demo

Experience the live application deployed on Streamlit Cloud:

🔗 Bankism AI Live App : https://bankism-firewall-bnunjmmpnr79mxxsnv6wbg.streamlit.app/

📝 License

This project is open-source and available under the MIT License.
