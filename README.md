# _**LI Junxing**_

_李俊星_ _Jasen_

[العربية](/ar/) · **EN** · [Español](/es/) · [فارسی](/fa/) · [Français](/fr/) · [हिन्दी](/hi/) · [日本語](/ja/) · [한국어](/ko/) · [Русский](/ru/) · [中文](/zh/)

> Welcome to this site! This page contains more details about me.<br>

## 🙋 Profile

Research engineer with a mathematics and statistics background, working across quantitative research engineering, financial data infrastructure, computer-vision post-processing, and enterprise AI-agent delivery. I can take a problem from definition and experimental validation through reproducible data/model workflows, engineering delivery, and user-facing documentation.

My current practice combines quantitative data platforms and signal research with RankSEG image-segmentation research engineering and practical AI-agent workflow design. I care about systems that are testable, repeatable, and useful in real operating environments.

**Current focus:** quantitative research engineering, financial data infrastructure, research platforms, trading-data services, and AI solutions / agent automation.

## 🌈 Color Balance

```text
Color   Share   Bar            Meaning
-----   -----   ------------   ---------------------------------------------
Black   40.6%   ████████░░░░   Agency, achievement, strategic execution
Blue    26.9%   █████░░░░░░░   Understanding, mastery, analytical depth
Red     14.4%   ███░░░░░░░░░   Intensity, candor, pressure tolerance
White   12.7%   ███░░░░░░░░░   Structure, order, stability
Green    5.4%   █░░░░░░░░░░░   Connection, emotional attunement, harmony
```

My profile is strongly Black-Blue: action paired with analysis.

- Black shows up as drive, agency, and a bias toward getting things done.
- Blue adds precision, curiosity, and a preference for understanding how systems actually work.
- Red contributes some appetite for pressure, directness, and intensity.
- White is present, but secondary: I value structure when it improves execution.
- Green is the least prominent, which means I am less naturally oriented around emotional atmosphere or consensus-building.

### Core Pattern

I do my best work when there is a difficult problem, a real constraint, and enough room to think clearly.

I am drawn to environments where rigor matters, where complexity is not avoided, and where outcomes can be judged by whether they hold up in practice. I tend to trust methods that are testable, repeatable, and grounded in reality. I would rather build a working system than produce a persuasive description of one.

In teams, this often means I contribute through problem-solving, structure, and execution. I may not always lead with warmth or visibility, but I tend to care by making things work, reducing ambiguity, and carrying difficult tasks across the finish line.

### Reference

- SoulTrace Result: <https://soultrace.app/en/results/48093f7c-7980-4f83-97a2-e5b8df3a103f>

## 🎓 Education

- **City University of Hong Kong** *(Sep 2025 – Oct 2026)*  
  *Master of Science in Statistics*

- **Qingdao University of Technology** *(Sep 2020 – Jun 2024)*  
  *Bachelor of Science in Mathematics and Applied Mathematics*

## 💼 Internship & Research Experience

### **Sika China**
*AI Agent Intern | Apr 2026 – Jul 2026*

- **Requirements decomposition and delivery:** Worked across AI product support, internal solutions, data automation, and business operations for repetitive, experience-dependent workflows.
- **Agent/skill design:** Turned loosely defined business needs into structured inputs, rules, MVPs, feedback loops, and acceptance criteria.
- **Internal rollout:** Supported agent enablement, user training, SOP documentation, and reusable workflow assets while keeping business information within appropriate boundaries.
- **Business automation:** Built and adapted practical automations for data processing, knowledge retrieval, reporting, and presentation workflows, balancing visual quality, editability, and reuse.

### **The Chinese University of Hong Kong (CUHK)**
*Part-time Research Assistant | Feb 2026 – Present*

