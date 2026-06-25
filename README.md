# Portfolio: Projetos de Data Science e IA (Quantum Finance)

Este repositório contém o portfólio de projetos desenvolvidos durante o **MBA em Data Science e IA pela FIAP**. O objetivo central destes trabalhos é a aplicação de técnicas avançadas de análise de dados, Machine Learning e Processamento de Linguagem Natural (PLN) para resolver problemas reais no setor financeiro, atuando como parte do time de analistas da **Quantum Finance**.

---

## 📂 Projetos Desenvolvidos

### 1. Classificação de Score de Crédito
* **Descrição:** Construção de um sistema robusto para a classificação de risco de crédito, transformando dados complexos em *insights* acionáveis para a tomada de decisão.
* **Técnicas:** Análise Exploratória de Dados (EDA), tratamento de valores nulos (*Monthly_Inhand_Salary*, *Credit_History_Age*) e *pipeline* de modelagem supervisionada.
* **Algoritmos:** Random Forest, XGBoost e LightGBM.
* **Resultado:** O **LightGBM** foi o modelo campeão, alcançando um *f1_weighted* de **0.74** via otimização com *GridSearch*, demonstrando excelente capacidade de generalização e eficácia no tratamento do desequilíbrio das classes alvo.

### 2. Classificador de Chamados (NLP)
* **Descrição:** Automatização da categorização de assuntos em atendimentos via chat para otimizar o fluxo de suporte ao cliente.
* **Técnicas:** Processamento de Linguagem Natural (PLN) aplicado a textos abertos, utilizando vetorização **TF-IDF**.
* **Modelo:** LinearSVC.
* **Resultado:** Modelo otimizado via *GridSearchCV*, alcançando um *f1_weighted* de **0.902**, garantindo alta precisão na identificação automática das demandas dos clientes.

---

## 🛠 Tecnologias e Ferramentas
* **Linguagem:** Python
* **Bibliotecas:** `Pandas`, `Scikit-learn`, `LightGBM`, `XGBoost`, `Matplotlib`, `Seaborn`.
* **Ambiente:** Jupyter Notebooks.

---



---
*Este repositório reflete o meu foco em desenvolver soluções que unem técnica de ponta, rigor analítico e valor de negócio.*
