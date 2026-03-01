# 🚀 MuleNet  
### A Unified Cross-Channel Entity Graph for High-Velocity Mule Ring Detection

> Transforming fraud detection from isolated transaction monitoring to network-level intelligence.

---

## 📌 Problem Statement

Money mule networks exploit fragmentation across financial channels — Mobile App, Web Banking, UPI, and ATM — to rapidly move illicit funds across multiple accounts within minutes.

Traditional fraud systems fail because they:

- Operate in **channel silos**
- Use **static rule thresholds**
- Lack **relationship intelligence**
- Cannot detect **multi-hop, high-velocity fund movement**

The real challenge is not detecting a suspicious transaction —  
it is detecting a **suspicious network in motion**.

---

## 💡 Our Solution: MuleNet

**MuleNet** is a real-time fraud intelligence platform that unifies cross-channel transaction data into a dynamic **Entity Relationship Graph**.

Instead of analyzing isolated transactions, MuleNet evaluates **network behavior**.

### Core Capabilities

- 🔗 **Unified Entity Graph**  
  Integrates App, Web, ATM, and UPI data into a single relationship network.

- ⚡ **Velocity-Based Detection**  
  Flags unusually short time gaps between transaction hops.

- 🔄 **Multi-Hop Chain Detection**  
  Identifies rapid fund movement across multiple accounts.

- 🧠 **Cluster Identification**  
  Detects coordinated mule rings using structural patterns.

- 📊 **Network-Level Risk Scoring**  
  Calculates risk based on routing depth, transaction complexity, velocity, and behavior.

- 💸 **Fragmentation & Structuring Detection**  
  Identifies splitting of funds or multiple small inbound transfers to avoid detection.

---

## 🏗 System Architecture

### 1️⃣ Data Sources
- Mobile App Transactions  
- ATM Withdrawals  
- UPI Transfers  
- Web Banking Logs  

### 2️⃣ Event Ingestion Layer
- FastAPI-based ingestion  
- Streaming simulation  

### 3️⃣ Entity Graph Builder
- Dynamic account relationship graph  
- Time-stamped transaction edges  

### 4️⃣ Detection & Risk Engine
- Velocity analysis  
- Multi-hop chain detection  
- Cluster detection  
- Behavioral risk scoring  

### 5️⃣ Output & Action Layer
- Risk scores  
- Flagged mule clusters  
- Automated blocking triggers  
- Streamlit dashboard visualization  

---

## 🧠 Core Detection Logic

### Graph Formation
- Each transaction becomes a time-stamped edge.
- Accounts are modeled as dynamic nodes.
- Multi-hop chains emerge over time.

### Velocity & Pattern Analysis
- Calculates time differences between hops.
- Measures transaction chain depth.
- Detects repeating structural patterns.
- Identifies fund fragmentation and structuring.

### Risk Scoring
A transaction or cluster is flagged if:

- Time between hops is unusually short  
- Chain depth exceeds defined threshold  
- Structural pattern repeats across accounts  

Suspicion is derived from **network behavior**, not isolated events.

---

## 🛠 Tech Stack

### Backend & Processing
- Python
- FastAPI
- Pandas
- NetworkX

### Visualization
- Streamlit
- Plotly

### Future Scaling Layer
- PyTorch Geometric (Graph Neural Networks)
- Neo4j / TigerGraph
- Apache Kafka

---

## 📊 Business & Regulatory Impact

### For Financial Institutions
- Near real-time mule ring detection  
- Cross-channel visibility  
- Reduced fraud losses  
- Lower false negatives  

### For Regulators
- Transparent network-level explanations  
- Risk scores with confidence metrics  
- Graph-based explainability  
- Regulatory-ready reporting  

---

## 🚀 Roadmap

### Phase 1 – Hackathon MVP
- Unified transaction graph  
- Velocity-based mule detection  
- Initial cluster identification  

### Phase 2 – Intelligent Learning
- Graph Neural Network integration  
- Structural anomaly detection  
- Adaptive pattern recognition  

### Phase 3 – Ecosystem Intelligence
- Cross-bank privacy-safe intelligence sharing  
- Jurisdiction-based risk scoring  
- Advanced structuring detection  

---

## ⚙️ How to Run

```bash
git clone <your-repo-link>
cd MuleNet
pip install -r requirements.txt
python app.py
streamlit run dashboard.py
```

---

## 📂 Sample Dataset Format

```
transaction_id
sender_account
receiver_account
amount
timestamp
channel
```

---

## 👥 Team

MindMesh  
Hackathon: Intellect Hackathon  
Date: March 2026  

---

## 🌟 Vision

MuleNet transforms fraud monitoring from reactive transaction blocking to proactive, network-intelligent defense — continuously adapting to evolving financial crime patterns.
