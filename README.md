# Quantum Semantic Communication Networks  
### Intelligent Link Selection for Hybrid Classical-Quantum Networks  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

## 📌 Overview  
This repository contains the implementation of an **intelligent link selection mechanism** for **hybrid classical-quantum communication networks**. Our approach integrates **Fuzzy Analytic Hierarchy Process (FAHP)** and **Technique for Order Preference by Similarity to Ideal Solution (TOPSIS)** for optimal network selection while considering:  
✅ **Classical Network Metrics** – Bit Error Rate (BER), Bandwidth, Latency  
✅ **Quantum Network Metrics** – Fidelity, Qubit Transfer Rate, Entanglement Quality  
✅ **Semantic Awareness** – Knowledge Graph Alignment, Semantic Fidelity  
✅ **Energy Efficiency** – Power Consumption Minimization  

## 🚀 Features  
- **FAHP-Based Dynamic Weighting**: Assigns real-time importance to classical, quantum, and semantic attributes.  
- **TOPSIS-Based Network Ranking**: Selects the best transmission link under dynamic conditions.  
- **Graph-Based Channel Translation**: Converts classical parameters into quantum equivalents adaptively.  
- **Semantic-Aware Link Selection**: Ensures the transmission preserves **meaningful information** in AI-driven applications.  
- **Energy Optimization Module**: Ensures power-efficient network selection.  

## 📂 Project Structure  
📁 Q-Semantic_Communication
│── 📜 README.md # Project Documentation
│── 📜 requirements.txt # Dependencies
│── 📜 LICENSE # MIT License
│── 📜 main.py # Core FAHP-TOPSIS Implementation
│── 📜 fuzzy_logic.py # Fuzzy Inference System
│── 📜 topsis_ranking.py # TOPSIS Network Ranking
│── 📜 graph_translation.py # Classical-to-Quantum Parameter Mapping
│── 📜 data_simulation.py # Network Data Simulation
│── 📁 results # Plots and Analysis
│── 📁 docs # Research Papers, References
│── 📁 tests # Test Cases

bash
Copy
Edit

## 🛠 Installation  
To run this project, ensure you have **Python 3.8+** installed. Then, clone the repository and install dependencies:  
```bash
git clone https://github.com/Prakash-Sankalan/Q-Semantic_Communication.git  
cd Q-Semantic_Communication  
pip install -r requirements.txt  
🏃‍♂️ Usage
Run the main script to execute FAHP-TOPSIS-based link selection:

bash
Copy
Edit
python main.py  
Modify data_simulation.py to simulate different network conditions and observe the model's adaptability.

📊 Results & Visualizations
The system generates dynamic plots showcasing network selection performance:
✅ Time-Series Analysis – How link quality evolves over time
✅ 3D Scatter Plot – Influence of BER and Bandwidth on link selection
✅ Correlation Heatmap – Relationships between classical, quantum, and semantic parameters
✅ Box Plot – Distribution of network selection metrics

🔬 Research Contributions
This project extends the work of Shantom Kumar Borah and Sainath Bitragunta on FAHP-TOPSIS-based hybrid network selection by introducing:

Semantic Fidelity as a Key Decision Factor
Adaptive Graph-Based Channel Translation
Dynamic Fuzzy-Based Weight Adjustment
Reinforcement Learning for Future Optimization
🔮 Future Work
🔹 Reinforcement Learning for FAHP Optimization
🔹 Hardware Deployment on FPGA-Based Routers
🔹 Integration with 6G and AI-Driven Semantic Networks
🔹 Quantum Key Distribution (QKD) Implementation


