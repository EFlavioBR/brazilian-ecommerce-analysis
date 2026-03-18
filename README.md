# Análise de E-Commerce Brasileiro (Dataset Olist)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## 📌 Visão Geral
Este projeto realiza uma Análise Exploratória de Dados (AED) no conjunto de dados públicos da Olist. O objetivo é extrair insights estratégicos sobre o desempenho das vendas, comportamento do consumidor e eficiência logística de um marketplace brasileiro entre 2016 e 2018.

> **Status do Projeto:** 🚧 Em desenvolvimento (Análise Exploratória Concluída).

---

## 📊 Insights Extraídos (Até agora)

### 1. Evolução do Faturamento
A análise da série temporal revelou um crescimento consistente da plataforma ao longo de 2017. O ponto de maior destaque foi **Novembro de 2017**, onde o faturamento ultrapassou R$ 1 milhão devido ao impacto da **Black Friday**.

### 2. Motores de Receita (Categorias)
Nem sempre as categorias com mais vendas são as que geram mais dinheiro. Identificamos que **Beleza & Saúde**, **Relógios & Presentes** e **Cama, Mesa & Banho** são os pilares de faturamento, indicando um ticket médio elevado nesses setores.

### 3. Eficiência Logística (Lead Time)
O tempo médio de entrega identificado foi de **12 dias**. 
- **Pico de entrega:** A maioria dos pedidos chega entre 7 e 15 dias.
- **Taxa de Atraso:** Aproximadamente **7%**, sinalizando oportunidades de melhoria na experiência final do cliente.

### 4. Comportamento Financeiro (Pagamentos)
Investigamos como o brasileiro paga suas compras:
- **Cartão de Crédito:** É o método soberano, impulsionado pela cultura do parcelamento.
- **Fenômeno das 10x:** Observamos um pico atípico em **10 parcelas**, sugerindo que o consumidor utiliza o crédito para viabilizar compras de maior valor.
- **Boleto Bancário:** Mantém-se como a segunda força, atendendo ao público que busca descontos à vista ou não possui limite de crédito.

---

## 🛠️ Tecnologias e Ferramentas
- **Linguagem:** Python 3.11.9
- **Manipulação:** Pandas, Numpy
- **Visualização:** Matplotlib, Seaborn
- **Ambiente:** VS Code / Jupyter Notebook

## 📁 Estrutura do Repositório
```text
├── data/               # Bases em CSV (não enviadas ao GitHub por tamanho)
├── 
├── notebooks/          # 1_AED.ipynb (Arquivo principal de análise)
├── .gitignore          # Filtros para venv e arquivos de dados
└── README.md           # Documentação do projeto
