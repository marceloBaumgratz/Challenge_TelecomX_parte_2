## 📊 Telecom X – Previsão de Evasão de Clientes (Churn) - parte 2

### 🎯 Objetivo da Análise

Este projeto tem como objetivo identificar os fatores associados à evasão de clientes (Churn) na empresa Telecom X e desenvolver modelos preditivos capazes de identificar clientes com maior probabilidade de cancelamento.

A proposta foi aplicar técnicas de preparação de dados, análise exploratória e modelagem preditiva utilizando Python, com o objetivo de compreender os principais fatores relacionados ao churn e apoiar estratégias de retenção de clientes.

### 🔎 Principais Insights

Durante a análise, foram identificados alguns fatores importantes associados à evasão de clientes:

- Clientes com **contrato mensal (Month-to-month)** apresentam maior taxa de churn.

- Clientes com **menor tempo de relacionamento (tenure)** têm maior probabilidade de cancelar o serviço.

- A **ausência de serviços adicionais**, como segurança online e suporte técnico, está associada a maior evasão.

- O método de pagamento **Electronic check** aparece com maior incidência entre clientes que cancelam.

- Variáveis relacionadas aos **valores de cobrança** também influenciam o comportamento de evasão.

Esses fatores indicam que o tempo de relacionamento do cliente com a empresa e o tipo de contrato possuem forte influência na probabilidade de cancelamento.

### 🤖 Modelos Preditivos

Foram desenvolvidos dois modelos de classificação para prever a evasão de clientes:

**Regressão Logística**

- Modelo amplamente utilizado em problemas de classificação binária.
- Permite interpretar a influência das variáveis na previsão de churn.
- Apresentou o melhor desempenho geral no projeto.

**Random Forest**

- Modelo baseado em múltiplas árvores de decisão.
- Capaz de capturar relações não lineares entre variáveis.

Os modelos foram avaliados utilizando as seguintes métricas:

- Acurácia
- Precisão
- Recall
- F1-score
- Matriz de confusão

### 🗂 Estrutura do Projeto

O projeto é organizado em um único notebook, onde toda a análise acontece:

Challenge_TelecomX_parte_2/

├── TelecomX_BR__parte_2_Notebook_Final.ipynb -> Notebook principal com preparação dos dados, modelagem e análises  
├── dados_tratados.csv -> Dataset utilizado na análise  
├── README.md -> Documentação do projeto

No notebook, o conteúdo está organizado da seguinte forma:

* Importação das bibliotecas  
* Leitura dos dados  
* Preparação e tratamento dos dados  
* Codificação das variáveis categóricas  
* Análise exploratória  
* Divisão em dados de treino e teste  
* Criação e treinamento dos modelos  
* Avaliação dos modelos  
* Análise das variáveis mais relevantes  
* Conclusão e estratégias de retenção

---

### 🛠 Tecnologias Utilizadas

- Python  
- Pandas  
- Scikit-learn  
- Seaborn  
- Matplotlib  
- Google Colab  

### ▶ Como Executar

1. Baixe ou clone este repositório:

```bash
git clone https://github.com/marceloBaumgratz/Challenge_TelecomX_parte_2
```

2. Abra o arquivo TelecomX_BR__parte_2_Notebook_Final.ipynb no Google Colab ou Jupyter Notebook.

3. Execute as células.

### 📚 Observação Final

Projeto desenvolvido no Google Colab como parte do curso de Análise de Dados da Alura, com foco na aplicação de técnicas de machine learning para previsão de evasão de clientes e identificação dos fatores associados ao churn.
