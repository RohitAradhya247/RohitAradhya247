<h1 align="center">Hi, I'm Rohit 👋</h1>

<p align="center">
  <b>I build AI systems that check their own work.</b><br>
  MS in Artificial Intelligence at Northeastern University, Boston
</p>

<p align="center">
  <a href="https://rohitaradhya247.github.io"><img src="https://img.shields.io/badge/Website-rohitaradhya247.github.io-0D9488?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/rohit-rajashekar-aradhya"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:aradhya.ro@northeastern.edu"><img src="https://img.shields.io/badge/Email-Get_in_touch-4F46E5?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open_to-AI%2FML_co--ops,_Jan_to_Aug_2027-E11D48?style=flat-square" alt="Open to AI/ML co-ops, January to August 2027">
</p>

---

## About me

- 🎓 MS in Artificial Intelligence at **Northeastern University**, computer vision concentration, GPA 3.75, graduating December 2027
- 💼 15 months as an **Associate Software Engineer at Accenture**, keeping production automation on Azure Logic Apps and Function Apps running, handling incidents and tracing them to their root cause
- 🔍 Right now I'm building the **verifier and router for OpsPilot**, an LLM root-cause agent, and **CoreOps**, an end-to-end AI operations platform
- 🎯 Most interested in LLMs, agentic AI, verification and computer vision
- 🌏 From Bengaluru, now in Boston. Off the clock: cricket, travel and motorcycles

---

## Featured projects

### 🛡️ OpsPilot: verifier and router for an LLM root-cause agent
An LLM agent diagnoses the root cause of failures in microservice systems on the RCAEval benchmark. I own the layer that decides whether to trust that diagnosis.

- Six checks test every diagnosis against a DuckDB and Parquet evidence store: cited evidence, anomaly onset (robust z-score), timing, propagation path, fault signature and corroboration
- A router accepts the diagnosis, sends it back with feedback for up to two retries, or marks it unsure when evidence is missing
- On the agent's first real diagnosis, the verifier caught it citing evidence it had never retrieved
- About 25 PRs merged and 700+ tests passing. Evaluation is still ahead, so no accuracy numbers yet

`Python` `LLM agents` `DuckDB` `Parquet` `Ollama` · [Repository](https://github.com/Adhithyan245/OpsPilot)

### 🏗️ CoreOps: AI operations platform for an e-commerce company
A tested data warehouse, a secure role-based API, dashboards, a chatbot and AI agents with a verifier, built on the real Olist dataset of about 100,000 orders.

- Phases 0 and 1 done: 1,550,922 rows loaded with 0 rejected, 151 of 151 dbt tests passing and 8 of 8 reconciliation checks
- Spotted that the dataset's apparent "sales collapse" was unfinished orders missing from the export, and handled it with a 49-day maturity cut-off so delivery metrics aren't flattered
- Phase 2, the secure API with role-based access and a tamper-proof audit log, is in progress
- Built with Claude Code under a phase-gated review process I designed

`PostgreSQL` `dbt` `FastAPI` `Docker` `GitHub Actions` · Repository private for now

### 👁️ VisionPilot: uncertainty-aware multi-agent vision system
Compares a team of specialist vision models, coordinated by agents, against a single vision-language model. It uses uncertainty-aware abstention, so it declines to answer when it isn't sure instead of guessing. In progress, aimed at a conference submission.

`PyTorch` `TensorFlow` `Agents` `Vision-language models`

### 🛣️ Road damage detection with YOLOv8
Detects potholes and three kinds of cracks in street photos. Raised mAP@50 from 0.326 to 0.529 across 3,027 images, then field-tested on our own Boston photos and traced the misses to gaps in the training data.

`YOLOv8` `PyTorch` `OpenCV` · [Repository](https://github.com/RohitAradhya247/Road_Damage_Detection_Proj)

### 🗽 NYC 311 service request prediction
Predicts whether a city service request closes within 72 hours, across 100,000 messy records and five classifiers. ROC-AUC 0.922, and found that resolution rates fall from about 80% to 67% during business hours.

`scikit-learn` `Pandas` `SMOTE` · [Repository](https://github.com/Sonikakv/NYC311_Project)

### 🛒 Autonomous shopping cart return
A cart that drives itself back to the corral, simulated in ROS 2 and Gazebo, with a GPS-IMU Extended Kalman Filter holding position error far below raw GPS noise.

`ROS 2` `Gazebo` `Sensor fusion` `EKF`

### 🌾 Raitha Saathi
My undergraduate final-year project: a crop price forecasting system built with ICAR-IIHR Bengaluru and selected for the Karnataka Government NAIN initiative. I led data cleaning and model training.

`Python` `Random Forest`

---

## Tech I work with

**AI and ML**<br>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
<img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat-square" alt="YOLOv8">
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code">

**Data and backend**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB">
<img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt">
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">

**Cloud and tools**<br>
<img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Microsoft Azure">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
<img src="https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 2">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">

**Certifications:** Microsoft Azure AI Fundamentals (AI-900) and Azure Fundamentals (AZ-900)

---

<p align="center"><i>Want to talk AI, agents or co-ops? The quickest way to reach me is <a href="mailto:aradhya.ro@northeastern.edu">email</a>.</i></p>
