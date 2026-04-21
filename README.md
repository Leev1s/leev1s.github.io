# _**LI Junxing**_

_李俊星_ _Jasen_

[العربية](/ar/) · **EN** · [Español](/es/) · [فارسی](/fa/) · [Français](/fr/) · [हिन्दी](/hi/) · [日本語](/ja/) · [한국어](/ko/) · [Русский](/ru/) · [中文](/zh/)

> Welcome to this site! This page contains more details about me.\
> Personal Email: lev1s at duck dot com

## 🙋 Profile

Strong research engineering and system delivery capabilities, able to independently drive the complete pipeline from problem definition, solution design, experimental validation to engineering delivery. During undergraduate studies, built solid modeling, analytical, and teamwork skills through mathematical modeling competitions and research training. During graduate studies, conducted cross-domain practice in cryptocurrency quantitative research and image segmentation post-processing, completing quantitative research framework reconstruction, time-series forecasting pipeline setup, and [RankSEG](https://github.com/rankseg/rankseg) adaptation, experiment reproduction, and environment packaging within mainstream segmentation workflows. Familiar with open-source collaboration, technical documentation and bilingual communication, with practical experience in Agent workflows, automated toolchains and cloud deployment.

## 🎓 Education

- **City University of Hong Kong** *(Sep 2025 – Oct 2026)*  
  *Master of Science in Biostatistics*  

- **Qingdao University of Technology** *(Sep 2020 – Jun 2024)*  
  *Bachelor of Science in Mathematics and Applied Mathematics*  


## 💼 Internship & Research Experience  

### **The Chinese University of Hong Kong (CUHK)**  
*Part-time Research Assistant | Feb 2026 – Present*  
- Supervised by [Prof. Ben Dai](https://www.bendai.org/).
- Drove research engineering and deployment of the [RankSEG](https://github.com/rankseg/rankseg) image segmentation post-processing algorithm, responsible for the full pipeline from source code reading and experiment reproduction, mainstream segmentation framework adaptation, inference post-processing integration, and evaluation script development to cluster environment packaging, advancing the algorithm from research prototype to reproducible, deployable engineering form.  
- Advanced [RankSEG](https://github.com/rankseg/rankseg) integration and extension within mainstream semantic segmentation workflows; participated in mmsegmentation and PaddleSeg framework adaptation, and designed a post-processing helper in a Transformers fork to enable model output probability tensors to be directly fed into Dice/IoU-guided post-processing, supporting optimization of segmentation prediction results without retraining.  
- Participated in inference post-processing and evaluation pipeline reconstruction, optimizing prediction workflows around Dice/IoU metrics, supplementing logging, evaluation scripts and result tracking to improve experimental comparability, debugging efficiency and reproduction stability.  
- Set up reproducible experiments using Singularity + Slurm on the CUHK HPC cluster, completing image packaging, dependency management, job template submission and multi-GPU environment adaptation, consolidating scattered experiment commands into unified templates supporting batch experiments on A100, V100, and RTX Pro 6000.  
- Enhanced project delivery pipeline for community users and potential collaborators by supplementing quickstart guides, integration tutorials, README, interactive demos and playground, advancing cloud demonstration and CI/CD pipeline development to lower onboarding barriers and improve external project visibility.

### **Zhejiang Mingce Asset Management Co., Ltd.**  
*Quantitative Architecture Intern (CityUHK Bios Coop) | Sep 2025 – Apr 2026*  
*Cryptocurrency Quantitative Trading & Strategy Development*  
- Conducted signal research and framework development for daily-frequency cryptocurrency trading around BTC, ETH, and subsequent liquidity Top40 assets, responsible for the full R&D pipeline from on-chain data cleaning, feature construction, factor preprocessing, predictive modeling, time-series backtesting to signal generation.  
- Performed active factor mining and signal enhancement using tree models including Random Forest and XGBoost, improving input feature quality through stationarity tests, correlation tests and factor classification preprocessing strategies, exploring different response variable construction methods and cross-sectional signal contributions.  
- Led the reconstruction of early R Markdown-based experimental scripts into a modular Python-R-SQL research framework, designing from scratch the code directory, module boundaries, function interfaces, variable naming, data structures and YAML configuration mechanisms, forming a reusable and extensible quantitative research and backtesting pipeline.  
- Applied MAVE and Autoencoder methods for feature dimensionality reduction and representation learning to address high-noise and high-collinearity in financial time series, combined with strict time-series cross-validation and hyperparameter search to control information leakage risks and improve model evaluation robustness.  
- Conducted 7/14/28-day multi-period directional prediction validation using 8 years of historical data and a 1-year rolling backtest window, building dual classification and continuous prediction evaluation paths using log return sign as the core directional label, achieving approximately **65% directional accuracy**.  
- Established a signal delivery pipeline from research to production, supporting multi-asset parallel training, prediction and backtesting, driven by unified YAML configuration, with results returned via JSON/API and stored in SQL database, supporting subsequent frontend display and live trading integration.

## 🔬 Project Experience  

### **Hong Kong Jockey Club Odds and Betting Behavior Statistical Modeling**  
*Project Initiator | Oct 2025 – Dec 2025*  
*CityU Course Project*  
- Conducted large-scale data scraping, cleaning and exploratory analysis of HKJC historical race data, constructing a structured analytical dataset covering race results, odds and betting types.  
- Applied statistical inference and hypothesis testing to systematically analyze race result distributions and potential influencing factors, verifying sample balance and modeling feasibility.  
- Built statistical learning models for **place** and **place Q** betting scenarios using historical race data, completing feature engineering, model training and result evaluation.  
- Achieved high predictive accuracy in Sha Tin racecourse samples and small-scale validation, supporting subsequent betting strategy analysis and model optimization.  

### **Experimental Study on Shear Strength of Unsaturated Soil over a Wide Suction Range and Its Prediction**  
*Core Team Member | National Natural Science Foundation of China Grant*  
*Grant No.: 42307236, 12172187, 12072170*  
[📄 Journal Paper (Rock and Soil Mechanics)](https://doi.org/10.16285/j.rsm.2022.2005)  
- Participated in experimental study and predictive modeling of unsaturated soil shear strength; implemented high-accuracy simulation algorithms in **MATLAB** with model fit accuracy above **98%**.  
- Rewrote and optimized data-fitting functions in **C**, supporting 200k+ data points and improving core computational efficiency by about **300%**.  
- Performed data analysis and visualization using **Python / Origin**, supporting result interpretation, model validation, and paper writing.  
- Identified equipment limitations during simulation and experimental analysis, contributing to two patent outcomes for apparatus improvement and measurement-control enhancement.  

### **Study on the Generation of Multi-rule Fractals**  
*Outstanding Graduation Thesis*  
- Conducted a systematic review of existing fractal generation methods and rule systems, analyzing limitations in expressive capacity, control mechanisms, and generation efficiency.  
- Constructed a multi-rule fractal generation model driven by complex dynamical systems, providing a theoretical and implementation basis for compositional generation and evolutionary control.  
- Implemented GPU-accelerated computation based on **Taichi (Python)**, achieving about **100×** performance improvement over the original implementation.  
- Implemented real-time fractal rendering and interactive visualization, improving model interpretability and extensibility for follow-up research.  

### **Epidemiological Modeling of COVID-19**  
*MathorCup 2022*  
- Proposed **SIERR-T model** integrating **media & rumor dynamics**  
- **NLP sentiment analysis** on **5M Weibo comments**  
- Applied deep learning methods for rumor detection and trend forecasting, achieving strong predictive performance on experimental datasets.  
- Analyzed policy effects using [OxCGRT Data](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker)  


## 📚 Publications & Patents  

- **[J.1]** NIU Geng, ZHU Xiao-feng, **LI Jun-xing**, LÜ Meng-yuan, AN Li-qi, CHEN Zi-han. (2022). [**Experimental study on shear strength of unsaturated soil over a wide suction range and its prediction**](https://doi.org/10.16285/j.rsm.2022.2005). *Rock and Soil Mechanics*, No. 12, pp. 1-11. DOI: 10.16285/j.rsm.2022.2005. (IF=3.721, EI, CA, JST, CSCD, Peking University Core Journal)  
- **[P.1]** NIU Geng, **LI Jun-xing**, ZHU Xiao-feng, TAN Yong-ming, MIAO Yu-song, ZHAO Shi-jun, WU Di. (2024). [**Triaxial Apparatus for Unsaturated Soil Based on Dialysis Method Suction Control**](https://patents.google.com/patent/CN117368002A). Chinese Patent, Patent No. CN117368002A. Application No. CN202311298912.7, Application Date: 2023-10-09, Publication Date: 2024-01-09.  
- **[P.2]** NIU Geng, KONG Liang, ZHU Xiao-feng, **LI Jun-xing**, AN Li-qi, LÜ Meng-yuan, CHEN Zi-han. (2022). [**Direct Shear Apparatus for Unsaturated Soil with Erosion Monitoring and Control System**](https://patents.google.com/patent/CN115452613A). Chinese Patent, Patent No. CN115452613A. Application No. CN202211220042.7, Application Date: 2022-10-08, Publication Date: 2022-12-09.


## 🏅 Honors & Awards  

- 🥈 **Chinese Mathematics Competitions (CMC), National Second Prize** *(Jan 2023)*
- 🥈 **CUMCM Mathematical Contest in Modeling, Shandong Second Prize** *(Nov 2022)*
- 🥈 **Shandong Provincial Mathematics Competition, Shandong Second Prize** *(Nov 2022)*
- 🥉 **MathorCup Mathematical Modeling Challenge, National Third Prize** *(May 2022)*
- 🥈 **Shandong Provincial Physics Competition, Shandong Second Prize** *(Nov 2021)*



## 🛠 Skills  

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat-square&logo=r&logoColor=white)
![MATLAB](https://img.shields.io/badge/-MATLAB-FF4B00?style=flat-square&logo=mathworks&logoColor=white)
![LaTeX](https://img.shields.io/badge/-LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-E38C00?style=flat-square&logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-333333?style=flat-square&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/-CI%2FCD-2EA043?style=flat-square&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Slurm](https://img.shields.io/badge/-Slurm-009BDE?style=flat-square&logoColor=white)
![Singularity](https://img.shields.io/badge/-Singularity-1D3557?style=flat-square&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)




### Toolchain Highlights
- **Python stack**: Python (Keras / TensorFlow / PyTorch), R, SQL, MATLAB, C, Shell
- **Systems**: Linux/Unix (4 years), Git, MySQL, Redis, Slurm, Singularity/Docker, GitHub CI/CD
- **Productivity & Agents**: Jupyter Notebook, VS Code, Claude Code, Codex, Dify, Cloudflare, LaTeX, Office

## 🌏 Languages

- Mandarin Chinese *(Native)*  
- English *(B2 – Academic & Professional Communication)*  


## 🎯 Interests  

🏞 Hiking · 🏋️‍♂️ Fitness · 🏍 Motorcycle · 📷 Photography · 💻 Coding  

---
*Last Updated: Apr. 2026*
