# Análise do Conjunto de Dados "Adult" com Modelos de Classificação  

Este repositório contém um notebook Jupyter dedicado à análise exploratória e à aplicação de diferentes modelos de classificação no conjunto de dados **"Adult"**, disponível no [UCI Machine Learning Repository](https://archive.ics.uci.edu/) e no [Kaggle](https://www.kaggle.com/c/adult-pmr3508).  

---

## 📌 Objetivo  

O objetivo deste projeto é desenvolver modelos de classificação para prever se um indivíduo ganha mais de **50 mil dólares por ano**, com base em variáveis socioeconômicas extraídas do conjunto de dados "Adult". 

---

## 🔍 Abordagem Utilizada

Para alcançar o objetivo proposto, foi conduzida uma análise exploratória detalhada, visando identificar padrões e potenciais vieses nos dados. Em conjunto com tal análise, foram aplicadas diversas técnicas de pré-processamento, incluindo tratamento de valores ausentes, detecção de outliers, codificação de variáveis categóricas e normalização de features numéricas.

Na etapa de modelagem, quatro algoritmos de machine learning foram testados: Regressão Logística, Support Vector Machine (SVM), XGBoost e Random Forest. Seus hiperparâmetros foram ajustados por meio de validação cruzada para otimizar o desempenho.

Por fim, a avaliação dos modelos foi realizada com base em diferentes métricas de classificação, permitindo uma comparação detalhada entre as abordagens e a seleção da melhor solução para o problema.

 

### 1️⃣  **Configuração Inicial**  
- Instalação e importação das bibliotecas necessárias (*Pandas, NumPy, Scikit-learn, Plotly, entre outras*).  
- Leitura e transformação do conjunto de dados em um DataFrame do Pandas.  

### 2️⃣ **Exploração e Pré-processamento dos Dados**  
- **Análise exploratória**: compreensão da estrutura do dataset e detecção de padrões.  
- **Tratamento de valores inconsistentes** e análise de distribuição das variáveis.  
- **Identificação e tratamento de outliers** nas features numéricas.  
- **Análise de correlação** entre variáveis.  
- **Processamento de variáveis categóricas**, incluindo:  
  - Codificação binária da variável alvo (*label encoding*).  
  - Transformação de uma feature ordinal.  
  - One-Hot Encoding para variáveis categóricas nominais.  
  - Compressão de algumas categorias para reduzir a dimensionalidade.  
- **Normalização das features numéricas** para melhorar o desempenho dos modelos.  

### 3️⃣ **Treinamento dos Modelos de Classificação**  
- Implementação e treinamento dos seguintes modelos:  
  - **Regressão Logística**  
  - **Support Vector Machine (SVM)**  
  - **XGBoost**  
  - **Random Forest**  
- Seleção dos hiperparâmetros mais adequados por meio de validação cruzada.  

### 4️⃣ **Comparação e Avaliação dos Modelos**  
- Análise dos resultados obtidos para cada modelo.  
- Comparação do desempenho com métricas como:  
  - **Acurácia**  
  - **Matriz de confusão**  
  - **Precisão, recall e F1-score**  
- Justificativa para a escolha do modelo final.  

---

## 🚀 Instruções para Executar o Notebook

Clone o repositório:  
```bash
 git clone https://github.com/GB-Navarro/PMR3508-Adult-Analysis
```
Acesse o diretório do projeto e execute o notebook.

As dependências serão instaladas automaticamente dentro do notebook.

---
 
