# 📊 Superstore Data Analysis

Projeto de Análise Exploratória de Dados (EDA) utilizando o dataset público **Superstore Dataset**, disponível no Kaggle.

O objetivo deste projeto é realizar o tratamento dos dados, explorar padrões de vendas, faturamento, lucro e logística, além de preparar uma base limpa para construção de dashboards analíticos.

---

## 📁 Dataset

Dataset utilizado:

- Superstore Dataset Final  
  [Kaggle - Superstore Dataset Final](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/data?utm_source=chatgpt.com)

O dataset contém informações sobre:
- vendas;
- lucro;
- categorias de produtos;
- regiões;
- formas de envio;
- descontos;
- clientes;
- datas de pedidos e envio.

---

## 🎯 Objetivos do Projeto

Este projeto busca:

- Realizar limpeza e tratamento dos dados;
- Criar novas variáveis temporais para análise;
- Explorar padrões de faturamento e lucro;
- Identificar comportamento de vendas por:
  - região;
  - categoria;
  - modalidade de envio;
  - dia da semana;
- Preparar um dataset limpo para dashboards no Looker Studio.

---

## 🧹 Tratamento dos Dados

Durante o processo de limpeza e preparação foram realizadas etapas como:

- Conversão de colunas de datas;
- Criação de variáveis temporais:
  - mês;
  - ano;
  - trimestre;
  - semana do ano;
  - dia da semana;
- Criação da variável:
  - `Dias_Envio`;
- Remoção de colunas irrelevantes;
- Padronização de formatos;
- Exportação do dataset tratado.

---

## 📈 Análises Realizadas

Algumas análises desenvolvidas:

- Faturamento por região;
- Faturamento por categoria;
- Lucro total por categoria;
- Relação entre faturamento e lucro;
- Número de vendas por região;
- Análise por dia da semana;
- Impacto das modalidades de envio;
- Tempo médio de envio.

---

## 📂 Estrutura do Projeto

```bash
📦 superstore-data-analysis
 ┣ 📜 README.md
 ┣ 📜 Superstore_Data_Analisis.ipynb
 ┣ 📜 Sample - Superstore.csv
 ┣ 📜 superstore_clean.csv
 ┗ 📂 images
```

---

## 📄 Arquivos do Projeto

### 📘 Notebook de análise

Arquivo contendo:
- tratamento dos dados;
- análises exploratórias;
- gráficos;
- visualizações.

```bash
Superstore_Data_Analisis.ipynb
```

---

### 📊 Dataset original

Arquivo original obtido do Kaggle.

```bash
Sample - Superstore.csv
```

---

### 🧹 Dataset tratado

Arquivo final utilizado para construção do dashboard.

```bash
superstore_clean.csv
```

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Looker Studio

---

## 📌 Principais Insights

Alguns insights identificados durante a análise:

- Certas categorias possuem alto faturamento mas baixa margem de lucro;
- Existem diferenças relevantes entre regiões;
- Algumas modalidades de envio concentram maior volume de vendas;
- O comportamento de vendas varia ao longo da semana;
- O desconto impacta diretamente a lucratividade.

---

## 📊 Dashboard

O dataset tratado foi preparado para integração com:

- [Looker Studio](https://lookerstudio.google.com/?utm_source=chatgpt.com)
- [Power BI](https://powerbi.microsoft.com/?utm_source=chatgpt.com)
- [Tableau](https://www.tableau.com/?utm_source=chatgpt.com)

---

## 🚀 Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/EricoCoutoJr/Superstore-Dataset.git
```

---

### 2. Instale as dependências

```bash
pip install pandas numpy matplotlib jupyter
```

---

### 3. Execute o notebook

```bash
jupyter notebook
```

Abra:

```bash
Superstore_Data_Analisis.ipynb
```

---

## 👨‍💻 Autor

Projeto desenvolvido para fins de estudo, prática de análise exploratória de dados e construção de dashboards analíticos.

---
