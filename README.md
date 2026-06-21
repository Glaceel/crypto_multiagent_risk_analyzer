# Autonomous Multi-Agent System for bitcoin Technical Analysis & Portfolio Risk Management

An advanced AI orchestrator built on Langflow that utilizes a Multi-Agent architecture to process structured financial data (.csv) and deliver autonomous risk management recommendations without numerical hallucinations.

![Langflow Architecture](Screenshot_2026-06-20_182336.png)

## 🌟 Key Features
- **Multi-Agent Separation of Concerns**: 
  - **Agent 1 (Data Analyst)**: Parses raw historical CSV data and utilizes external computation tools.
  - **Agent 2 (Risk Manager)** : Evaluates the calculated technical metrics against market logic to output executive risk decisions.
- **Function/Tool Calling Integration**: Combines Gemini 1.5 Flash with an external Calculator Tool to eliminate LLM numerical hallucination during volatility math.
- **Context-Aware Parsing**: Handles raw content messages seamlessly from dynamic historical price datasets.

## 🛠️ System Workflow
