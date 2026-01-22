# Socio-Economic Indicators & Climate Adaptation Framework - Pernambuco (Brazil)
### Análise de Indicadores Socioeconômicos para o Plano Estadual de Adaptação às Mudanças Climáticas

---

## 🌎 Overview | Visão Geral

**[EN]** This repository contains the analytical framework and datasets developed to support the **Pernambuco State Climate Change Adaptation Plan**. The project integrates data science with public policy requirements, processing raw indicators from SEPLAG-PE and IBGE to assess the adaptive capacity of Pernambuco's 12 Development Regions (RDs).

**[PT]** Este repositório contém o framework analítico e as bases de dados desenvolvidas para subsidiar o **Plano Estadual de Adaptação às Mudanças Climáticas de Pernambuco**. O projeto integra técnicas de ciência de dados com demandas de políticas públicas, processando indicadores brutos da SEPLAG-PE e do IBGE para avaliar a capacidade adaptativa das 12 Regiões de Desenvolvimento (RDs) de Pernambuco.

---

## 👥 Authors | Autores

* **Jean Firmino Cardoso** – Data Analysis & Script Development (MSc Candidate, UFPE).
* **Antonio Celso Dantas Antonino** – Advisor & Project Supervision (UFPE).

---

## 📂 File Guide | Guia de Arquivos

Como este repositório utiliza uma estrutura plana, utilize a tabela abaixo para localizar os componentes do projeto:

| Categoria | Arquivos Principais | Descrição |
| :--- | :--- | :--- |
| **Scripts (Code)** | `graficos regioes de desenvolvimento pib pear.ipynb` | Pipeline de dados em Python (ETL, análise e visualização). |
| **Final Datasets** | `Tabela_Consolidada_Final.xlsx`, `Ranking_Geral_Municipios_PE.xlsx`, `Ranking_Geral_Regioes.xlsx` | Dados consolidados e limpos prontos para tomada de decisão. |
| **Visualizations** | `grafico_decrescente_*.png`, `pib_per_capita_600dpi.png`, `idh_medio_600dpi.png` | Gráficos científicos de alta resolução (600 DPI) para relatórios. |
| **Technical Docs** | `Caderno_*.pdf` (Ex: Mata Sul, Sertão, Metropolitana) | Cadernos de referência técnica por Região de Desenvolvimento. |
| **Raw Data** | `Indices_RD_Cadernos_SEPLAG_*.xlsx`, `20250106_*.xlsx` | Extrações originais de fontes governamentais. |

---

## 🛠 Tech Stack | Tecnologias Utilizadas

* **Language:** Python 3.x
* **Data Wrangling:** `Pandas`, `NumPy`
* **Scientific Visualization:** `Matplotlib`, `Seaborn` (outputs em 600 DPI)
* **Environment:** Jupyter Notebooks / Google Colab

---

## 📊 Methodology | Metodologia

**[EN]** The analysis focuses on the correlation between economic strength (GDP per capita) and social development (HDI-M) as proxies for climate resilience. The Python pipeline automates the generation of municipal rankings for each Development Region, providing a granular view of local vulnerabilities and adaptive capacity.

**[PT]** A análise foca na correlação entre força econômica (PIB per capita) e desenvolvimento social (IDH-M) como indicadores de resiliência climática. O pipeline em Python automatiza a geração de rankings municipais para cada Região de Desenvolvimento, fornecendo uma visão granular das vulnerabilidades locais e da capacidade de adaptação.

---

## 📝 Citation | Citação

Se você utilizar estes scripts ou bases de dados em sua pesquisa ou planejamento governamental, por favor cite:

> **Cardoso, J. F.; Antonino, A. C. D. (2026).** *Climate Adaptation Data Framework for Pernambuco: Socio-Economic Indicators and Python-based Analysis.* GitHub Repository.

---

## ⚖️ License | Licença

**Creative Commons Zero v1.0 Universal (CC0-1.0)**. Este material é de domínio público para fins acadêmicos e governamentais.