- **Research engineering:** Drove research engineering and deployment of the [RankSEG](https://github.com/rankseg/rankseg) image-segmentation post-processing algorithm, covering reproduction, framework adaptation, inference integration, evaluation, and cluster packaging.
- **Framework integration:** Advanced RankSEG across mmsegmentation, PaddleSeg, Hugging Face Transformers, and SAM-family paths; designed interfaces for Dice/IoU-oriented post-processing without retraining.
- **Reproducible evaluation:** Built evaluation, logging, and result-tracking workflows to improve comparability, debugging, and reproduction stability.
- **HPC packaging:** Packaged Singularity + Slurm environments on CUHK HPC and prepared reusable multi-GPU job templates.
- **Open-source collaboration:** Contributed through merged [Transformers PR #19](https://github.com/rankseg/rankseg/pull/19), [SAM integration PR #20](https://github.com/rankseg/rankseg/pull/20), [integration documentation PR #22](https://github.com/rankseg/rankseg/pull/22), and [MONAI PR #2](https://github.com/rankseg/MONAI/pull/2).

### **Zhejiang Mingce Asset Management Co., Ltd.**
*Quantitative Architecture Intern | Sep 2025 – Apr 2026*
*Quantitative research engineering and digital-asset data infrastructure*

- **Data platform:** Built a quantitative research platform covering about 8 years of history and the liquidity Top 40 digital assets, integrating OHLCV data, on-chain indicators, and derived factors.
- **Columnar architecture:** Managed roughly 170 million minute-level records, 3,000 candidate features, and about 20 GB of Parquet data; reworked storage around Parquet, S3-compatible object storage, DuckDB/Polars, and MySQL metadata.
- **Query and refresh optimization:** Added partitioning, incremental collection, validation, and backups, reducing typical research queries from 1–3 minutes to 5–15 seconds and keeping daily updates within 10 minutes.
- **Research pipeline:** Refactored scattered Python/R work into a configurable Python–R–SQL pipeline for multi-asset training, inference, rolling validation, backtesting, and reproducible experiments.
- **Model validation:** Used LightGBM, XGBoost, MAVE, and VAE for 7/14/28-day prediction and feature representation; a stage-specific rolling out-of-sample result reached about 65% directional accuracy, not a universal performance claim.
- **Signal delivery:** Built standardized model-management and API/JSON layers for predictions, factor exposures, and strategy weights.

## 🔬 Project Experience

### **Hong Kong Jockey Club Odds and Betting Behavior Statistical Modeling**
*Project Initiator | Oct 2025 – Dec 2025*  
*CityU course project*

- Collected and cleaned historical race, odds, and betting-type data, then applied statistical inference and learning to place and place-Q scenarios.
- This was a small-scale CityU course project; results should not be interpreted as stable betting ability or live trading returns.

### **Experimental Study on Shear Strength of Unsaturated Soil over a Wide Suction Range and Its Prediction**
*Core Team Member | National Natural Science Foundation of China related project*
[📄 Journal Paper (Rock and Soil Mechanics)](https://doi.org/10.16285/j.rsm.2022.2005)

- Implemented high-accuracy fitting in **MATLAB** (above **98%**) and rewrote core functions in **C**, supporting 200k+ data points with about **300%** higher computational efficiency.
- Used **Python / Origin** for analysis and visualization, and contributed to two equipment-related patent outcomes.

### **Study on the Generation of Multi-rule Fractals**
*Outstanding Graduation Thesis*

- Built a complex-dynamical-system-driven multi-rule fractal model and implemented real-time interactive rendering.
- Used **Taichi / Python** for GPU acceleration, achieving about **100×** improvement over the original implementation.

### **Epidemiological Modeling of COVID-19**
*Mathematical modeling competition project | Mar 2022*

- Built an **SIERR-T** model incorporating media and rumor dynamics, with sentiment and rumor analysis on Weibo comments.
- Analyzed policy effects using [OxCGRT data](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker).

## 📚 Publications & Patents

- **[J.1]** NIU Geng, ZHU Xiao-feng, **LI Jun-xing**, LÜ Meng-yuan, AN Li-qi, CHEN Zi-han. (2022). [**Experimental study on shear strength of unsaturated soil over a wide suction range and its prediction**](https://doi.org/10.16285/j.rsm.2022.2005). *Rock and Soil Mechanics*, 44(12), 3349–3359. DOI: 10.16285/j.rsm.2022.2005. (IF=3.721, EI, CA, JST, CSCD, Peking University Core Journal)
- **[P.1]** NIU Geng, **LI Jun-xing**, ZHU Xiao-feng, TAN Yong-ming, MIAO Yu-song, ZHAO Shi-jun, WU Di. (2024). [**Triaxial Apparatus for Unsaturated Soil Based on Dialysis Method Suction Control**](https://patents.google.com/patent/CN117368002A). Chinese Patent, CN117368002A. Application No. CN202311298912.7, Application Date: 2023-10-09, Publication Date: 2024-01-09.
- **[P.2]** NIU Geng, KONG Liang, ZHU Xiao-feng, **LI Jun-xing**, AN Li-qi, LÜ Meng-yuan, CHEN Zi-han. (2022). [**Direct Shear Apparatus for Unsaturated Soil with Erosion Monitoring and Control System**](https://patents.google.com/patent/CN115452613A). Chinese Patent, publication CN115452613A; grant CN115452613B. Application No. CN202211220042.7, Application Date: 2022-10-08, Publication Date: 2022-12-09.

## 🏅 Honors & Awards

- 🥈 **Chinese Mathematics Competitions (CMC), National Second Prize** *(Jan 2023)*
- 🥈 **CUMCM Mathematical Contest in Modeling, Shandong Second Prize** *(Nov 2022)*
- 🥈 **Shandong Provincial Mathematics Competition, Shandong Second Prize** *(Nov 2022)*
- 🥉 **MathorCup Mathematical Modeling Challenge, National Third Prize** *(May 2022)*
- 🥈 **Shandong Provincial Physics Competition, Shandong Second Prize** *(Nov 2021)*

## 🛠 Skills

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-E38C00?style=flat-square&logo=mysql&logoColor=white)
![Polars](https://img.shields.io/badge/-Polars-CD792C?style=flat-square&logo=polars&logoColor=white)
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Parquet](https://img.shields.io/badge/-Apache%20Parquet-50ABF1?style=flat-square&logo=apache&logoColor=white)
![MATLAB](https://img.shields.io/badge/-MATLAB-FF4B00?style=flat-square&logo=mathworks&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Linux](https://img.shields.io/badge/-Linux-333333?style=flat-square&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/-CI%2FCD-2EA043?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Slurm](https://img.shields.io/badge/-Slurm-009BDE?style=flat-square&logoColor=white)
![Singularity](https://img.shields.io/badge/-Singularity-1D3557?style=flat-square&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

### Toolchain Highlights

- **Quantitative research:** Pandas, NumPy, Polars, DuckDB, LightGBM, XGBoost, MAVE, VAE, time-series cross-validation, walk-forward validation, backtesting.
- **Data infrastructure:** Apache Parquet, S3-compatible object storage, MySQL, Redis, JSON/API delivery, partitioned and incremental data pipelines.
- **Research engineering:** PyTorch, Hugging Face Transformers, MMSegmentation, PaddleSeg, MONAI, TorchGeo, nnU-Net, TotalSegmentator.
- **Systems and delivery:** Linux/Unix, Git/GitHub, Slurm, Singularity, Docker, GitHub Actions, YAML configuration, CLI workflows, logging, and experiment tracking.
- **AI-agent workflows:** Claude Code, Codex, Cursor, GitHub Copilot, Dify, MCP, and business-facing automation design.

## 🌏 Languages

- Mandarin Chinese *(Native)*
- English *(B2)*

## 🎯 Interests

🏞 Hiking · 🏋️‍♂️ Fitness · 🏍 Motorcycle · 📷 Photography · 💻 Coding

---
*Last Updated: Jul. 2026*
