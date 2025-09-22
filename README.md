# Checkpoint 02 – Casos de Uso de Machine Learning em Energias Renováveis
## Integrantes do Grupo
- Bruno Otávio da Cruz Carvalho, RM 562354  
- João Ivo Campolina Silveira, RM 562287  
- João Vitor Santana Silva Ribeiro, RM 564693  
- Luiz Miguel Martin Crocco, RM 562796  
- Rafael Louzã Lopes, RM 564963  
---
## Descrição Geral

Este repositório contém os códigos desenvolvidos para o **Checkpoint 02** da disciplina *Soluções em Energias Renováveis e Sustentáveis*.  
Foram explorados casos de **regressão** e **classificação** aplicados a datasets de energia residencial, redes inteligentes e geração renovável (solar e eólica).
Os notebooks/scripts em Python utilizam bibliotecas como **pandas**, **numpy**, **scikit-learn** e **matplotlib**.
---
## Estrutura dos Exercícios
### Exercício 1 – Regressão (Appliances Energy Prediction)
- **Objetivo:** Prever o consumo de energia dos eletrodomésticos de uma residência (coluna `Appliances`).  
- **Dataset:** [energydata_complete.csv](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction)  
- **Modelos:** Regressão Linear, Árvore de Regressão e Random Forest.  
- **Avaliação:** R², RMSE e MAE.  
### Exercício 2 – Classificação (Smart Grid Stability)
- **Objetivo:** Classificar a estabilidade da rede elétrica em *estável* ou *instável* (coluna `stabf`).  
- **Dataset:** [Smart Grid Stability Dataset](https://archive.ics.uci.edu/ml/datasets/Smart+Grid+Stability)  
- **Modelos:** Árvore de Decisão, KNN e Regressão Logística.  
- **Avaliação:** Acurácia, F1-score e Matriz de Confusão.  
### Exercício 1 – Classificação (Solar)
- **Objetivo:** Prever níveis de radiação solar (*Alta* ou *Baixa*) a partir da mediana da coluna `Radiation`.  
- **Dataset:** [Solar Radiation Prediction](https://www.kaggle.com/datasets/dronio/SolarEnergy)  
- **Modelos:** Árvore de Decisão, Random Forest e SVM.  
- **Avaliação:** Acurácia e Matriz de Confusão (com visualização em matplotlib).  
### Exercício 2 – Regressão (Eólica)
- **Objetivo:** Prever a potência ativa gerada (`LV ActivePower (kW)`) por turbinas eólicas a partir de variáveis operacionais.  
- **Dataset:** [Wind Turbine Scada Dataset](https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset)  
- **Modelos:** Regressão Linear, Árvore de Regressão e Random Forest.  
- **Avaliação:** RMSE e R², com gráfico comparativo dos modelos.  
---
## Como Executar
1. Instale as dependências:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
Coloque os arquivos .csv dos datasets na pasta data/ (ou ajuste os caminhos no código).
Execute os scripts Python correspondentes para cada exercício:
Observações
Os datasets usados são públicos (UCI e Kaggle).
Os códigos foram escritos de forma clara e simples, priorizando legibilidade em vez de complexidade.
As métricas e gráficos gerados são suficientes para comparar o desempenho dos modelos em cada caso de uso.
