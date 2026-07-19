---
title: Lev1s（日本語）
permalink: /ja/
---

# _**LI Junxing**_

_李俊星_ _Jasen_

[العربية](/ar/) · [EN](/) · [Español](/es/) · [فارسی](/fa/) · [Français](/fr/) · [हिन्दी](/hi/) · **日本語** · [한국어](/ko/) · [Русский](/ru/) · [中文](/zh/)

> このサイトへようこそ！このページには私についての詳細が記載されています。\
> 個人メール：lev1s at foxmail dot com

## 🙋 プロフィール

数学・統計学を背景とする研究エンジニアとして、量的研究エンジニアリング、金融データ基盤、コンピュータビジョンの後処理、企業向け AI エージェントの導入に携わっています。問題定義と実験検証から、再現可能なデータ／モデルワークフロー、エンジニアリングへの実装、利用者向け文書化まで一貫して進められます。

現在は、量的データプラットフォームとシグナル研究、RankSEG の画像分割研究エンジニアリング、実用的な AI エージェントワークフロー設計を組み合わせています。テスト可能で再現性があり、実際の運用環境で役立つシステムを重視しています。

**現在の重点：**量的研究エンジニアリング、金融データ基盤、研究プラットフォーム、取引データサービス、AI ソリューション／エージェント自動化。

## 🎓 学歴

- **香港城市大学** *(2025年9月 – 2026年10月)*<br>
  *統計学 理学修士*

- **青島理工大学** *(2020年9月 – 2024年6月)*  
  *数学および応用数学 理学学士*  


## 💼 インターンシップ・研究経験

### **Sika China**
*AI エージェントインターン | 2026年4月 – 2026年7月*

- 反復性が高く経験に依存するワークフローを対象に、AI 製品支援、内部ソリューション、データ自動化、業務運用に携わりました。
- 曖昧な業務要件を構造化された入力、ルール、エージェント／スキル設計、MVP、フィードバックループ、受け入れ基準へと整理しました。
- 業務情報を適切な範囲に保ちながら、エージェントの社内展開、ユーザー支援、トレーニング、SOP 文書、再利用可能なワークフロー資産の整備を支援しました。
- データ処理、ナレッジ検索、レポート、プレゼンテーションの各ワークフロー向けに実用的な自動化を構築・調整し、見た目の品質、編集可能性、再利用性を両立させました。

