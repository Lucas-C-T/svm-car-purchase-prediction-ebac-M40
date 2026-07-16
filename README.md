# Projeto: Modelo de Classificação - SVM (Propensão de Compra)

## 🎯 Objetivo
Este projeto faz parte do curso de Data Science da EBAC (Módulo 39). O objetivo é aplicar técnicas de **Support Vector Machine (SVM)** para prever a propensão de compra de carros pelos clientes, com base em dados demográficos e financeiros.

## 🛠️ Tecnologias Utilizadas
- Python 3.9+
- Pandas, NumPy
- Scikit-learn (SVC, LabelEncoder, Model Selection)
- Matplotlib, Seaborn

## 📊 Metodologia
1. **Exploração dos dados**: Análise de tipos de dados, verificação de nulos e remoção da coluna `User ID`.
2. **Pré-processamento**: Aplicação de `LabelEncoder` na variável categórica `Gender` para adequação ao modelo.
3. **Análise**: Criação da matriz de correlação para identificar as variáveis com maior impacto na variável target (`Purchased`).
4. **Modelagem**: Implementação e treinamento do classificador SVM (SVC).
