Real-Time Fraud Detection & Compliance Intelligence System
This project demonstrates a real-time fraud detection and compliance system that processes continuous transaction streams and analyzes them instantly. It identifies suspicious behavior using features like transaction amount, time of activity, and geographic patterns. A RAG + LLM assistant allows users to ask natural-language questions about fraud, compliance rules, and flagged activity, making insights easy to understand. With real-time alerts, dashboards, and a modular event-driven design, the system replicates how modern financial platforms monitor fraud dynamically and support compliance operations efficiently.
Problem Statement
Financial institutions struggle to detect fraud instantly because traditional batch systems are too slow. There is a need for a real-time system that analyzes transactions continuously, flags suspicious patterns immediately, and provides clear compliance insights through natural language.

Key Features

1. Live Data Ingestion
Simulated streaming feed (Kafka-like)
New events processed every 2 seconds
No batch reprocessing needed

2. Streaming Transformations
Real-time fraud scoring
Feature engineering (amount, time, geography)
Running aggregations and stateful metrics

3. RAG + LLM Assistant
Document store with policies and fraud cases
Answers natural questions like:
“Why was this transaction flagged?”
“Is this compliant with policy X?”

4. Production-Oriented Architecture
Instant alerts for risky transactions
Real-time dashboard for trends and patterns
Event-driven, low-latency design

5. Tech Stack
Python
Pathway
FastAPI
LLM + RAG
Streamlit / Grafana
