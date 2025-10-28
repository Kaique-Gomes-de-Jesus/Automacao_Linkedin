# 🤖 Automação de Busca de Vagas no LinkedIn

[![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white)](https://www.python.org/)  [![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)  [![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B8BBE?logo=python&logoColor=white)](https://www.crummy.com/software/BeautifulSoup/)  [![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white)](https://plotly.com/python/)  [![SQLite](https://img.shields.io/badge/SQLite-07405E?logo=sqlite&logoColor=white)](https://www.sqlite.org/)  [![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-red?logo=python&logoColor=white)](https://www.sqlalchemy.org/)

---

## 🌟 Introdução

Este projeto foi desenvolvido com o objetivo de **automatizar a coleta de vagas do LinkedIn** de forma simples e eficiente.  
A automação realiza uma **busca dinâmica** conforme os parâmetros fornecidos pelo usuário, como **cargo, cidade, estado, país e período de publicação**, retornando um **banco de dados estruturado** pronto para análise.

O script também permite **armazenar os resultados** em formato `.csv` ou em um **banco SQLite**, além de gerar um **gráfico interativo** que ajuda a visualizar **as empresas com mais oportunidades**.

---

## 🎯 Objetivo

O projeto visa facilitar a vida de quem busca oportunidades ou realiza análises de mercado, permitindo:

- 🔎 Pesquisar vagas de forma automatizada por cargo e localização;  
- 🕓 Filtrar resultados por período (últimas 24h ou qualquer tempo);  
- 📦 Armazenar os resultados em **CSV ou SQLite**;  
- 📊 Visualizar, através do gráfico, quais empresas estão mais contratando.  

---

## 🛠 Tecnologias Utilizadas

- 🐍 **Python** — Linguagem principal  
- 📊 **Pandas** — Manipulação e limpeza dos dados  
- 🌐 **BeautifulSoup (bs4)** — Extração e análise do HTML do LinkedIn  
- ⚡ **Requests** — Requisições HTTP
- 🗄 **SQLite + SQLAlchemy** — Armazenamento dos dados em banco relacional  
- 📈 **Plotly Express** — Visualização interativa dos resultados  

---

## 🚀 Funcionalidades

### 1️⃣ Entrada de Dados
- O usuário informa:
  - Nome da vaga  
  - Cidade, Estado e País  
  - Quantidade de páginas a buscar  
  - Filtro de tempo (24h ou qualquer momento)

### 2️⃣ Coleta de Informações
- Extração de:
  - Título da vaga  
  - Empresa contratante  
  - Localização  
  - Data de publicação  
  - Link direto para a vaga  

### 3️⃣ Armazenamento
- Escolha entre:
  - 💾 CSV (`vagas_pesquisadas.csv`)  
  - 🗄 SQLite (`vagas.db`)

### 4️⃣ Visualização Gráfica
- Exibição de gráfico de **quantidade de vagas por empresa** utilizando **Plotly**.

---

## 🧩 Estrutura do Projeto

```text
├── Automação_Linkedin.ipynb     # Notebook principal com todo o código
├── vagas.db                          # Banco SQLite gerado (opcional)
├── Vagas_Pesquisadas.csv             # Arquivo CSV com os resultados (opcional)
└── README.md                         # Este arquivo
```

---
## 👨‍💻 Autor do Projeto

Desenvolvido por **[Kaique Gomes]** — estudante de Ciência de Dados e Desenvolvimento de Sistemas.

📫 [LinkedIn](https://www.linkedin.com/in/kaique-gomes-dev)  
🐙 [GitHub](https://github.com/Kaique-Gomes-de-Jesus)  