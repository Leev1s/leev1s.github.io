---
title: Lev1s（中文）
permalink: /zh/
---

# _**李俊星**_

_LI Junxing_ _Jasen_

[العربية](/ar/) · [EN](/) · [Español](/es/) · [فارسی](/fa/) · [Français](/fr/) · [हिन्दी](/hi/) · [日本語](/ja/) · [한국어](/ko/) · [Русский](/ru/) · **中文**

> 欢迎来到这个页面！这里包含更多关于我的信息。\
> 个人邮箱：lev1s at duck dot com

## 🙋 个人总结

具备较强的研究工程化与系统落地能力，能够独立推进从问题定义、方案设计、实验验证到工程交付的完整链路。本科阶段通过数学建模竞赛与科研训练积累了扎实的建模分析、抽象表达与团队协作能力；硕士阶段围绕加密货币量化研究与图像分割后处理算法开展跨方向实践，分别完成量化研究框架重构、时序预测 pipeline 搭建，以及 [RankSEG](https://github.com/rankseg/rankseg) 在主流分割流程中的适配、实验复现与环境封装。熟悉开源协作、技术文档编写与双语沟通，具备 Agent 工作流、自动化工具链与云端部署相关实践经验。

## 🎓 教育经历

- **香港城市大学** *(2025年9月 – 2026年10月)*  
  *生物统计学理学硕士*  

- **青岛理工大学** *(2020年9月 – 2024年6月)*  
  *数学与应用数学理学学士*  

## 💼 实习与科研经历

### **香港中文大学（CUHK）**
*兼职研究助理 | 2026年2月 – 至今*  
- Supervised by [Prof. Ben Dai](https://www.bendai.org/).
- 围绕 [RankSEG](https://github.com/rankseg/rankseg) 图像分割后处理算法开展研究工程化落地，负责从源码阅读与实验复现、主流分割框架适配、推理后处理接入、评估脚本开发到集群环境封装的完整链路，推动算法从研究原型走向可复现、可部署的工程形态。  
- 基于主流 semantic segmentation 流程推进 [RankSEG](https://github.com/rankseg/rankseg) 融合与扩展，参与 mmsegmentation、PaddleSeg 等框架适配，并在 Transformers fork 中设计 post-processing helper，使模型输出概率张量可直接接入 Dice/IoU 导向的后处理流程，支持在不重新训练模型的前提下优化分割预测结果。  
- 参与推理后处理与评估链路重构，围绕 Dice / IoU 指标优化预测流程，补充日志记录、评估脚本与结果追踪能力，提升实验可比性、排障效率与复现稳定性。  
- 在 CUHK HPC 集群环境中搭建基于 Singularity + Slurm 的可复现实验方案，完成镜像打包、依赖管理、任务模板化提交与多 GPU 环境适配，将原本分散的实验命令整理为统一模板，支持在 A100、V100、RTX Pro 6000 等环境下进行批量实验与评估。  
- 面向社区用户与潜在合作者完善项目交付链路，补充 quickstart、接入教程、README、交互式 demo 与 playground，推进云端演示与 CI/CD 流程建设，降低新用户上手门槛并提升项目外部展示效率。

### **浙江明策资产管理有限公司**
*量化架构实习生（CityUHK Bios Coop）| 2025.9 -- 2026.4*  
*加密货币量化交易与策略开发*  
- 面向加密资产日频交易场景，围绕 BTC、ETH 及后续流动性 Top40 币种开展信号研究与框架搭建，负责从链上数据清洗、特征构建、因子预处理、建模预测、时间序列回测到信号生成的全流程研发。  
- 基于 Random Forest、XGBoost 等树模型开展主动因子挖掘与信号增强，结合平稳性检验、相关性检验及因子分类型预处理策略提升输入特征质量，并探索不同响应变量构造方式与横截面信号对主信号的补充效果。  
- 主导将早期基于 R Markdown 的试验性脚本重构为模块化 Python-R-SQL 研究框架，从 0 到 1 设计代码目录、模块边界、函数入口、变量命名、数据结构及 YAML 配置机制，形成可复用、可扩展的量化研究与回测 pipeline。  
- 针对金融时序高噪声、高共线性问题，应用 MAVE、Autoencoder 等方法进行特征降维与有效表示学习，并结合严格的时间序列交叉验证与超参数搜索流程控制信息泄露风险，提升模型评估的稳健性与可信度。  
- 基于 8 年历史数据、最近 1 年滚动回测窗口开展 7/14/28 天多周期方向预测验证，以 log return 符号为核心方向标签构建分类与连续预测双路径评估体系，方向预测准确率达到约 **65%**。  
- 打通研究到生产的信号交付链路，支持多币种并行训练、预测与回测，统一通过 YAML 配置驱动生产环境读取参数并生成交易信号，结果以 JSON/API 形式回传并入 SQL 库，支撑后续前端展示与实盘侧衔接。

## 🔬 项目经历

### **香港赛马会赔率与投注行为统计建模**
*项目发起人 | 2025.10 -- 2025.12*  
*香港城市大学课程项目*  
- 面向香港赛马会历史赛事数据，完成大规模数据抓取、清洗与探索性分析，构建覆盖赛事结果、赔率与投注类型的结构化分析数据集。  
- 基于统计推断与假设检验方法，对赛事结果分布与潜在影响因素进行系统分析，验证赛事样本的平衡性与建模可行性。  
- 基于历史赛事数据，围绕位置与位置Q投注场景构建统计学习模型，完成特征设计、模型训练与结果评估。  
- 在沙田马场相关样本与小规模验证中取得较高预测命中率，支持后续投注策略分析与模型优化。  

### **宽广吸力范围非饱和土剪切强度试验研究及其预测**
*核心团队成员 | 国家自然科学基金资助（资助号：42307236，12172187，12072170）*  
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
- 基于大规模微博评论数据开展疫情期间情感分析，提取舆情变化特征并用于辅助刻画传播行为与公众反应。  
- 结合深度学习方法开展谣言识别与传播趋势预测，在实验数据集上取得较高预测准确率。  
- 结合 [OxCGRT 数据](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker) 分析政府干预措施对疫情传播的影响，并提出针对性建模结论与策略建议。  

## 📚 论文与专利

- **[J.1]** NIU Geng, ZHU Xiao-feng, **LI Jun-xing**, LÜ Meng-yuan, AN Li-qi, CHEN Zi-han. (2022). [**Experimental study on shear strength of unsaturated soil over a wide suction range and its prediction**](https://doi.org/10.16285/j.rsm.2022.2005). *Rock and Soil Mechanics*, No. 12, pp. 1-11. DOI: 10.16285/j.rsm.2022.2005. (IF=3.721, EI, CA, JST, CSCD, Peking University Core Journal)  
- **[P.1]** NIU Geng, **LI Jun-xing**, ZHU Xiao-feng, TAN Yong-ming, MIAO Yu-song, ZHAO Shi-jun, WU Di. (2024). [**Triaxial Apparatus for Unsaturated Soil Based on Dialysis Method Suction Control**](https://patents.google.com/patent/CN117368002A). Chinese Patent, Patent No. CN117368002A. Application No. CN202311298912.7, Application Date: 2023-10-09, Publication Date: 2024-01-09.  
- **[P.2]** NIU Geng, KONG Liang, ZHU Xiao-feng, **LI Jun-xing**, AN Li-qi, LÜ Meng-yuan, CHEN Zi-han. (2022). [**Direct Shear Apparatus for Unsaturated Soil with Erosion Monitoring and Control System**](https://patents.google.com/patent/CN115452613A). Chinese Patent, Patent No. CN115452613A. Application No. CN202211220042.7, Application Date: 2022-10-08, Publication Date: 2022-12-09.

## 🏅 荣誉奖项

- 🥈 **中国大学生数学竞赛（CMC）**
- 🥈 **山东省大学生数学竞赛**
- 🥈 **全国大学生数学建模竞赛（CUMCM）**
- 🥉 **MathorCup 数学建模挑战赛**
- 🥈 **山东省大学生物理竞赛**

## 🛠 技能

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

## 🌏 语言能力

- 中文普通话（母语）  
- 英语（B2，学术与职场沟通）  

## 🎯 兴趣爱好

🏞 徒步 · 🏋️‍♂️ 健身 · 🏍 摩托车 · 📷 摄影 · 💻 编程  

---
*最后更新：2026年4月*
