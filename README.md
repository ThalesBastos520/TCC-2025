# 🎓 Análise Preditiva de Câncer de Pulmão com Técnicas de Machine Learning

Este repositório contém o Trabalho de Conclusão de Curso (TCC) apresentado ao curso de Engenharia de Computação do CEFET-MG, com foco na análise preditiva de câncer de pulmão utilizando técnicas de aprendizado de máquina e análise estatística.

## 🧠 Objetivo

Desenvolver e comparar modelos de aprendizado supervisionado para prever a ocorrência de câncer de pulmão com base em atributos clínicos, com ênfase na análise segmentada por gênero (masculino e feminino).

## 📁 Conteúdo do Repositório

- 📄 `TCC2_Thales Henrique Bastos Neves.pdf`: Versão final do trabalho escrito.
- 📊 `lung_cancer2.ipynb`: Código-fonte em Python com toda a análise exploratória, treinamento dos modelos, validação e métricas.
- 🧬 `survey_lung_cancer.csv`: Base de dados utilizada no estudo (proveniente do Kaggle).
- 📈 `resultados/`: Gráficos e tabelas geradas durante a execução do projeto.

## 🛠️ Tecnologias e Bibliotecas

- Python 3
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- SMOTE (imbalanced-learn)

## 📌 Principais Métricas Avaliadas

- Acurácia
- F1-Score
- Recall (Sensibilidade)
- Curva ROC & AUC
- Análise separada por gênero para melhor compreensão da performance dos modelos

## 🔍 Resultados

Os modelos Random Forest, XGBoost e Gaussian Naive Bayes mostraram alto desempenho no conjunto completo. Entretanto, a performance variou de acordo com o gênero, reforçando a importância da análise personalizada.

## ⚠️ Limitações

A base de dados é limitada em tamanho e profundidade, o que pode afetar a generalização dos modelos. Além disso, ao segmentar os dados por gênero, o volume de dados em cada grupo torna-se ainda menor, o que exige cautela na interpretação dos resultados.


## 📫 Contato

Thales Bastos  
[LinkedIn](https://www.linkedin.com/in/thales-henrique-bastos15) · [Email](thaleshenrique44@gmail.com)
