# Challenge-Telecom-X-an-lise-de-evas-o-de-clientes---Parte-2
Um desafio do programa ONE da Oracle com parceria com a Alura

# 📊 TelecomX - Predição de Churn

Este projeto tem como objetivo **analisar e prever o churn de clientes** em uma empresa de telecomunicações, utilizando modelos de Machine Learning.  
A partir da análise exploratória e modelagem preditiva, foram identificados os principais fatores que levam à evasão e propostas **estratégias acionáveis** para aumentar a retenção de clientes.

---

## 🚀 Tecnologias Utilizadas

- **Python 3.10+**
- **Pandas / NumPy** → manipulação e análise de dados
- **Matplotlib / Seaborn** → visualizações gráficas
- **Scikit-learn** → modelagem preditiva
- **LightGBM** → modelo de gradient boosting
- **Jupyter Notebook** → ambiente de experimentação

---

## 📈 Modelos Avaliados

Foram comparados três algoritmos principais:

- 🔹 **Regressão Logística** → Melhor equilíbrio entre *Recall* e *Precision* (**AUC = 0.84**)  
- 🔹 **Random Forest** → Bom desempenho, mas mais custoso em termos computacionais  
- 🔹 **LightGBM** → Alta performance, mas menor interpretabilidade  

O modelo escolhido foi a **Regressão Logística**, por ser mais simples, interpretável e eficaz para os objetivos de negócio.

---

## 🔍 Principais Insights

- **Tipo de contrato** mensal é o maior preditor de churn  
- **Tenure baixo (menos de 12 meses)** aumenta drasticamente o risco  
- **Cobranca Mensal alta** sem valor percebido acelera a evasão  
- **Internet Fibra Óptica** aparece associada a maior churn, devido ao preço  

---

## 👥 Perfis de Clientes Identificados

- **📌 Risco alto de churn**
  - Clientes com **contrato mensal**
  - Clientes de **fibra óptica insatisfeitos**
  - Clientes básicos **sem serviços adicionais**  

- **✅ Cliente ideal (baixo risco)**
  - Clientes com **contrato anual/bianual**
  - Clientes que consomem **serviços de valor agregado**
  - Clientes **com família/estabilidade**  

---

## 🎯 Recomendações Estratégicas

1. **Blindagem de Novos Clientes** → oferecer migração para contratos anuais com benefícios nos primeiros meses  
2. **Pacotes de Valor para Fibra Óptica** → incluir serviços de suporte como padrão  
3. **Campanha de Ecossistema** → incentivar múltiplos serviços para aumentar dependência e lealdade

---

##👨‍💻 Autor

Desenvolvido por Lucas Santos
🔗 LinkedIn
