# 📊 Grupo44 - Projeto de Análise de Dados

Projeto desenvolvido por alunos do curso de **Análise e Desenvolvimento de Sistemas (SENAC EAD)**, como parte da disciplina:

**2601 – Projeto Integrador: Desenvolvimento Low Code em Ciência de Dados**

---

## 🔗 Repositório

Acesse o projeto no GitHub:  
👉 https://github.com/CesarSilveira-96/Grupo44-PI-ADS-Senac/tree/main

---

## 📌 Descrição do Projeto

Este projeto tem como objetivo realizar a análise de uma base de dados utilizando um processo de **ETL (Extração, Transformação e Carga)**, além da criação de um **dashboard interativo**.

A análise foca nos **preços globais da gasolina** e no impacto do conflito entre **Estados Unidos e Irã em 2026**.

---

## 📊 Base de Dados

- **Nome:** Global Petrol Prices — Impact of 2026 US-Iran War  
- **Fonte:** Kaggle  
- **Formato:** CSV  
- **Tamanho:** ~150–300 K
- **Linhas:** ~250 a 600

## 🔗 **Dataset:**  
https://www.kaggle.com/datasets/zkskhurram/global-petrol-prices-impact-of-2026-us-iran-war

⚠️ **Observação:**  Origem e Confiabilidade dos Dados

O dataset foi disponibilizado na plataforma Kaggle pelo usuário **zkskhurram**, sendo voltado para fins educacionais e analíticos.

Os dados possuem caráter **simulado/hipotético**, representando um cenário de impacto de um conflito geopolítico (EUA x Irã em 2026) sobre os preços globais da gasolina.

Por se tratar de um conjunto de dados sintético, não há garantia de atualização contínua ou correspondência com dados reais em tempo real. Ainda assim, o dataset é adequado para práticas de análise de dados, modelagem de processos ETL e construção de dashboards.

Sua utilização neste projeto tem como objetivo explorar padrões, tendências e possíveis impactos em um cenário controlado, permitindo o desenvolvimento de habilidades analíticas.

---

## 🎯 Tema

Preços globais da gasolina e o impacto do conflito entre Estados Unidos e Irã em 2026.

---

## 🌍 Contexto

O dataset reúne informações sobre preços de combustíveis em diversos países.

A proposta é analisar como **eventos geopolíticos** impactam:
- o mercado global de energia
- os preços da gasolina
- a economia internacional

---

## 🎯 Objetivo da Análise

Analisar como conflitos geopolíticos influenciam o mercado global de energia, identificando:
- padrões de variação de preços
- impactos regionais
- mudanças ao longo do tempo

---

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Python  
- **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn  
- **Dashboard:** Power BI
- **Versionamento:** Git e GitHub  

---

**📁 Estrutura do Repositório**

/Data ------------ # Base de dados bruta e tratada

/notebooks -------- # Jupyter notebooks com análises exploratórias e scripts ETL

/dashboard -------- # Arquivos e códigos relacionados ao dashboard

/docs ------------- # Documentações e relatórios adicionais

README.md --------- # Documentação principal do projeto

---

## 🗓️ Planejamento

| Semana   | Atividade                                                |
|----------|----------------------------------------------------------|
| Semana 1 | Criação do repositório e documentação inicial            |
| Semana 2 | Seleção da base de dados e definição do escopo           |
| Semana 3 | Limpeza e tratamento dos dados                           |
| Semana 4 | Análises e hipóteses                                     |
| Semana 5 | Construção do dashboard                                  |
| Semana 6 | Interpretação dos resultados                             |
| Semana 7 | Documentação final e entrega                             |

---

## 👥 Responsabilidades

| Tarefa                         | Responsável        |
|--------------------------------|--------------------|
| README                         | Todos              |
| Análise inicial                | Allan + César      |
| Tratamento de dados            | Marcos + Ricardo   |
| Análises                       | Paulo              |
| Dashboard                      | Todos              |
| Conclusões                     | César  + Ricardo   |
| Documentação                   | Allan              |
| Revisão final                  | Marcos + Paulo     |

---

## 🔄 Processo ETL

### 1. Extração
Importação dos dados do arquivo CSV (Kaggle)

### 2. Transformação
- Tratamento de valores faltantes  
- Remoção de duplicatas  
- Padronização de dados  
- Seleção de colunas relevantes  

### 3. Carga
- Exportação para CSV ou Parquet  

---

## 📊 Status do Projeto

| Etapa                       | Status         |
|---------------------------|----------------|
| Repositório               | ✅ Concluído    |
| Base de dados             | ✅ Concluído    |
| Limpeza                   | ⏳ Em andamento |
| Análises                  | ⏳ Pendente     |
| Visualizações             | ⏳ Pendente     |
| Resultados                | ⏳ Pendente     |
| Documentação final        | ⏳ Pendente     |

---

## 🔄 Status do ETL

| Etapa         | Status         |
|--------------|----------------|
| Extração     | ✅ Concluído    |
| Transformação| ⏳ Em andamento |
| Carga        | ⏳ Em andamento |

---

## 🔧 Transformações de Dados (ETL)

### ✔️ Tratamento de dados
- Preenchimento de valores nulos  
- Remoção de dados irrelevantes  

### ✔️ Limpeza
- Remoção de duplicatas  

### ✔️ Padronização
- Conversão para datetime  
- Dados numéricos em float  

### ✔️ Normalização
- Preços em USD/L  
- Padronização de países  

### ✔️ Engenharia de dados
- Variação percentual  
- Classificação por região  
- Indicadores de impacto  

## **Os dados tratados no processo de ETL serão utilizados diretamente na construção do dashboard, garantindo consistência nas métricas e visualizações.**
---

## 📊 Dashboard (Planejado)

### Visualizações
- Série temporal de preços  → analisar evolução ao longo do tempo
- Mapa mundial (choropleth)  → comparar países
- Comparação antes/depois do conflito  
- Distribuição (boxplot/violino)  → identificar variações/extremos
- Correlação (dispersão)  

### Métricas
- Preço médio global  
- Variação percentual  
- Países com maior impacto  
- Ranking de preços  

## **O dashboard terá como objetivo permitir a análise interativa dos preços globais, com foco em comparação temporal e geográfica**

---

## 👨‍💻 Integrantes

| Nome           | GitHub                                      | Email                         |
|----------------|---------------------------------------------|-------------------------------|
| César Silveira | https://github.com/CesarSilveira-96         | cesarsilveira35@gmail.com     |
| Allan Lima | https://github.com/slimaallan-ops           | slima.allan@gmail.com         |
| Marcos         | https://github.com/usuario                  | marcosbahia2605@gmail.com     |
| Paulo Mesquita | https://github.com/usuario                  | paulo_henrique.dm@hotmail.com |
| Ricardo Leão   | https://github.com/RicardoLeaoDEV           | ricardoleao_1997@live.com     |

---
