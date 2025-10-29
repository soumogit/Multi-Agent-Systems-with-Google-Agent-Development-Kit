# 🧠 Build Multi-Agent Systems with Google Agent Development Kit (ADK)

This project demonstrates how to orchestrate **multi-agent workflows** using the **Google Agent Development Kit (ADK)**.  
It shows how agents collaborate in **sequential**, **looping**, and **parallel** structures to complete complex tasks — such as researching, drafting, and refining a film concept.

---

## 📘 Overview

The goal is to simulate a film concept team made of several agents that work together automatically once the user provides minimal input.


The system then:
- Researches the topic using Wikipedia  
- Writes and refines a script draft  
- Estimates box office performance  
- Suggests casting ideas  
- Compiles everything into a final report  

---

## 🧩 Architecture

The multi-agent system includes three main workflow types:

| Agent Type | Description |
|-------------|-------------|
| **SequentialAgent** | Executes steps one after another |
| **LoopAgent** | Iterates between agents for improvement cycles |
| **ParallelAgent** | Runs agents simultaneously and aggregates results |

---
## 🧱 Project Structure

MULTI_AGENT/
│
├── adk_multiagent_systems/
│   ├── Output_MultiAgent/
│   │   ├── ADK_Event_backend.png
│   │   ├── ADK_query_output.png
│   │   ├── ADK_query_output2.png
│   │   ├── ADK_Structured_output.png
│   │   ├── ADK_time_trace.png
│   │   ├── ADK_WiFi_Tech_Query.png
│   │   ├── cloudshell_terminal_output.png
│   │   └── cloudshell_terminal_output2.png
│   │
│   ├── parent_and_subagents/
│   │   ├── __init__.py
│   │   └── agent.py
│   │
│   ├── workflow_agents/
│   │   ├── __init__.py
│   │   └── agent.py
│   │
│   ├── callback_logging.py
│   ├── requirements.txt
│   └── README-cloudshell.txt


## 🧰 Technologies Used

| Component | Description |
|------------|-------------|
| **ADK (Google Agent Development Kit)** | Framework for building multi-agent systems |
| **Python 3.10+** | Programming environment |
| **Wikipedia Tool** | Used by the researcher agent for factual information |
| **File Writer Tool** | Used to aggregate and save final outputs |

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/your-username/multi-agent-adk-lab.git
cd multi-agent-adk-lab

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

---
