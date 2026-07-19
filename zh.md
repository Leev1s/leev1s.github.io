---
title: Lev1s（中文）
permalink: /zh/
---

# _**李俊星**_

_LI Junxing_ _Jasen_

[العربية](/ar/) · [EN](/) · [Español](/es/) · [فارسی](/fa/) · [Français](/fr/) · [हिन्दी](/hi/) · [日本語](/ja/) · [한국어](/ko/) · [Русский](/ru/) · **中文**

> 欢迎来到这个页面！这里包含更多关于我的信息。\
> 个人邮箱：lev1s at foxmail dot com

## 🙋 个人总结

具备数学与统计学背景的研究工程师，主要从事量化研究工程、金融数据基础设施、计算机视觉后处理和企业级 AI Agent 交付。我能够将问题从定义与实验验证推进到可复现的数据/模型工作流、工程交付和面向用户的文档。

当前的实践将量化数据平台与信号研究、RankSEG 图像分割研究工程，以及实用的 AI Agent 工作流设计结合起来。我重视可测试、可复现，并能在真实运行环境中发挥作用的系统。

**当前重点：**量化研究工程、金融数据基础设施、研究平台、交易数据服务，以及 AI 解决方案与 Agent 自动化。

## 🎓 教育经历

- **香港城市大学** *(2025年9月 – 2026年10月)*<br>
  *统计学理学硕士*

- **青岛理工大学** *(2020年9月 – 2024年6月)*  
  *数学与应用数学理学学士*  

## 💼 实习与科研经历

### **Sika China**
*AI Agent 实习生 | 2026年4月 – 2026年7月*

- 围绕重复性强、依赖经验的工作流，参与 AI 产品支持、内部解决方案、数据自动化和业务运营相关工作。
- 将较为宽泛的业务需求拆解为结构化输入、规则、Agent/Skill 设计、MVP、反馈闭环和验收标准。
- 支持 Agent 的内部推广、用户启用、培训、SOP 文档和可复用工作流资产建设，并在适当边界内处理业务信息。
- 针对数据处理、知识检索、报告和演示文稿流程构建与调整实用自动化方案，兼顾视觉质量、可编辑性与复用性。

