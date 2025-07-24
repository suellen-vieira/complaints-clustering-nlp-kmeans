# Consumer Complaints Clustering and Resolution Prediction – Brazil (2022)

This project analyzes consumer complaint data from the Cadastro Nacional de Reclamações Fundamentadas 2022 (Brazil's National Registry of Substantiated Consumer Complaints), provided by the Brazilian Ministry of Justice (PROCONS – Sindec). The main goal is to combine Natural Language Processing (NLP) and Machine Learning to extract insights from complaint texts, identify recurring patterns, and predict complaint resolution outcomes.


## 📊 Dataset Overview

- **Source**: [dados.gov.br](https://dados.gov.br/dados/conjuntos-dados/cadastro-nacional-de-reclamacoes-fundamentadas-procons-sindec1)
- **Year**: 2022
- **Scope**: Includes complaint details such as:
  - Company name (Razão Social)
  - Complaint description
  - Region and state
  - Dates of opening and closure
  - Whether the complaint was resolved or not


## ⚙️ Techniques Used

- Data Cleaning & Preprocessing

- NLP: Tokenization, stopword removal

- TF-IDF Vectorization for text features

- Unsupervised Learning: KMeans clustering for topic discovery

- Supervised Learning: Random Forest for complaint resolution prediction

- Exploratory Data Analysis (EDA): Visualization of complaint patterns by company, sector, and region


## 🎯 Key Goals

- Text Clustering: Apply NLP and KMeans to group similar complaints and uncover dominant complaint topics.

- Prediction: Use a Random Forest classifier to predict whether a complaint will be resolved or unresolved, based on structured features.

- Topic Discovery: Identify the most frequent issues reported by consumers (e.g., billing disputes, poor service, contract problems).

- Company-Level Analysis: Compare complaint clusters across different companies, sectors, and regions, highlighting recurring problems.