# Classificação de Cobertura Florestal 

Este projeto aplica o framework CRISP-DM para classificar automaticamente 7 tipos de cobertura florestal com base em variáveis cartográficas (Forest Cover Type Dataset).

## Objetivo
Resolver um problema de desbalanceamento severo (103:1) utilizando técnicas de oversampling (SMOTE) e normalização para construir um modelo preditivo confiável.

## Tecnologias e Ferramentas
* **Linguagem:** Python
* **Machine Learning:** Scikit-Learn, LightGBM, XGBoost
* **Processamento de Dados:** Pandas, Imbalanced-learn (SMOTE)
* **Métrica Principal:** F1-macro e Balanced Accuracy

## Principais Resultados
O modelo homologado foi o **LightGBM** treinado sobre a variante **v4 (Escala + SMOTE)**.
* **F1-macro (Teste):** 0.8688
* **Balanced Accuracy:** 0.9094
* Houve comprovação de superioridade estatística em relação ao baseline através do Teste de Wilcoxon ($p = 0.031$).

## Como executar
1. Clone o repositório:
   `git clone https://github.com/SEU_USUARIO/classificacao-cobertura-florestal.git`
2. Instale as dependências:
   `pip install -r requirements.txt`
3. Execute os notebooks na pasta `/notebooks`.
