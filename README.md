# 🚀 Desafio DIO – Detecção de Fraudes em Cartões de Crédito

Este projeto faz parte do **bootcamp da DIO** e tem como objetivo aplicar técnicas de **Machine Learning** para detectar fraudes em transações de cartão de crédito.

## 📌 Objetivo
- Explorar um dataset real de transações financeiras.
- Tratar o problema de **desbalanceamento de classes** (fraudes são raras).
- Criar modelos de classificação para identificar transações fraudulentas.
- Avaliar métricas como **Recall, Precision, AUC e curvas ROC/Precision-Recall**.
- Testar modelos básicos e avançados (Logistic Regression, Random Forest, XGBoost).

## 📂 Estrutura do Notebook
O notebook está dividido em etapas:

1. **Importação de bibliotecas**  
2. **Carregamento e exploração dos dados**  
3. **Feature Engineering** (transformações em variáveis)  
4. **Modelos básicos** – Logistic Regression  
5. **Modelos com balanceamento** – Random Forest  
6. **Pipeline com scaler** – Logistic Regression com normalização  
7. **Ajuste de threshold** – aumentar recall para detectar mais fraudes  
8. **Modelo avançado** – XGBoost  
9. **Importância das variáveis** – análise de features  
10. **Ajuste de hiperparâmetros** – GridSearchCV  

## 📊 Principais Resultados
- **Logistic Regression**: modelo simples, mas sensível ao desbalanceamento.  
- **Random Forest**: melhora recall ao usar `class_weight="balanced"`.  
- **XGBoost**: melhor desempenho geral, especialmente após ajuste de hiperparâmetros.  
- **Curvas ROC e Precision-Recall**: usadas para avaliar trade-off entre precisão e recall.  

## 🛠️ Tecnologias Utilizadas
- Python 3  
- Pandas / NumPy  
- Scikit-learn  
- Matplotlib  
- XGBoost  

## 📎 Dataset
O dataset utilizado está disponível publicamente:  
[Credit Card Fraud Detection Dataset](https://storage.googleapis.com/download.tensorflow.org/data/creditcard.csv)

## 📌 Como Executar
1. Clone este repositório:
   ```bash
 
