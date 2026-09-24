<div align="center">

![Header](https://capsule-render.vercel.app/api?type=rect&height=210&color=0:020617,100:1e3a8a&text=Thomas%20Flamand&fontColor=e5e7eb&fontSize=52&descAlignY=75&desc=Operations%20Research%20%7C%20Machine%20Learning%20%7C%20LLM%20Engineering&descSize=18)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=18&duration=3200&pause=1200&color=64748B&center=true&vCenter=true&width=820&lines=Optimization+and+simulation+for+operational+decisions;Machine+learning+with+rigorous+evaluation;Fine-tuning+language+models+for+regulatory+compliance)](https://github.com/thomasflamand)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Thomas%20Flamand-0f172a?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thomas-flamand/)
[![Email](https://img.shields.io/badge/Email-tf2636%40columbia.edu-0f172a?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tf2636@columbia.edu)
[![GitHub](https://img.shields.io/badge/GitHub-thomasflamand-0f172a?style=for-the-badge&logo=github&logoColor=white)](https://github.com/thomasflamand)

</div>

---

## About

Dual-degree graduate student working at the intersection of **operations research**, **machine learning** and **LLM engineering**. I like problems where a rigorous model has to survive contact with messy, real-world data: sizing systems, allocating scarce resources, and turning unstructured data into something a model can learn from.

Currently finishing my M.S. in Operations Research at Columbia University (graduating December 2026), after an AI engineering internship at Veolia North America.

---

## Recruiter Snapshot

| **Education** | **Experience** |
| --- | --- |
| **M.S. Operations Research**, Columbia University, New York (Aug 2025 - Dec 2026)<br>**MS & BS in Engineering**, CentraleSupélec, Paris-Saclay University (Sep 2022 - Dec 2026) | **AI Engineer (Intern)**, Veolia North America (2026)<br>**Data Engineer & Internal Tools Developer**, LightBlue Environmental Consulting (2025)<br>**GenAI Engineer & Consultant**, AI Sisters (2024 - 2025) |

**Core stack:** Python · SQL · PyTorch · scikit-learn · Gurobi · QLoRA / RAFT · Optuna

---

## What I Work On

- **Optimization & Operations Research**: mixed-integer programming, queueing theory, agent-based simulation
- **Machine Learning & Deep Learning**: feature engineering, model interpretability (SHAP), efficient Transformer architectures
- **LLM Engineering**: fine-tuning small language models (RAFT, QLoRA), training-data pipelines, retrieval-based applications

---

## Featured Work

### Optimization of NY State Child Care Expansion
[![Repository](https://img.shields.io/badge/Public%20Repository-111827?style=flat-square&logo=github&logoColor=fbbf24)](https://github.com/thomasflamand/Optimization_Childcare_Expansion)

- **Problem:** Childcare deserts across New York State: what is the minimum investment needed to eliminate them, and where should it go?
- **Solution:** Large-scale MILP (Gurobi) covering 1,600+ ZIP codes, under budget, spatial, fairness and capacity constraints.
- **Impact:** Spatial filtering of 200k+ sites cut costs by ~25%.
- **Stack:** Python · Gurobi · MILP · Spatial analysis

### Hybrid Queueing-Simulation Model for Rideshare Systems
[![Repository](https://img.shields.io/badge/Public%20Repository-111827?style=flat-square&logo=github&logoColor=fbbf24)](https://github.com/thomasflamand/Transportation_Hybrid_Fleet_Sizing)

- **Problem:** Determine optimal staffing of a rideshare system, and measure how far analytical queueing models drift from real-world operations.
- **Solution:** M/M/s model calibrated on real arrival and service rates, complemented by an agent-based simulation with spatial dynamics and routing constraints.
- **Impact:** Exposed the bias of the queueing model and identified realistic staffing ranges under real-world conditions.
- **Stack:** Python · Queueing theory · Agent-based simulation

### Improving Efficient Vision Transformers with Relative Positional Encodings
[![Repository](https://img.shields.io/badge/Public%20Repository-111827?style=flat-square&logo=github&logoColor=fbbf24)](https://github.com/thomasflamand/Data_Mining_ViT_Performers)

- **Problem:** Linear-attention Transformers are cheaper than full attention but tend to lose accuracy under limited compute budgets.
- **Solution:** Implemented Performer-based ViTs (FAVOR+, ReLU) with several RPE variants (RoPE, General RPE, Circulant-STRING) and benchmarked accuracy against inference time on MNIST and CIFAR-10.
- **Impact:** Showed that RPEs close the performance gap with full attention under limited compute budgets.
- **Stack:** Python · PyTorch · Transformers · Efficient attention

### Airbnb Price Prediction
[![Repository](https://img.shields.io/badge/Public%20Repository-111827?style=flat-square&logo=github&logoColor=fbbf24)](https://github.com/thomasflamand/Airbnb_Price_Prediction)

- **Problem:** Which factors drive Airbnb prices in New York City, and how robust is a published pricing pipeline once reproduced?
- **Solution:** Reproduced the Kalehbasti et al. (2019) pipeline on 50k+ NYC listings (feature engineering, Lasso-based feature selection, sentiment extraction from reviews) for log-price prediction, then extended it with Optuna-tuned models and stacking ensembles.
- **Impact:** Best stacking ensemble reaches **R² = 0.754**. SHAP analysis of the key price drivers, linear vs non-linear model comparison, and robustness assessed through multi-seed experiments (mean ± std of MAE and R²).
- **Stack:** Python · scikit-learn · LightGBM · Optuna · SHAP · NLP

### Also on my GitHub
- [Multi-Date Remote Sensing Change Detection](https://github.com/thomasflamand/Multi-Date_Remote_Sensing_Change_Detection): change detection on multi-date remote sensing imagery

---

## Professional Experience

### Veolia North America: AI Engineer (Intern) · Paramus, NJ · Jun - Aug 2026
*Proprietary work, no public repository.*
- Engineered a **small language model with RAFT** for regulatory compliance in water utilities, processing **18,000+ documents** into an **85M-token training corpus**.
- Built and ran a **9-step data cleaning pipeline** turning scraped regulatory documents into production-ready training data.
- Tuned **QLoRA** parameters under GPU memory constraints with **Optuna**, establishing the architecture for fine-tuning deployment.

### LightBlue Environmental Consulting: Data Engineer & Internal Tools Developer · Bangkok · Feb - Jul 2025
- Optimized Python data pipelines and built a **real-time internal dashboard** for KPI analysis across **150+ hotels and 200+ kitchens**.
- Built a **benchmarking engine (2M+ data points)**, defining classification frameworks and performance indicators with the CEO and executive managers.
- Designed the data architecture and workflows of a new Food Intel Tech (FIT) solution, from data collection to client reporting.

### AI Sisters: GenAI Engineer & Consultant · Paris · Aug 2024 - Feb 2025
- Led end-to-end development of GenAI solutions, from problem framing to iterative refinement with clients, **cutting repetitive operation times by a factor of 5-10**.
- Delivered consulting on AI integration and team training, leading to **6 development contracts**.
- Built LLM-based applications with prompt engineering and retrieval pipelines to improve response quality and consistency.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-0f172a?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-0f172a?style=flat-square)
![MATLAB](https://img.shields.io/badge/MATLAB-0f172a?style=flat-square)

**Machine Learning & Data**

![PyTorch](https://img.shields.io/badge/PyTorch-0f172a?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0f172a?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0f172a?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-0f172a?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-0f172a?style=flat-square&logo=numpy&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-0f172a?style=flat-square)
![Optuna](https://img.shields.io/badge/Optuna-0f172a?style=flat-square)

**Optimization & Simulation**

![Gurobi](https://img.shields.io/badge/Gurobi-0f172a?style=flat-square)
![MILP](https://img.shields.io/badge/MILP-0f172a?style=flat-square)
![Queueing Theory](https://img.shields.io/badge/Queueing%20Theory-0f172a?style=flat-square)
![Agent-Based Simulation](https://img.shields.io/badge/Agent--Based%20Simulation-0f172a?style=flat-square)

**LLMs**

![QLoRA](https://img.shields.io/badge/QLoRA-0f172a?style=flat-square)
![RAFT](https://img.shields.io/badge/RAFT-0f172a?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-0f172a?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-0f172a?style=flat-square)

---

## Beyond Code

- **Kickboxing:** 11 years of competition with international medals, including **2× World Champion, 5× Vice World Champion and 8× French Champion**. I also co-coached junior sections.
- **CentraleSupélec Student Sports Committee:** Head of Quality & IT (2022 - 2024). Led the ISO 9001 audit renewal for a 5,000-student sports organization and managed the license database for 6,000+ students.
- **Languages:** French (native), Spanish (intermediate)

---

<div align="center">

**Let's connect:** [LinkedIn](https://www.linkedin.com/in/thomas-flamand/) · [Email](mailto:tf2636@columbia.edu)

</div>
