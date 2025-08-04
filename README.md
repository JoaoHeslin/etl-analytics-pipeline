# ⚡ ELETROTECH — Pipeline de Dados com Python, MySQL e Power BI

Este projeto demonstra uma pipeline completa de dados, da ingestão à visualização, utilizando Python para o tratamento e carga dos dados, MySQL para o armazenamento e Power BI para a análise visual interativa.

---

## 🎯 Objetivo

Automatizar o fluxo de dados da empresa **ELETROTECH**, estruturando a base de informações com:

- 🐍 **Python** para realizar todo o processo de ETL;
- 🐬 **MySQL** para armazenar os dados em tabelas relacionais;
- 📊 **Power BI** para criação de dashboards analíticos.

---

## ⚙️ Tecnologias Utilizadas

- `Python 3.10+`
- `pandas`, `sqlalchemy`, `mysql-connector-python`
- `MySQL`
- `Power BI`
- Jupyter Notebook (`.ipynb`)

---

## 🗂️ Estrutura do Projeto

📁 ELETROTECH/
├── dados/
│ ├── Canal.xlsx
│ ├── Categoria.xlsx
│ ├── Cidade.xlsx
│ ├── Clientes.txt
│ ├── Marca.xlsx
│ ├── Produto.xlsx
│ ├── Subcategoria.xlsx
│ └── vendas_2010_2021.xlsx
│
├── etl/
│ └── etl_mysql.ipynb # Notebook com todo o processo de ETL e conexão com MySQL
│
├── imagens/
│ ├── dashboard.png # Imagem do dashboard no Power BI
│ ├── integracao_python_mysql.png # Diagrama da integração entre Python e MySQL
│ └── modelo_relacional.png # Modelo relacional das tabelas no MySQL
│
├── powerbi/
│ └── Dashboard.pbix # Dashboard interativo no Power BI
│
└── README.md
