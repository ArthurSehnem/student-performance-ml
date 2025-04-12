# 📊 Previsão de Desempenho Estudantil com Regressão Linear

Este projeto utiliza técnicas de Ciência de Dados e Machine Learning para prever o desempenho de estudantes com base em fatores como **horas de estudo** e **notas anteriores**. O objetivo é identificar quais variáveis mais impactam o **Índice de Desempenho** e criar um modelo preditivo simples e eficaz.

---

## 🔍 Objetivo

- Explorar um dataset educacional.
- Analisar correlações entre variáveis como: horas de estudo, sono, provas práticas, atividades extracurriculares, etc.
- Treinar um modelo de **regressão linear** para prever o desempenho estudantil.
- Avaliar o modelo com métricas como **MSE**, **MAE** e **R²**.
- Criar uma função de previsão personalizada com entrada de novos dados.

---

## 📁 Dados Utilizados

- Arquivo: `Student_Performance.csv`
- Principais colunas:
  - `Hours Studied`
  - `Previous Scores`
  - `Sleep Hours`
  - `Sample Question Papers Practiced`
  - `Extracurricular Activities`
  - `Performance Index` (variável alvo)

---

## 🧠 Principais Descobertas

- Há **correlação positiva** entre:
  - **Horas Estudadas** e **Índice de Desempenho**
  - **Notas Anteriores** e **Índice de Desempenho**
- Variáveis como **horas de sono**, **atividades extracurriculares** e **número de provas praticadas** não apresentaram correlação clara com o desempenho.
- O modelo mostrou bom desempenho preditivo ao utilizar apenas as duas variáveis com maior correlação.

---

## ⚙️ Tecnologias e Bibliotecas

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib (visualização)
- Scikit-learn (modelagem e avaliação)
