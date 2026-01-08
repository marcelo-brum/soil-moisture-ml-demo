ENGLISH VERSION

# Soil Moisture Prediction Using Machine Learning and Satellite Data

## Overview
This repository presents a **demonstration case study** on basin-scale soil moisture prediction using **machine learning techniques** and the integration of **environmental and remote sensing data**.

The project is inspired by my PhD research in Agricultural Engineering, focused on applying data science to support water resources management and decision-making in agriculture.

> **Scientific integrity notice**  
> To preserve the originality of a manuscript currently under peer review, this repository contains only a **demonstration version** of the workflow. The full dataset and official scientific results are not disclosed here.

---

## Problem
Soil moisture estimation at large spatial scales is constrained by:
- limited density of in situ sensors;
- uncertainties in satellite-based products;
- strong spatial and temporal soil variability.

These limitations directly affect decisions related to:
- irrigation management;
- drought monitoring;
- climate risk assessment.

---

## Objective
To develop a **data science pipeline** that integrates multiple data sources to improve surface soil moisture prediction, with a strong focus on practical applications in agribusiness and environmental management.

---

## Data acquisition and processing
The datasets used in this project were obtained through an **automated data pipeline**, involving:

- **Google Earth Engine (GEE)** for:
  - remote sensing data extraction;
  - spatial and temporal processing;
  - generation of environmental time series;

- **Python (Google Colab)** for:
  - automated data collection;
  - dataset organization;
  - export to modeling environments;

- **R** for:
  - exploratory data analysis;
  - statistical modeling and machine learning;
  - performance evaluation and result visualization.

---

## Data sources (demonstration version)
The main data sources used in the workflow include:

- Satellite soil moisture products (e.g., **SMAP**);
- Meteorological variables (e.g., **ERA5-Land**);
- Soil physical attributes (texture, bulk density);
- Land use and land cover data (e.g., **MODIS**, **Sentinel**).

> In this public version, **open datasets, subsets, or simulated samples** are used for demonstration purposes only.

---

## Methodology
- Geospatial data preprocessing and integration  
- Feature engineering  
- Exploratory data analysis  
- Predictive modeling using:
  - Random Forest  
  - XGBoost  
- Model performance evaluation (RMSE, R²)  
- Spatial mapping of predictions in GIS environments  

---

## Results (demonstration)
The results presented in this repository are **illustrative** and show that integrating multiple data sources through machine learning:

- reduces prediction uncertainty;
- improves the spatial representation of soil moisture;
- enhances its potential for operational use in decision-support systems.

---

## Applications
- Irrigation planning  
- Water stress monitoring  
- Climate risk management  
- Technical support for agricultural consulting  
- Watershed-scale hydrological studies  

---

## Data availability
The datasets used in this study are **not shared** in this repository due to:

- preservation of the originality of a manuscript currently under peer review;
- compliance with institutional research policies;
- protection of sensitive field data.

However, all **public data sources** employed in this project are described above, enabling the replication of the workflow with equivalent datasets.

---

## Author
**Marcelo Lovato Brum**  

VERSÃO EM PORTUGUÊS-BR

# Predição da Umidade do Solo com Machine Learning e Dados de Satélite

## Visão geral
Este repositório apresenta um **estudo de caso demonstrativo** sobre a predição da umidade do solo em escala de bacia hidrográfica utilizando técnicas de **machine learning** e integração de **dados ambientais e de sensoriamento remoto**.

O projeto é inspirado em minha pesquisa de doutorado em Engenharia Agrícola, focada na aplicação de ciência de dados para apoiar a gestão de recursos hídricos e a tomada de decisão no setor agrícola.

> **Nota de integridade científica**  
> Para preservar a originalidade de um manuscrito atualmente em avaliação por pares, este repositório contém apenas uma **versão demonstrativa** do fluxo de trabalho. Os dados completos e os resultados científicos oficiais não são divulgados aqui.

---

## Problema
A estimativa da umidade do solo em escala espacial ampla é limitada por:
- baixa densidade de sensores in situ;
- incertezas associadas a produtos de satélite;
- alta variabilidade espacial e temporal do solo.

Essas limitações impactam diretamente decisões relacionadas a:
- manejo da irrigação;
- monitoramento de secas;
- avaliação de risco climático.

---

## Objetivo
Desenvolver um **pipeline de ciência de dados** capaz de integrar múltiplas fontes de informação para melhorar a predição da umidade do solo superficial, com foco em aplicações práticas no agronegócio e na gestão ambiental.

---

## Aquisição e processamento dos dados
Os dados utilizados neste projeto foram obtidos por meio de um **pipeline automatizado**, envolvendo:

- **Google Earth Engine (GEE)** para:
  - extração de produtos de sensoriamento remoto;
  - processamento espacial e temporal;
  - geração de séries temporais ambientais;

- **Python (Google Colab)** para:
  - automação da coleta de dados;
  - organização dos conjuntos de dados;
  - exportação para ambientes de modelagem;

- **R** para:
  - análise exploratória;
  - modelagem estatística e machine learning;
  - avaliação de desempenho e visualização dos resultados.

---

## Fontes de dados (versão demonstrativa)
As principais fontes de dados utilizadas no fluxo de trabalho incluem:

- Produtos de umidade do solo por satélite (ex.: **SMAP**);
- Variáveis meteorológicas (ex.: **ERA5-Land**);
- Atributos físicos do solo (textura, densidade aparente);
- Uso e cobertura da terra (ex.: **MODIS**, **Sentinel**).

> Nesta versão pública do projeto, são utilizados **dados públicos, subconjuntos ou amostras simuladas**, apenas para fins demonstrativos.

---

## Metodologia
- Pré-processamento e integração de dados geoespaciais  
- Engenharia de atributos  
- Análise exploratória dos dados  
- Modelagem preditiva com:
  - Random Forest  
  - XGBoost  
- Avaliação de desempenho (RMSE, R²)  
- Geração de mapas de predição em ambiente SIG  

---

## Resultados (demonstração)
Os resultados apresentados neste repositório têm caráter **ilustrativo** e indicam que a integração de múltiplas fontes de dados por meio de machine learning:

- reduz a incerteza das estimativas;
- melhora a representação espacial da umidade do solo;
- amplia o potencial de uso operacional em sistemas de suporte à decisão.

---

## Aplicações
- Planejamento da irrigação  
- Monitoramento de estresse hídrico  
- Gestão de risco climático  
- Apoio técnico para consultorias agrícolas  
- Estudos hidrológicos em bacias hidrográficas  

---

## Disponibilidade dos dados
Os conjuntos de dados utilizados neste estudo **não são disponibilizados** neste repositório por motivos de:

- preservação da originalidade de manuscrito científico em avaliação;
- conformidade com boas práticas de pesquisa e políticas institucionais;
- proteção de dados sensíveis de campo.

No entanto, todas as **fontes públicas de dados** utilizadas são descritas acima, permitindo a reprodução do fluxo de trabalho com conjuntos de dados equivalentes.

---

## Autor
**Marcelo Lovato Brum**  
Doutorando em Engenharia Agrícola  
Áreas de atuação: Ciência de Dados, Geoprocessamento, Machine Learning aplicado ao Agronegócio e Recursos Hídricos

PhD candidate in Agricultural Engineering  
Focus areas: Data Science, Geospatial Analytics, Machine Learning for AgTech and Water Resources
