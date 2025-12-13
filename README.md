# Finance-AI-agent  
### AI Agent for Automated Financial Report Analysis

This project develops an AI-powered agent capable of analysing annual financial reports, extracting key figures, computing standard financial ratios, and generating peer-review style insights.  
The system supports Latvian company reports and handles financial data in PDFs, providing multilingual output.

The agent combines:
- **LLM-based extraction** (OpenAI GPT-4o, Groq Llama-3, Gemini Pro)  
- **Structured parsing** using a Pydantic schema  
- **Python-based financial ratio calculations** (liquidity, profitability, solvency)  
- **Plotly visualisations** for cross-company comparison  
- **A Gradio UI** for uploading PDFs and receiving analysis  

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
| [`/meeting_minutes`](meeting_minutes/) | Weekly meeting notes documenting project process | Team |
| [`/methodology_artifacts`](methodology_artifacts/) | Gantt chart, Risk register, methodology | Team |

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

---

## 🚀 How to Run the Project

### **Requirements**
- Python 3.10+  
- API key for one of:
  - OpenAI (GPT-4o)
  - Groq (Llama-3)
  - Google Gemini Pro  

### **1. Clone the repository**
```bash
git clone https://github.com/yourusername/Finance-AI-Agent.git
cd Finance-AI-Agent



