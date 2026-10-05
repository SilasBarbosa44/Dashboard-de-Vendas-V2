# 📊 Dashboard de Vendas - MySQL + Power BI

Projeto de portfólio desenvolvido para análise de dados comerciais utilizando **MySQL, SQL e Power BI**.

O projeto simula um cenário de vendas e apresenta um dashboard desenvolvido para transformar dados armazenados em banco de dados em **KPIs, indicadores e análises visuais**, permitindo acompanhar o desempenho comercial.

O objetivo é demonstrar conhecimentos práticos em **SQL, MySQL, Power BI, DAX, modelagem de dados e análise de indicadores de negócio**.

---

## 🎯 Objetivo do Projeto

O principal objetivo deste projeto é desenvolver uma solução de análise de vendas capaz de transformar dados brutos em informações úteis para tomada de decisão.

O dashboard permite analisar:

- Faturamento total
- Ticket médio
- Total de vendas
- Quantidade de produtos vendidos
- Clientes atendidos
- Faturamento por vendedor
- Faturamento por mês
- Faturamento por categoria
- Desempenho comercial
- Distribuição das vendas

---

## 🛠️ Tecnologias Utilizadas

- **MySQL 8.0** — Banco de dados
- **SQL** — Consultas e análise dos dados
- **Power BI Desktop** — Visualização e criação do dashboard
- **DAX** — Criação dos indicadores e medidas
- **MySQL Workbench** — Administração e execução dos scripts SQL

---

## 🗄️ Banco de Dados

O projeto utiliza um banco de dados desenvolvido em **MySQL 8.0** para armazenar as informações utilizadas nas análises.

O banco de dados é composto por **7 tabelas** utilizadas para representar diferentes informações do cenário comercial.

A estrutura do banco é criada através do arquivo:

```text
database.sql
```

Os dados fictícios utilizados no projeto estão disponíveis em:

```text
dados/dados_fake.sql
```

Os dados são fictícios e foram criados exclusivamente para fins de estudo e demonstração de habilidades em análise de dados.

---

## 📂 Estrutura do Projeto

```text
Dashboard-Vendas-MySQL-PowerBI/
│
├── dados/
│   └── dados_fake.sql
│
├── powerbi/
│   ├── Dashboard_Vendas.pbix
│   │
│   └── prints/
│       ├── 1_Visao_Geral.png
│       ├── 2_Produto.png
│       ├── 3_Cliente.png
│       └── 4_Vendedores.png
│
├── database.sql
│
└── README.md
```

---

## 📊 Dashboard

O dashboard foi desenvolvido no **Power BI** para apresentar uma visão geral do desempenho das vendas.

A página de visão geral contém indicadores principais e gráficos para facilitar a análise dos resultados comerciais.

### 📌 KPIs Principais

| Indicador | Resultado |
|---|---:|
| **Clientes Atendidos** | 5 |
| **Faturamento** | R$ 23,9 mil |
| **Ticket Médio** | R$ 3,41 mil |
| **Total de Vendas** | 7 |
| **Quantidade de Produtos Vendidos** | 18 |

---

## 📈 Análises do Dashboard

### 💰 Faturamento por Vendedor

O gráfico de faturamento por vendedor permite comparar o desempenho individual dos vendedores e identificar quais possuem maior participação no faturamento.

Vendedores apresentados no dashboard:

- Carlos Silva
- João Lima
- Ana Souza
- Maria Oliveira

---

### 📅 Faturamento por Mês

O dashboard apresenta a evolução do faturamento ao longo dos meses.

Os dados permitem comparar o desempenho entre:

- Abril
- Maio
- Junho

Essa análise facilita a identificação de períodos com maior e menor faturamento.

---

### 🏷️ Faturamento por Categoria

O dashboard apresenta o faturamento separado por categoria.

Categorias apresentadas no dashboard:

- Informática
- Móveis

Essa análise permite identificar quais categorias possuem maior participação no faturamento total.

---

## 📊 Indicadores de Vendas

### 👥 Clientes Atendidos

O dashboard apresenta:

**5 clientes atendidos**

Esse indicador permite acompanhar a quantidade de clientes que realizaram compras no período analisado.

---

### 💰 Faturamento

O faturamento total apresentado no dashboard é de aproximadamente:

**R$ 23,9 mil**

Esse indicador representa o valor total gerado pelas vendas analisadas.

---

### 🎯 Ticket Médio

O ticket médio apresentado é de aproximadamente:

**R$ 3,41 mil**

Esse indicador permite analisar o valor médio movimentado por venda.

---

### 🛒 Total de Vendas

O projeto apresenta:

**7 vendas**

Esse KPI permite acompanhar o volume total de vendas realizado no período analisado.

---

### 📦 Quantidade de Produtos Vendidos

O dashboard apresenta:

**18 produtos vendidos**

Esse indicador permite acompanhar o volume de produtos comercializados.

---

## 🔎 Perguntas de Negócio Respondidas

Através do dashboard é possível responder perguntas como:

