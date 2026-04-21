---
title: Lev1s (Français)
permalink: /fr/
---

# _**LI Junxing**_

_李俊星_ _Jasen_

[العربية](/ar/) · [EN](/) · [Español](/es/) · [فارسی](/fa/) · **Français** · [हिन्दी](/hi/) · [日本語](/ja/) · [한국어](/ko/) · [Русский](/ru/) · [中文](/zh/)

> Bienvenue sur ce site ! Cette page contient plus de détails à mon sujet.\
> E-mail personnel : lev1s at duck dot com

## 🙋 Profil

Solides compétences en ingénierie de la recherche et en déploiement de systèmes, capable de piloter de façon autonome le pipeline complet allant de la définition du problème, la conception de la solution et la validation expérimentale jusqu'à la livraison engineering. En licence, j'ai développé des compétences solides en modélisation analytique, expression abstraite et travail d'équipe grâce aux concours de modélisation mathématique et à la formation en recherche. En master, j'ai mené des pratiques croisées en recherche quantitative sur les cryptomonnaies et en algorithmes de post-traitement pour la segmentation d'images, achevant la reconstruction du cadre de recherche quantitative, la mise en place d'un pipeline de prévision de séries temporelles, ainsi que l'adaptation de [RankSEG](https://github.com/rankseg/rankseg) aux workflows de segmentation courants, la reproduction d'expériences et le packaging d'environnements. Familier de la collaboration open-source, de la rédaction de documentation technique et de la communication bilingue, avec une expérience pratique des workflows d'agents, des chaînes d'outils automatisées et du déploiement cloud.

## 🎓 Formation

- **City University of Hong Kong** *(Sept. 2025 – Oct. 2026)*
  *Master of Science en Biostatistique*

- **Qingdao University of Technology** *(Sept. 2020 – Juin 2024)*
  *Licence de Sciences en Mathématiques et Mathématiques Appliquées*

## 💼 Expériences de Stage & Recherche

