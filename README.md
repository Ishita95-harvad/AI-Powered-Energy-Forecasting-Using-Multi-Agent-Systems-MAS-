# AI-Powered Multi-Agent System for Renewable Energy Forecasting

This repository contains the simulation code, forecasting models (LSTM, Prophet, ARIMA), and optimization workflow for an MAS-based Smart Grid architecture.

## 🧠 Features
- Hybrid forecasting using LSTM, ARIMA, Prophet
- Decentralized multi-agent system with RL agents
- GridLAB-D simulation and optimization using MILP and PPO

## 📂 Structure
- `/notebooks` – Training and evaluation notebooks
- `/src` – Python modules for MAS agents and communication
- `/data` – Sample weather and load datasets
- `/simulation` – GridLAB-D files and PPO agent configs

# AI Smart Grid: Multi-Agent System for Renewable Forecasting and Optimization

This project demonstrates an AI-powered Multi-Agent System (MAS) designed for real-time energy forecasting, grid optimization, and climate-resilient decision-making.

## 📌 Key Features
- 📈 **Hybrid Forecasting**: LSTM, Prophet, ARIMA ensemble
- 🤖 **Multi-Agent System**: Autonomous decision-making using RL
- ⚡ **Optimization Algorithms**: MILP, GA, PPO for resource allocation
- 🌦 **Climate Resilience**: Weather-aware adaptive grid operations

## 📂 Folder Structure

| Folder | Description |
|--------|-------------|
| `/notebooks` | Forecasting models in Jupyter |
| `/src` | MAS agent logic and optimization modules |
| `/data` | Sample weather and load data |
| `/simulation` | GridLAB-D config for simulation |
| `/models` | Pretrained models (if any) |
| `/figures` | Architecture diagrams |
| `/docs` | Paper summary and presentation slides |

## 🚀 How to Run

```bash
pip install -r requirements.txt
python src/agent.py

## 🚀 Getting Started
pip install -r requirements.txt

python run_simulation.py

## 📜 Citation
If you use this code in your research, please cite the paper:
> Bahamnia, I. (2025). "Hybrid Forecasting and MAS Optimization for Smart Grids", *Elsevier Energy and AI*.



## 🔗 Related Resources

- 📜 [Research Paper (Preprint)](link_to_preprint.pdf)
- 📊 [Live Streamlit Dashboard (if deployed)](link_here)
- 📘 [Dataset DOI on Zenodo](https://doi.org/10.5281/zenodo.xxxxxx)
