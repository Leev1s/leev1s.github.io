---
title: Lev1s (Español)
permalink: /es/
---

# _**LI Junxing**_

_李俊星_ _Jasen_

[العربية](/ar/) · [EN](/) · **Español** · [فارسی](/fa/) · [Français](/fr/) · [हिन्दी](/hi/) · [日本語](/ja/) · [한국어](/ko/) · [Русский](/ru/) · [中文](/zh/)

> ¡Bienvenido a este sitio! Esta página contiene más detalles sobre mí.\
> Correo personal: lev1s at duck dot com

## 🙋 Perfil

Sólidas capacidades de ingeniería en investigación y entrega de sistemas, capaz de impulsar de forma independiente el pipeline completo desde la definición del problema, el diseño de la solución y la validación experimental hasta la entrega de ingeniería. Durante los estudios de grado, desarrollé sólidas habilidades de modelado analítico, expresión abstracta y trabajo en equipo a través de concursos de modelado matemático y formación en investigación. Durante el máster, realicé prácticas interdisciplinarias en investigación cuantitativa de criptomonedas y algoritmos de post-procesamiento para segmentación de imágenes, completando la reconstrucción del framework de investigación cuantitativa, la configuración del pipeline de predicción de series temporales, y la adaptación de RankSeg a workflows de segmentación convencionales, reproducción de experimentos y empaquetado de entornos. Familiarizado con la colaboración open-source, la documentación técnica y la comunicación bilingüe, con experiencia práctica en workflows de agentes, cadenas de herramientas automatizadas y despliegue en la nube.

## 🎓 Educación

- **City University of Hong Kong** *(Sep 2025 – Oct 2026)*
  *Máster en Ciencias en Bioestadística*

- **Qingdao University of Technology** *(Sep 2020 – Jun 2024)*
  *Licenciatura en Ciencias en Matemáticas y Matemáticas Aplicadas*

## 💼 Experiencia en Prácticas & Investigación

### **The Chinese University of Hong Kong (CUHK)**
*Asistente de Investigación a tiempo parcial | Feb 2026 – Presente*
- Impulsé la ingeniería de investigación y el despliegue del algoritmo de post-procesamiento de segmentación de imágenes RankSEG, responsable del pipeline completo desde la lectura del código fuente y la reproducción de experimentos, la adaptación a frameworks de segmentación principales, la integración del post-procesamiento de inferencia, el desarrollo de scripts de evaluación hasta el empaquetado del entorno en clúster, haciendo avanzar el algoritmo de prototipo de investigación a una forma de ingeniería reproducible y desplegable.
- Avancé la integración y extensión de RankSEG en workflows de segmentación semántica convencionales; participé en la adaptación de los frameworks mmsegmentation y PaddleSeg, y diseñé un post-processing helper en un fork de Transformers para permitir que los tensores de probabilidad de salida del modelo se alimenten directamente en el post-procesamiento guiado por Dice/IoU, soportando la optimización de resultados de segmentación sin reentrenamiento.
- Participé en la reconstrucción del pipeline de post-procesamiento de inferencia y evaluación, optimizando los flujos de predicción en torno a las métricas Dice/IoU, añadiendo registros, scripts de evaluación y seguimiento de resultados para mejorar la comparabilidad experimental, la eficiencia de depuración y la estabilidad de reproducción.
- Configuré experimentos reproducibles usando Singularity + Slurm en el clúster HPC de CUHK, completando el empaquetado de imágenes, la gestión de dependencias, la presentación de trabajos por plantillas y la adaptación a entornos multi-GPU, consolidando comandos de experimentos dispersos en plantillas unificadas que soportan experimentos en lote en A100, V100 y RTX Pro 6000.
- Mejoré el pipeline de entrega del proyecto para usuarios de la comunidad y colaboradores potenciales añadiendo guías de inicio rápido, tutoriales de integración, README, demos interactivas y playground, avanzando en la demostración cloud y el desarrollo del pipeline CI/CD para reducir las barreras de incorporación y mejorar la visibilidad externa del proyecto.