### **香港中文大学（CUHK）**
*兼职研究助理 | 2026年2月 – 至今*  
- Supervised by [Prof. Ben Dai](https://www.bendai.org/).
- 围绕 [RankSEG](https://github.com/rankseg/rankseg) 图像分割后处理算法开展研究工程化与部署，覆盖源码阅读、实验复现、框架适配、推理集成、评估和集群环境封装。
- 推进 RankSEG 在语义分割工作流中的适配，涉及 mmsegmentation、PaddleSeg、Hugging Face Transformers 以及 SAM 系列模型路径；设计接口，使模型得分张量能够用于面向 Dice/IoU 的后处理，而无需重新训练。
- 构建可复现的评估、日志和结果追踪流程，提升实验可比性、排障效率和复现稳定性。
- 在 CUHK HPC 上封装 Singularity + Slurm 环境，并准备可复用的多 GPU 实验作业模板。
- 通过已合并的 [Transformers PR #19](https://github.com/rankseg/rankseg/pull/19)、[SAM 集成 PR #20](https://github.com/rankseg/rankseg/pull/20)、[集成文档 PR #22](https://github.com/rankseg/rankseg/pull/22) 以及 [MONAI PR #2](https://github.com/rankseg/MONAI/pull/2)，参与 RankSEG 生态的公开协作。

### **浙江明策资产管理有限公司**
*量化架构实习生 | 2025年9月 – 2026年4月*
*量化研究工程与数字资产数据基础设施*
- 搭建量化研究数据平台，覆盖约 8 年历史数据和流动性排名 Top 40 的数字资产，整合分钟级与日频 OHLCV 数据、链上指标和衍生因子。
- 管理约 1.7 亿条分钟级市场记录、3,000 个候选特征和约 20 GB Parquet 数据；将架构调整为 Parquet + S3 兼容对象存储 + DuckDB/Polars，并使用 MySQL 管理元数据、任务状态和当前信号。
- 按资产、频率、年份和日期进行分区，加入增量采集、分区写入、数据校验和对象存储备份；典型研究查询从 1–3 分钟缩短至 5–15 秒，日常更新与备份控制在 10 分钟内。
- 将 R Markdown 和分散的 Python/R 脚本重构为可配置的 Python–R–SQL 研究流水线，支持多资产训练、推理、滚动验证、回测和可复现实验。
- 使用 LightGBM、XGBoost、MAVE 和 VAE 开展 7/14/28 天方向预测与特征表示；近期滚动样本外验证中的某一阶段性结果约为 65% 方向准确率，不应解读为普遍适用的表现。
- 构建标准化的信号交付与模型管理层，通过 API/JSON 接口向下游系统返回预测结果、因子暴露和策略权重。

## 🔬 项目经历

### **香港赛马会赔率与投注行为统计建模**
*项目发起人 | 2025.10 -- 2025.12*  
*香港城市大学课程项目*  
- 将历史赛事、赔率和投注类型数据整理、清洗为结构化分析数据集。
- 使用统计推断、假设检验和统计学习方法分析位置与位置 Q 场景。
- 这是一个小规模的城市大学课程研究项目，结果不应被解读为稳定的投注能力或实盘收益。

### **宽广吸力范围非饱和土剪切强度试验研究及其预测**
*核心团队成员 | 国家自然科学基金相关项目*
[📄 论文（岩土力学）](https://doi.org/10.16285/j.rsm.2022.2005)  
- 参与非饱和土剪切强度试验研究与预测建模，在 **MATLAB** 中实现高精度仿真算法，模型拟合准确率超过 **98%**。  
- 在 **C** 中重写并优化数据拟合函数，支持超过 200,000 个数据点处理，核心计算效率提升约 **300%**。  
- 使用 **Origin / Python** 完成数据分析与可视化，为试验结果解释、模型验证与论文撰写提供计算支持。  
- 在仿真与试验分析过程中识别现有设备局限，参与形成两项专利成果，支持实验装置改进与测控能力提升。  

### **多规则分形生成研究**
*优秀毕业论文*  
- 系统梳理现有分形生成方法与规则体系，分析其在表达能力、控制机制与生成效率上的局限性。  
- 构建复杂动力系统驱动的多规则分形生成模型，为分形结构的组合生成与演化控制提供理论与实现基础。  
- 基于 **Taichi（Python）** 实现 GPU 加速计算，相较原始实现获得约 **100 倍**性能提升。  
- 实现分形图形的实时渲染与交互式展示，提升模型可解释性与后续研究可扩展性。  

### **基于时变微分方程动力学的 COVID-19 流行病学建模**
*MathorCup 2022*  
- 构建面向 COVID-19 传播过程的 **SIERR-T 动力学模型**，将媒体传播与谣言扩散机制纳入流行病学建模框架。  
- 对微博评论开展疫情期间的情感分析与谣言识别，并使用 [OxCGRT 数据](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker) 分析政策影响。

## 📚 论文与专利

- **[J.1]** NIU Geng, ZHU Xiao-feng, **LI Jun-xing**, LÜ Meng-yuan, AN Li-qi, CHEN Zi-han. (2022). [**Experimental study on shear strength of unsaturated soil over a wide suction range and its prediction**](https://doi.org/10.16285/j.rsm.2022.2005). *Rock and Soil Mechanics*, 44(12), 3349–3359. DOI: 10.16285/j.rsm.2022.2005. (IF=3.721, EI, CA, JST, CSCD, Peking University Core Journal)
- **[P.1]** NIU Geng, **LI Jun-xing**, ZHU Xiao-feng, TAN Yong-ming, MIAO Yu-song, ZHAO Shi-jun, WU Di. (2024). [**Triaxial Apparatus for Unsaturated Soil Based on Dialysis Method Suction Control**](https://patents.google.com/patent/CN117368002A). Chinese Patent, CN117368002A. Application No. CN202311298912.7, Application Date: 2023-10-09, Publication Date: 2024-01-09.
- **[P.2]** NIU Geng, KONG Liang, ZHU Xiao-feng, **LI Jun-xing**, AN Li-qi, LÜ Meng-yuan, CHEN Zi-han. (2022). [**Direct Shear Apparatus for Unsaturated Soil with Erosion Monitoring and Control System**](https://patents.google.com/patent/CN115452613A). Chinese Patent, publication CN115452613A; grant CN115452613B. Application No. CN202211220042.7, Application Date: 2022-10-08, Publication Date: 2022-12-09.

## 🏅 荣誉奖项

- 🥈 **中国大学生数学竞赛（CMC）全国二等奖** *(2023年1月)*
- 🥈 **全国大学生数学建模竞赛（CUMCM）山东赛区二等奖** *(2022年11月)*
- 🥈 **山东省大学生数学竞赛山东省二等奖** *(2022年11月)*
- 🥉 **MathorCup 数学建模挑战赛全国三等奖** *(2022年5月)*
- 🥈 **山东省大学生物理竞赛山东省二等奖** *(2021年11月)*

## 🛠 技能

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat-square&logo=r&logoColor=white)
![Polars](https://img.shields.io/badge/-Polars-CD792C?style=flat-square&logo=polars&logoColor=white)
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Parquet](https://img.shields.io/badge/-Apache%20Parquet-50ABF1?style=flat-square&logo=apache&logoColor=white)
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

### 工具链重点

- **量化研究：** Pandas、NumPy、Polars、DuckDB、LightGBM、XGBoost、MAVE、VAE、时间序列交叉验证、Walk-forward 验证和回测。
- **数据基础设施：** Apache Parquet、S3 兼容对象存储、MySQL、Redis、JSON/API 交付、分区和增量数据流水线。
- **研究工程：** PyTorch、Hugging Face Transformers、MMSegmentation、PaddleSeg、MONAI、TorchGeo、nnU-Net、TotalSegmentator。
- **系统与交付：** Linux/Unix、Git/GitHub、Slurm、Singularity、Docker、GitHub Actions、YAML 配置、CLI 工作流、日志和实验追踪。
- **AI Agent 工作流：** Claude Code、Codex、Cursor、GitHub Copilot、Dify、MCP，以及面向业务的自动化设计。

## 🌏 语言能力

- 中文普通话（母语）  
- 英语（IELTS 6.0，学术阅读与专业书面沟通）

## 🎯 兴趣爱好

🏞 徒步 · 🏋️‍♂️ 健身 · 🏍 摩托车 · 📷 摄影 · 💻 编程  

---
*最后更新：2026年7月*