### **The Chinese University of Hong Kong (CUHK)**
*Assistant de Recherche à temps partiel | Fév. 2026 – Présent*
- Supervised by [Prof. Ben Dai](https://www.bendai.org/).
- Piloté l'ingénierie et le déploiement de l'algorithme de post-traitement de segmentation d'images [RankSEG](https://github.com/rankseg/rankseg), en charge du pipeline complet depuis la lecture du code source et la reproduction des expériences, l'adaptation aux frameworks de segmentation courants, l'intégration du post-traitement d'inférence, le développement des scripts d'évaluation jusqu'au packaging en environnement cluster, faisant évoluer l'algorithme d'un prototype de recherche vers une forme d'ingénierie reproductible et déployable.
- Avancé l'intégration et l'extension de [RankSEG](https://github.com/rankseg/rankseg) dans les workflows de segmentation sémantique courants ; participé à l'adaptation des frameworks mmsegmentation et PaddleSeg, et conçu un post-processing helper dans un fork de Transformers pour permettre aux tenseurs de probabilité en sortie de modèle d'être directement injectés dans un post-traitement guidé par Dice/IoU, soutenant l'optimisation des résultats de segmentation sans ré-entraînement.
- Participé à la reconstruction du pipeline de post-traitement d'inférence et d'évaluation, optimisant les workflows de prédiction autour des métriques Dice/IoU, en ajoutant la journalisation, des scripts d'évaluation et le suivi des résultats pour améliorer la comparabilité des expériences, l'efficacité du débogage et la stabilité de la reproduction.
- Mis en place des expériences reproductibles avec Singularity + Slurm sur le cluster HPC de CUHK, effectuant le packaging d'images, la gestion des dépendances, la soumission de tâches par templates et l'adaptation à des environnements multi-GPU, consolidant des commandes d'expériences dispersées en templates unifiés supportant des expériences en batch sur A100, V100 et RTX Pro 6000.
- Renforcé le pipeline de livraison du projet pour les utilisateurs de la communauté et les collaborateurs potentiels en ajoutant des guides de démarrage rapide, des tutoriels d'intégration, un README, des démos interactives et un playground, faisant progresser la démonstration cloud et le développement du pipeline CI/CD pour abaisser les barrières d'adoption et améliorer la visibilité externe du projet.

### **Zhejiang Mingce Asset Management Co., Ltd.**
*Stagiaire Architecture Quantitative (CityUHK Bios Coop) | Sept. 2025 – Avr. 2026*
*Trading Quantitatif de Cryptomonnaies & Développement de Stratégies*
- Réalisé des recherches sur les signaux et développé le cadre pour le trading journalier de cryptoactifs autour de BTC, ETH et des 40 actifs à liquidité suivants, en charge du pipeline complet de R&D allant du nettoyage des données on-chain, la construction de features, le prétraitement des facteurs, la modélisation prédictive, le backtesting de séries temporelles jusqu'à la génération de signaux.
- Réalisé une extraction active de facteurs et un renforcement de signaux à l'aide de modèles arborescents tels que Random Forest et XGBoost, améliorant la qualité des features d'entrée via des tests de stationnarité, des tests de corrélation et des stratégies de prétraitement par classification de facteurs, en explorant différentes méthodes de construction de la variable de réponse et les contributions des signaux transversaux.
- Piloté la reconstruction des scripts expérimentaux initiaux basés sur R Markdown en un framework de recherche modulaire Python-R-SQL, en concevant de zéro l'arborescence du code, les frontières de modules, les interfaces de fonctions, la nomenclature des variables, les structures de données et les mécanismes de configuration YAML, formant un pipeline de recherche quantitative et de backtesting réutilisable et extensible.
- Appliqué les méthodes MAVE et Autoencoder pour la réduction de dimension des features et l'apprentissage de représentations afin de traiter le bruit élevé et la colinéarité dans les séries temporelles financières, combiné à une validation croisée stricte des séries temporelles et une recherche d'hyperparamètres pour contrôler les risques de fuite d'information et améliorer la robustesse de l'évaluation des modèles.
- Réalisé une validation de prédiction directionnelle multi-période sur 7/14/28 jours en utilisant 8 ans de données historiques et une fenêtre de backtest glissante d'1 an, construisant un système d'évaluation à double voie (classification et prédiction continue) avec le signe du log return comme label directionnel principal, atteignant une précision directionnelle d'environ **65%**.
- Mis en place un pipeline de livraison de signaux de la recherche à la production, supportant l'entraînement parallèle multi-actifs, la prédiction et le backtesting, piloté par une configuration YAML unifiée, avec les résultats renvoyés via JSON/API et stockés en base SQL, soutenant l'affichage frontend et l'intégration au trading en direct.

## 🔬 Expériences de Projets

### **Modélisation Statistique des Cotes et Comportements de Paris du Hong Kong Jockey Club**
*Initiateur du Projet | Oct. 2025 – Déc. 2025*
*Projet de Cours CityU*
- Réalisé un scraping de données à grande échelle, un nettoyage et une analyse exploratoire des données historiques du HKJC, construisant un jeu de données analytiques structuré couvrant les résultats de courses, les cotes et les types de paris.
- Appliqué l'inférence statistique et les tests d'hypothèse pour analyser systématiquement les distributions des résultats de courses et les facteurs d'influence potentiels, vérifiant l'équilibre des échantillons et la faisabilité de la modélisation.
- Construit des modèles d'apprentissage statistique pour les scénarios de paris **place** et **place Q** à partir de données historiques, effectuant l'ingénierie des features, l'entraînement des modèles et l'évaluation des résultats.
- Atteint une haute précision prédictive sur les échantillons de l'hippodrome de Sha Tin et en validation à petite échelle, soutenant l'analyse de stratégies de paris et l'optimisation des modèles.

### **Étude Expérimentale sur la Résistance au Cisaillement des Sols Non Saturés**
*Membre clé | Subvention de la Fondation Nationale des Sciences Naturelles de Chine*
[📄 Article (Rock and Soil Mechanics)](https://doi.org/10.16285/j.rsm.2022.2005)
*Grant No.: 42307236, 12172187, 12072170*  
- Développement de **modèles MATLAB** haute précision (>**98% de précision**)
- Optimisation de **code C** pour 200k+ points de données → **accélération 3×**
- Production de visualisations en **Python / Origin**
- Co-auteur de **deux brevets nationaux**

### **Étude sur la Génération de Fractales Multi-règles**
*Thèse de Licence*
- Construction d'un modèle fractal accéléré GPU avec **Taichi**, atteignant une **accélération 100×**
- Rendu fractal en temps réel et interaction
- Identification d'améliorations sur les systèmes de génération de fractales existants

### **Modélisation Épidémiologique du COVID-19**
*MathorCup 2022*
- Proposition du **modèle $SIERR-T$** intégrant la **dynamique des médias & des rumeurs**
- **Analyse de sentiment NLP** sur **5M de commentaires Weibo**
- Application de méthodes d'apprentissage profond pour la détection des rumeurs et la prévision des tendances de propagation, avec de bonnes performances prédictives sur les jeux expérimentaux
- Analyse des effets des politiques via les [données OxCGRT](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker)

## 📚 Publications & Brevets

- **[J.1]** NIU Geng, ZHU Xiao-feng, **LI Jun-xing**, LÜ Meng-yuan, AN Li-qi, CHEN Zi-han. (2022). [**Experimental study on shear strength of unsaturated soil over a wide suction range and its prediction**](https://doi.org/10.16285/j.rsm.2022.2005). *Rock and Soil Mechanics*, No. 12, pp. 1-11. DOI: 10.16285/j.rsm.2022.2005. (IF=3.721, EI, CA, JST, CSCD, Peking University Core Journal)  
- **[P.1]** NIU Geng, **LI Jun-xing**, ZHU Xiao-feng, TAN Yong-ming, MIAO Yu-song, ZHAO Shi-jun, WU Di. (2024). [**Triaxial Apparatus for Unsaturated Soil Based on Dialysis Method Suction Control**](https://patents.google.com/patent/CN117368002A). Chinese Patent, Patent No. CN117368002A. Application No. CN202311298912.7, Application Date: 2023-10-09, Publication Date: 2024-01-09.  
- **[P.2]** NIU Geng, KONG Liang, ZHU Xiao-feng, **LI Jun-xing**, AN Li-qi, LÜ Meng-yuan, CHEN Zi-han. (2022). [**Direct Shear Apparatus for Unsaturated Soil with Erosion Monitoring and Control System**](https://patents.google.com/patent/CN115452613A). Chinese Patent, Patent No. CN115452613A. Application No. CN202211220042.7, Application Date: 2022-10-08, Publication Date: 2022-12-09.

## 🏅 Distinctions & Récompenses

- 🥈 **Compétition Chinoise de Mathématiques (CMC), Deuxième Prix National** *(janv. 2023)*
- 🥈 **Concours de Modélisation Mathématique CUMCM, Deuxième Prix du Shandong** *(nov. 2022)*
- 🥈 **Compétition Provinciale de Mathématiques du Shandong, Deuxième Prix du Shandong** *(nov. 2022)*
- 🥉 **Défi de Modélisation Mathématique MathorCup, Troisième Prix National** *(mai 2022)*
- 🥈 **Compétition Provinciale de Physique du Shandong, Deuxième Prix du Shandong** *(nov. 2021)*

## 🛠 Compétences

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

## 🌏 Langues

- Mandarin *(Langue maternelle)*
- Anglais *(B2 – Communication académique et professionnelle)*

## 🎯 Centres d'Intérêt

🏞 Randonnée · 🏋️‍♂️ Fitness · 🏍 Moto · 📷 Photographie · 💻 Programmation

---
*Dernière mise à jour : Avr. 2026*