### **Zhejiang Mingce Asset Management Co., Ltd.**
*Pasante de Arquitectura Cuantitativa (CityUHK Bios Coop) | Sep 2025 – Abr 2026*
*Trading Cuantitativo de Criptomonedas & Desarrollo de Estrategias*
- Realicé investigación de señales y desarrollo de framework para el trading diario de criptoactivos en torno a BTC, ETH y los siguientes 40 activos de mayor liquidez, responsable del pipeline completo de I+D desde la limpieza de datos on-chain, construcción de features, preprocesamiento de factores, modelado predictivo, backtesting de series temporales hasta la generación de señales.
- Realicé minería activa de factores y mejora de señales usando modelos arborescentes como Random Forest y XGBoost, mejorando la calidad de las features de entrada mediante pruebas de estacionariedad, pruebas de correlación y estrategias de preprocesamiento por clasificación de factores, explorando diferentes métodos de construcción de la variable de respuesta y las contribuciones de las señales transversales.
- Lideré la reconstrucción de los scripts experimentales iniciales basados en R Markdown en un framework de investigación modular Python-R-SQL, diseñando desde cero el directorio de código, los límites de módulos, las interfaces de funciones, la nomenclatura de variables, las estructuras de datos y los mecanismos de configuración YAML, formando un pipeline de investigación cuantitativa y backtesting reutilizable y extensible.
- Apliqué métodos MAVE y Autoencoder para la reducción de dimensionalidad de features y el aprendizaje de representaciones para abordar el alto ruido y la alta colinealidad en series temporales financieras, combinado con validación cruzada estricta de series temporales y búsqueda de hiperparámetros para controlar los riesgos de fuga de información y mejorar la robustez de la evaluación de modelos.
- Realicé validación de predicción direccional multi-período a 7/14/28 días usando 8 años de datos históricos y una ventana de backtest móvil de 1 año, construyendo un sistema de evaluación de doble vía (clasificación y predicción continua) usando el signo del log return como etiqueta direccional principal, alcanzando una precisión direccional aproximada del **65%**.
- Establecí un pipeline de entrega de señales desde la investigación hasta producción, soportando entrenamiento paralelo multi-activo, predicción y backtesting, impulsado por configuración YAML unificada, con resultados devueltos vía JSON/API y almacenados en base de datos SQL, soportando la visualización frontend posterior y la integración con trading en vivo.

## 🔬 Experiencia en Proyectos

### **Modelado Estadístico de Cuotas y Comportamiento de Apuestas del Hong Kong Jockey Club**
*Iniciador del Proyecto | Oct 2025 – Dic 2025*
*Proyecto de Curso CityU*
- Realicé scraping de datos a gran escala, limpieza y análisis exploratorio de datos históricos del HKJC, construyendo un conjunto de datos analíticos estructurado que cubre resultados de carreras, cuotas y tipos de apuestas.
- Apliqué inferencia estadística y pruebas de hipótesis para analizar sistemáticamente las distribuciones de resultados de carreras y los factores de influencia potenciales, verificando el equilibrio muestral y la viabilidad del modelado.
- Construí modelos de aprendizaje estadístico para escenarios de apuestas **place** y **place Q** usando datos históricos de carreras, completando ingeniería de features, entrenamiento de modelos y evaluación de resultados.
- Logré alta precisión predictiva en muestras del hipódromo de Sha Tin y en validación a pequeña escala, soportando el análisis de estrategias de apuestas y la optimización de modelos.

### **Estudio Experimental sobre la Resistencia al Corte de Suelos No Saturados**
*Miembro Principal | Subvención de la Fundación Nacional de Ciencias Naturales de China*
[📄 Artículo (Rock and Soil Mechanics)](https://doi.org/10.16285/j.rsm.2022.2005)
- Desarrollo de **modelos MATLAB** de alta precisión (>**98% de precisión**)
- Optimización de **código C** para más de 200k puntos de datos → **aceleración 3×**
- Producción de visualizaciones en **Python / Origin**
- Co-autor de **dos patentes nacionales**

### **Estudio sobre la Generación de Fractales Multi-regla**
*Tesis de Graduación*
- Construcción de un modelo fractal acelerado por GPU con **Taichi**, logrando una **aceleración 100×**
- Implementación de renderizado fractal en tiempo real e interacción
- Identificación de mejoras sobre los sistemas de generación de fractales existentes

### **Modelado Epidemiológico del COVID-19**
*MathorCup 2022*
- Propuesta del **modelo $SIER_1R_2-T$** integrando la **dinámica de medios y rumores**
- **Análisis de sentimientos NLP** sobre **5M de comentarios de Weibo**
- **Modelo de aprendizaje profundo** para predicción de datos de panel
- Análisis de efectos de políticas usando [datos OxCGRT](https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker)

## 📚 Publicaciones & Patentes

- **[J.1]** [Estudio experimental sobre la resistencia al corte de suelos no saturados...](https://doi.org/10.16285/j.rsm.2022.2005) – *Rock and Soil Mechanics* (IF=3.721)
- **[P.1]** [Aparato Triaxial para Suelo No Saturado Basado en el Método de Diálisis](https://patents.google.com/patent/CN117368002A) – Patente China CN117368002A
- **[P.2]** [Aparato de Corte Directo con Monitoreo de Erosión](https://patents.google.com/patent/CN115452613A) – Patente China CN115452613A

## 🏅 Honores & Premios

- 🥈 **Competencia China de Matemáticas (CMC)**
- 🥈 **Competencia Provincial de Matemáticas de Shandong**
- 🥈 **Concurso de Modelado Matemático CUMCM**
- 🥉 **Desafío de Modelado Matemático MathorCup**
- 🥈 **Competencia Provincial de Física de Shandong**
- 🎖️ **Beca de Actividades Culturales y Deportivas**

## 🛠 Habilidades

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

## 🌏 Idiomas

- Mandarín *(Nativo)*
- Inglés *(B2 – Comunicación académica y profesional)*

## 🎯 Intereses

🏞 Senderismo · 🏋️‍♂️ Fitness · 🏍 Motocicleta · 📷 Fotografía · 💻 Programación

---
*Última actualización: Abr. 2026*