- Quanto foi faturado?
- Qual foi o ticket médio?
- Quantas vendas foram realizadas?
- Quantos produtos foram vendidos?
- Quantos clientes realizaram compras?
- Qual vendedor gerou mais faturamento?
- Qual vendedor teve menor faturamento?
- Como o faturamento evoluiu ao longo dos meses?
- Qual categoria apresentou maior faturamento?
- Qual categoria apresentou menor faturamento?
- Como está distribuído o faturamento entre os vendedores?
- Como está distribuído o faturamento entre as categorias?

---

## 💡 Principais Insights

Com os dados utilizados no projeto, o dashboard permite identificar:

- O faturamento total gerado pelas vendas.
- O ticket médio das vendas realizadas.
- O volume total de vendas.
- A quantidade de produtos comercializados.
- A quantidade de clientes atendidos.
- Os vendedores com maior participação no faturamento.
- A evolução do faturamento durante os meses analisados.
- As categorias com maior participação nas vendas.
- A distribuição do faturamento entre diferentes vendedores e categorias.

---

## 🧮 Principais KPIs

Os principais indicadores utilizados no projeto são:

```text
Faturamento Total
Ticket Médio
Total de Vendas
Quantidade de Produtos Vendidos
Clientes Atendidos
Faturamento por Vendedor
Faturamento por Mês
Faturamento por Categoria
```

---

## 🔄 Fluxo do Projeto

O fluxo do projeto pode ser representado da seguinte forma:

```text
Dados Fictícios
      ↓
    MySQL
      ↓
     SQL
      ↓
Modelagem dos Dados
      ↓
    Power BI
      ↓
     DAX
      ↓
Dashboard de Vendas
      ↓
Análise dos Indicadores
```

---

## 🖼️ Prints do Dashboard

### 1. Visão Geral

A página de visão geral apresenta os principais KPIs do projeto e gráficos de acompanhamento do faturamento.

![Visão Geral](powerbi/prints/1_Visao_Geral.png)

---

### 2. Análise de Produtos

Página destinada à análise do desempenho dos produtos e suas respectivas vendas.

![Produtos](powerbi/prints/2_Produto.png)

---

### 3. Análise de Clientes

Página destinada à análise dos clientes e das vendas relacionadas aos clientes.

![Clientes](powerbi/prints/3_Cliente.png)

---

### 4. Análise de Vendedores

Página destinada à análise do desempenho dos vendedores.

![Vendedores](powerbi/prints/4_Vendedores.png)

---

## 🚀 Como Rodar o Projeto

### 1. Clonar o Repositório

Clone o repositório para sua máquina:

```bash
git clone SEU_LINK_DO_REPOSITORIO
```

Entre na pasta do projeto:

```bash
cd Dashboard-Vendas-MySQL-PowerBI
```

---

### 2. Configurar o Banco de Dados

Abra o **MySQL Workbench**.

Execute primeiro o arquivo:

```text
database.sql
```

Esse script cria a estrutura do banco de dados.

---

### 3. Inserir os Dados

Depois de criar as tabelas, execute:

```text
dados/dados_fake.sql
```

Esse arquivo insere os dados fictícios utilizados no projeto.

---

### 4. Abrir o Power BI

Abra o arquivo:

```text
powerbi/Dashboard_Vendas.pbix
```

Depois de abrir o projeto no Power BI Desktop, atualize a conexão com o banco de dados MySQL local.

---

## 🧠 Conceitos Aplicados

Durante o desenvolvimento do projeto foram aplicados conceitos de:

- SQL
- MySQL
- Banco de dados relacional
- Modelagem de dados
- Relacionamento entre tabelas
- Consultas SQL
- Agregações
- Filtros
- Indicadores de negócio
- KPIs
- DAX
- Power BI
- Visualização de dados
- Análise de vendas
- Business Intelligence
- Data Analytics

---

## 📚 Objetivo de Portfólio

Este projeto foi desenvolvido com o objetivo de demonstrar conhecimentos práticos na área de **Data Analytics e Business Intelligence**.

O projeto demonstra o processo de trabalho com dados desde o armazenamento e consulta no banco de dados até a construção de indicadores e visualizações no Power BI.

A solução permite transformar dados brutos em informações visuais para facilitar a análise do desempenho comercial.

---

## 👨‍💻 Autor

### Silas Barbosa da Silva

Projeto desenvolvido para portfólio na área de:

**Data Analytics | Business Intelligence**

### Tecnologias

```text
SQL
MySQL
Power BI
DAX
```

---

## ⭐ Projeto

Projeto desenvolvido com foco em demonstrar conhecimentos práticos em:

**SQL + MySQL + Power BI + DAX + Análise de Dados**

## 👨‍💻 Autor

### Silas Barbosa da Silva

**GitHub:** [SilasBarbosa44](https://github.com/SilasBarbosa44)

**LinkedIn:** [Silas Barbosa da Silva](https://www.linkedin.com/in/silas-barbosa-1885ab3a0/)