### **香港中文大学（CUHK）**
*パートタイム研究アシスタント | 2026年2月 – 現在*  
- Supervised by [Prof. Ben Dai](https://www.bendai.org/).
- [RankSEG](https://github.com/rankseg/rankseg)画像分割後処理アルゴリズムの研究エンジニアリングとデプロイを推進し、ソースコード読解、実験再現、フレームワーク適応、推論統合、評価、クラスター環境のパッケージングを担当しました。
- RankSEG をセマンティックセグメンテーションのワークフローに適応させ、mmsegmentation、PaddleSeg、Hugging Face Transformers、SAM ファミリーの適応経路を扱いました。モデルのスコアテンソルを Dice/IoU 指向の後処理に利用できるインターフェースを設計し、再学習なしで適用できるようにしました。
- 再現可能な評価、ログ、結果追跡のワークフローを構築し、実験の比較可能性、デバッグ効率、再現安定性を高めました。
- CUHK HPC 上で Singularity + Slurm 環境をパッケージ化し、マルチ GPU 実験用の再利用可能なジョブテンプレートを整備しました。
- [Transformers PR #19](https://github.com/rankseg/rankseg/pull/19)、[SAM 統合 PR #20](https://github.com/rankseg/rankseg/pull/20)、[統合ドキュメント PR #22](https://github.com/rankseg/rankseg/pull/22)、および [MONAI PR #2](https://github.com/rankseg/MONAI/pull/2) のマージを通じて、RankSEG エコシステムの公開協業に貢献しました。

### **浙江明策資産管理有限公司**
*量的アーキテクチャインターン | 2025年9月 – 2026年4月*
*量的研究エンジニアリングとデジタル資産データ基盤*
- 約8年分の履歴と流動性上位40のデジタル資産を対象とする量的研究データプラットフォームを構築し、分足・日足 OHLCV、オンチェーン指標、派生ファクターを統合しました。
- 約1億7,000万件の分足市場レコード、3,000個の候補特徴量、約20GBの Parquet データを管理しました。Parquet + S3 互換オブジェクトストレージ + DuckDB/Polars を中心とする構成へ再設計し、メタデータ、タスク状態、最新シグナルには MySQL を使用しました。
- 資産、頻度、年、日付でデータをパーティション化し、増分収集、パーティション書き込み、検証、オブジェクトストレージへのバックアップを追加しました。代表的な研究クエリは1–3分から5–15秒に短縮され、日次更新とバックアップは10分以内に収めました。
- R Markdown と分散した Python/R スクリプトを、マルチアセット学習、推論、ローリング検証、バックテスト、再現可能な実験に対応する設定可能な Python–R–SQL 研究パイプラインへ再構築しました。
- LightGBM、XGBoost、MAVE、VAE を用いて7/14/28日方向予測と特徴表現を実施しました。直近のローリング・アウトオブサンプル検証では、ある段階の結果として方向精度約65%となりましたが、普遍的な性能を示すものではありません。
- 予測、ファクターエクスポージャー、戦略ウェイトを API/JSON インターフェースで下流システムへ返す、標準化されたシグナル提供・モデル管理層を構築しました。

## 🔬 プロジェクト経験

### **香港ジョッキークラブ オッズ・投票行動統計モデリング**
*プロジェクト発起人 | 2025年10月 – 2025年12月*  
*シティ大学香港 課程プロジェクト*  
- 過去のレース、オッズ、投票タイプのデータを整理・クリーニングし、構造化された分析データセットにまとめました。
- 統計的推論、仮説検定、統計学習をプレースおよびプレースQのシナリオに適用しました。
- 小規模なシティ大学の課程研究プロジェクトであり、結果は安定した投票能力やライブ運用の収益を示すものではありません。

### **非飽和土のせん断強度に関する実験的研究**
*コアチームメンバー | 国家自然科学基金関連プロジェクト*
[📄 学術論文（岩土力学）](https://doi.org/10.16285/j.rsm.2022.2005)  
- **MATLAB** でシミュレーションとフィッティングのアルゴリズムを実装し、モデルフィット精度 **98%超** を達成しました。
- **C** で主要なフィッティング関数を書き直し、20万点超のデータに対応しながら計算効率を約 **300%** 改善しました。
- **Python / Origin** で分析と可視化を行い、装置関連の2件の特許成果に貢献しました。

### **マルチルールフラクタル生成の研究**
*卒業論文*  
- **Taichi** を使用した GPU 加速フラクタルモデルを構築し、**100倍の高速化** を達成  
- フラクタルのリアルタイムレンダリングとインタラクションを実装  
- 既存のフラクタル生成システムに対する改善点を特定  

### **COVID-19 の疫学モデリング**
*MathorCup 2022*  
- **メディア・デマ動態** を統合した **$SIERR-T$ モデル** を提案  
- Weibo コメントに対して感情分析とデマ識別を行い、[OxCGRT データ](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker) を用いて政策効果を分析しました。


## 📚 論文・特許

- **[J.1]** NIU Geng, ZHU Xiao-feng, **LI Jun-xing**, LÜ Meng-yuan, AN Li-qi, CHEN Zi-han. (2022). [**Experimental study on shear strength of unsaturated soil over a wide suction range and its prediction**](https://doi.org/10.16285/j.rsm.2022.2005). *Rock and Soil Mechanics*, 44(12), 3349–3359. DOI: 10.16285/j.rsm.2022.2005. (IF=3.721, EI, CA, JST, CSCD, Peking University Core Journal)
- **[P.1]** NIU Geng, **LI Jun-xing**, ZHU Xiao-feng, TAN Yong-ming, MIAO Yu-song, ZHAO Shi-jun, WU Di. (2024). [**Triaxial Apparatus for Unsaturated Soil Based on Dialysis Method Suction Control**](https://patents.google.com/patent/CN117368002A). Chinese Patent, CN117368002A. Application No. CN202311298912.7, Application Date: 2023-10-09, Publication Date: 2024-01-09.
- **[P.2]** NIU Geng, KONG Liang, ZHU Xiao-feng, **LI Jun-xing**, AN Li-qi, LÜ Meng-yuan, CHEN Zi-han. (2022). [**Direct Shear Apparatus for Unsaturated Soil with Erosion Monitoring and Control System**](https://patents.google.com/patent/CN115452613A). Chinese Patent, publication CN115452613A; grant CN115452613B. Application No. CN202211220042.7, Application Date: 2022-10-08, Publication Date: 2022-12-09.


## 🏅 受賞歴

- 🥈 **全国大学生数学コンテスト（CMC）全国2等賞** *(2023年1月)*
- 🥈 **全国大学生数学モデリングコンテスト（CUMCM）山東省2等賞** *(2022年11月)*
- 🥈 **山東省大学生数学コンテスト山東省2等賞** *(2022年11月)*
- 🥉 **MathorCup 数学モデリングチャレンジ全国3等賞** *(2022年5月)*
- 🥈 **山東省大学生物理コンテスト山東省2等賞** *(2021年11月)*

## 🛠 スキル

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

### ツールチェーンの概要

- **量的研究：** Pandas、NumPy、Polars、DuckDB、LightGBM、XGBoost、MAVE、VAE、時系列クロスバリデーション、Walk-forward 検証、バックテスト。
- **データ基盤：** Apache Parquet、S3 互換オブジェクトストレージ、MySQL、Redis、JSON/API 連携、パーティション分割・増分データパイプライン。
- **研究工学：** PyTorch、Hugging Face Transformers、MMSegmentation、PaddleSeg、MONAI、TorchGeo、nnU-Net、TotalSegmentator。
- **システムと提供：** Linux/Unix、Git/GitHub、Slurm、Singularity、Docker、GitHub Actions、YAML 設定、CLI ワークフロー、ログ・実験追跡。
- **AI エージェント：** Claude Code、Codex、Cursor、GitHub Copilot、Dify、MCP、業務向け自動化設計。



## 🌏 言語能力

- 中国語（普通話）*（母語）*  
- 英語 *（IELTS 6.0 – 学術的な読解・専門的な文章によるコミュニケーション）*


## 🎯 趣味・関心

🏞 ハイキング · 🏋️‍♂️ フィットネス · 🏍 バイク · 📷 写真 · 💻 コーディング  

---
*最終更新：2026年7月*
