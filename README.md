# Semantic Context-Aware SOC Alert Prioritization

## Overview
A system that automatically prioritizes SOC alerts by mapping them 
to MITRE ATT&CK techniques using semantic embeddings. Built to reduce 
alert fatigue for SOC analysts by surfacing the most critical threats first.

## Dataset
- CICIDS (Canadian Institute for Cybersecurity Intrusion Detection Dataset)

## How It Works
1. SOC alerts are processed and cleaned from the CICIDS dataset
2. Each alert is encoded using MiniLM sentence embeddings
3. Alerts are semantically mapped to the closest MITRE ATT&CK technique
4. A Flask dashboard visualizes alert priority and ATT&CK mapping in real time

## Tools & Technologies
- Python
- Jupyter Notebook
- MiniLM (Sentence Transformers)
- MITRE ATT&CK Framework
- Flask (Dashboard)
- CICIDS Dataset

## Project Status
🔧 Currently in active development
