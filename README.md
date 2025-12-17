# Finance-AI-agent  
### AI Agent for Automated Financial Report Analysis

This project develops an AI-powered agent capable of analysing annual financial reports, extracting key figures, computing standard financial ratios, and generating peer-review style insights.  
The system supports Latvian company reports and handles financial data in PDFs, providing multilingual output.

The agent combines:
- **LLM-based extraction** (OpenAI GPT-4o, Groq Llama-3, Gemini Flash 2.5)
- **Structured parsing** using a Pydantic schema
- **Python-based financial ratio calculations** (liquidity, profitability, solvency)
- **Plotly visualisations** for cross-company comparison
- **Interactive user interfaces** implemented with Gradio, Hugging Face Spaces, and Streamlit for uploading PDFs, exploring results, and exporting structured outputs (TXT, CSV)


This repository contains the full project portfolio, including code, data, methodology artefacts, meeting minutes, presentations, and results.

---

## 👥 Team Members & Roles

### **Anjali Shibu — Lead Application Developer**  
Designed and implemented the core AI agent pipeline, including LLM integration, PDF ingestion, Pydantic schema extraction, ratio calculation modules, and the full Gradio application. Developed the executable Python workflows and ensured end-to-end functionality. Contributed to the project concept and documentation.

### **Sandra Usane — Data Processing & Evaluation Lead**  
Processed and validated extracted financial data, tested the agent on real annual reports, verified calculation correctness, and refined prompts for accuracy and robustness. Conducted evaluation, debugging, and quality assurance across the pipeline. Co-developed the project idea, proposal, and portfolio documentation.

### **Aleksandrs Skraucis — Visualisation & UI Enhancement Lead**  
Participated in project ideation and proposal development. Contributed to design discussions for visualisation strategy and user experience. Supported the project documentation and final presentation materials.

---

## Annotated Table of Contents  

### **Project Documentation**
| Item | Description | Contributor(s) |
|------|-------------|----------------|
| [`/project_proposal`](project_proposal/) | Final project proposal| Anjali (40%), Sandra (40%), Aleksandrs (20%) |
| [`/meeting_minutes`](meeting_minutes/) | Weekly meeting notes documenting project process | Anjali (20%), Sandra (60%), Aleksandrs (20%) |
| [`/methodology_artifacts`](methodology_artifacts/) | Gantt chart, Risk register, methodology | Anjali (40%), Sandra (40%), Aleksandrs (20%) |

### **Notebooks**
| Item | Description | Contributor(s) |
|------|-------------|----------------|
| [`/notebooks/Finance_AI_Agent.ipynb`](notebooks/Finance_AI_Agent.ipynb) | Development notebook | Anjali (60%), Sandra (20%), Aleksandrs (20%) |

### **Data & Results**
| Item | Description | Contributor(s) |
|------|-------------|----------------|
| [`/data/raw_pdfs`](data/raw_pdfs/) | Annual report PDFs used for testing | Sandra (80%), Aleksandrs (20%) |
| [`/results/outputs`](results/outputs/) | Extracted tables, peer review text outputs | Anjali (35%), Sandra (35%), Aleksandrs (30%) |

### **Presentations & Reports**
| Item | Description | Contributor(s) |
|------|-------------|----------------|
| [`/presentations/final_presentation.pdf`](presentations/final_presentation.pdf) | Final project presentation | Team |

### Deployment

| Item | Description | Contributor(s) |
|------|------------|---------------|
| [Deployment & Live Demonstrations](#-deployment--live-demonstrations) | Publicly accessible AI agent deployments (Hugging Face & Streamlit) | Anjali (60%), Sandra (20%), Aleksandrs (20%) |
| [Deployment Source Code Repository](https://github.com/anjalii-s/AI_Agent_for_Latvian_Financial_Report_Analysis-) | Deployment-specific implementation and configuration | Anjali (70%), Sandra (15%), Aleksandrs (15%) |


---

## How to Run the Project

### **Requirements**
- Python 3.10+  
- API key for one of:
  - OpenAI (GPT-4o)
  - Groq (Llama-3)
  - Google Gemini (Flash 2.5)
 
## Deployment & Live Demonstrations

In addition to the development notebook and local prototype, the Finance-AI-agent has been deployed as publicly accessible applications to demonstrate real-world usability, reproducibility, and scalability.

### Hugging Face Spaces Deployment
A hosted version of the AI agent is available on Hugging Face Spaces, allowing users to upload annual financial reports and interact with the system through a web interface.

- **Live application:**  
  https://huggingface.co/spaces/Anjali488/AI_agent_deployment
- **Purpose:** Demonstrates end-to-end functionality, including PDF ingestion, LLM-based financial data extraction, automated ratio calculation, and narrative financial analysis.
- **Technology:** Python, Hugging Face Spaces, Gradio

**Contributors:** Anjali (60%), Sandra (25%), Aleksandrs (15%)

---

### Streamlit Cloud Deployment
A parallel deployment has been implemented using Streamlit Cloud to explore an alternative user interface and deployment environment.

- **Live application:**  
  https://financialaiagent.streamlit.app/
- **Purpose:** Provides an interactive dashboard-style interface for financial analysis and visualisation.
- **Additional functionality:** Allows users to export extracted financial data and computed ratios in TXT and CSV formats for further analysis or reporting.
- **Technology:** Python, Streamlit, Plotly

**Contributors:** Anjali (60%), Sandra (20%), Aleksandrs (20%)


---

### Deployment Source Code Repository
All deployment-specific source code and configuration files are maintained in a separate public GitHub repository to ensure a clear separation between development, experimentation, and production deployment.

- **Repository:**  
  https://github.com/anjalii-s/AI_Agent_for_Latvian_Financial_Report_Analysis-
- **Contents:**  
  - Streamlit application source code  
  - Hugging Face Spaces configuration  
  - Environment and dependency setup files

**Contributors:** Anjali (70%), Sandra (20%), Aleksandrs (10%)

---

### Note on Project Structure
This repository focuses on the project portfolio, including research process evidence, methodology artefacts, notebooks, datasets, results, and documentation.  
Deployment-specific code is intentionally maintained in a separate repository in line with best practices for modular and maintainable project organisation.

 

### **1. Clone the repository**
```bash
git clone https://github.com/yourusername/Finance-AI-Agent.git
cd Finance-AI-Agent




