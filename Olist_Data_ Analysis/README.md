# Olist E-commerce Data Analysis

## 📌 Sobre o projeto

Este projeto consiste na análise de dados de uma plataforma de e-commerce brasileira, utilizando dados da Olist.

O objetivo foi explorar os pedidos realizados na plataforma, analisar o processo de entrega e compreender a relação entre o tempo de entrega e a avaliação atribuída pelos clientes.

O projeto foi desenvolvido utilizando **Python, Pandas, NumPy, Matplotlib e Seaborn**, aplicando técnicas de preparação, exploração e análise de dados.

## 🎯 Objetivos

* Explorar e preparar os dados dos pedidos.
* Analisar o comportamento dos pedidos e das avaliações dos clientes.
* Analisar o tempo de entrega dos pedidos.
* Identificar casos com tempos de entrega elevados.
* Investigar a relação entre o tempo de entrega e a avaliação dos clientes.
* Apresentar os principais resultados através de estatísticas e visualizações.

## 📂 Dados utilizados

O projeto utiliza quatro datasets:

* `olist_orders_dataset.csv` — informações sobre os pedidos.
* `olist_customers_dataset.csv` — informações sobre os clientes.
* `olist_order_items_dataset.csv` — informações sobre os itens dos pedidos.
* `olist_order_reviews_dataset.csv` — avaliações dos clientes.

Os datasets são utilizados em conjunto para relacionar informações sobre pedidos, clientes, produtos e avaliações.

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🔎 Principais análises

O projeto inclui:

* preparação e tratamento dos dados;
* análise exploratória;
* análise do tempo de entrega;
* identificação de tempos de entrega elevados;
* análise das avaliações dos clientes;
* análise da relação entre tempo de entrega e avaliação.

Na análise da relação entre o tempo de entrega e a avaliação média, foi obtida uma correlação de aproximadamente **-0,334**. Este resultado indica uma relação negativa entre as duas variáveis: de forma geral, entregas mais demoradas tendem a estar associadas a avaliações inferiores.

## 📊 Principais resultados

* A avaliação média dos clientes foi de aproximadamente **4,09 pontos**.
* A mediana das avaliações foi de **5 pontos**.
* O tempo médio de entrega foi de aproximadamente **12 dias**.
* Foram identificados casos extremos de entrega, com valores superiores a **200 dias**.
* A correlação entre `delivery_days` e `review_score_mean` foi de aproximadamente **-0,334**.

## 📁 Estrutura do projeto

```text
Olist-Data-Analysis/
│
├── data/raw/
│   ├── olist_orders_dataset.csv
│   ├── olist_customers_dataset.csv
│   ├── olist_order_items_dataset.csv
│   └── olist_order_reviews_dataset.csv
│
├── notebooks/
│   └── olist_analysis.ipynb
│
├── README.md
└── requirements.txt
```

## 🚀 Como executar o projeto

### 1. Clonar o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Entrar na pasta do projeto

```bash
cd Olist-Data-Analysis
```

### 3. Criar um ambiente virtual

```bash
python -m venv venv
```

### 4. Ativar o ambiente virtual

No Windows:

```bash
venv\Scripts\activate
```

No macOS/Linux:

```bash
source venv/bin/activate
```

### 5. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 6. Executar o notebook

```bash
jupyter notebook
```

Depois, abrir o notebook localizado na pasta `notebooks`.

## 📌 Conclusão

A análise permitiu explorar diferentes aspetos do processo de compra e entrega, com especial atenção ao tempo de entrega e à experiência dos clientes.

Os resultados mostram uma tendência negativa entre o tempo de entrega e a avaliação média dos clientes, sugerindo que entregas mais demoradas podem estar associadas a uma pior avaliação da experiência de compra.

Este projeto permitiu aplicar, de forma prática, conceitos de **Python, manipulação de dados, análise exploratória, estatística descritiva e visualização de dados**.

````


