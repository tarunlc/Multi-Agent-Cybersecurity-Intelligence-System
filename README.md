AI-Powered Cybersecurity Intelligence System
📌 Overview

This project is an AI-driven cybersecurity intelligence pipeline that automates the process of detecting, analyzing, and reporting vulnerabilities (CVEs). It integrates:

Tavily API for real-time enrichment from trusted sources

Google Gemini LLM for vulnerability analysis and summarization

Automated reporting in CSV, JSON, PDF, and HTML

The system computes custom priority scores to help teams focus on high-risk vulnerabilities first, enabling smarter and faster security decisions.

🚀 Features

🔍 Real-time CVE Enrichment using Tavily Search API

🤖 LLM Analysis with Gemini to assess exploit likelihood and patch status

📊 Custom Risk Scoring engine for prioritization

📑 Multi-format Reports: CSV, JSON, PDF, HTML

⚡ Re-enrichment Pipeline for low-confidence results

🔔 (Optional) Slack Notifications for team alerts

🛠️ Tech Stack

Python 3.12+

Tavily API – Real-time vulnerability search

Google Gemini LLM – AI-powered text analysis

Pandas – Data handling

ReportLab – PDF report generation

Rich – Console visualization


⚙️ Setup Instructions

Clone the repo

git clone https://github.com/yourusername/cyber-intelligence.git
cd cyber-intelligence


Install dependencies

pip install -r requirements.txt


Add your API keys (Tavily + Gemini) in environment variables.

Run the pipeline:

python main.py

📊 Example Output

CSV/JSON for data processing

PDF/HTML reports for management and compliance

Console visualization with color-coded risk scores

🌟 Impact

This project demonstrates real-world AI deployment in cybersecurity, automating vulnerability analysis and enabling organizations to strengthen their defense posture with minimal manual effort.
