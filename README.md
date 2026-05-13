# Predictive-Analysis-ML

<img width="600" height="174" alt="Fiap-logo-novo" src="https://github.com/user-attachments/assets/7b403e06-60ba-4044-9dda-5e4735d665cf" />

# Análise Preditiva de Fertilizantes 🚜🌱

Este repositório contém um pipeline completo de Machine Learning para a recomendação inteligente de fertilizantes baseada em dados químicos e físicos do solo.

## 🚀 Sobre o Projeto
O objetivo principal é comparar o desempenho de diversos algoritmos de classificação para encontrar o modelo mais preciso na predição de insumos agrícolas.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python 3
- **Manipulação de Dados:** Pandas
- **Visualização:** Seaborn, Matplotlib
- **Machine Learning:** Scikit-Learn

## 📋 Etapas do Desenvolvimento
1. **Análise Exploratória:** Entendimento da distribuição dos dados e visualização de classes.
2. **Pré-processamento:**
   - `LabelEncoder` para a variável alvo (Fertilizer Name).
   - `OneHotEncoder` para variáveis categóricas nominais (Soil e Crop Type).
   - `MinMaxScaler` para normalização de escalas numéricas (colocando dados entre 0 e 1).
3. **Modelagem:** Implementação de 7 variações de algoritmos (LogReg, KNN, SVM, Trees).
4. **Avaliação:** Comparação via Acurácia e Classification Report.

## 📊 Modelos Comparados
- Regressão Logística
- KNN (K-Neighbors)
- SVM (Kernels: Linear, Poly, RBF)
- Decision Tree
- Random Forest

## 📈 Resultados
O projeto gera um ranking automatizado dos modelos no final do notebook, permitindo visualizar qual algoritmo obteve a melhor performance para este conjunto de dados específico.

---
*Projeto desenvolvido para fins educacionais em Machine Learning.*
