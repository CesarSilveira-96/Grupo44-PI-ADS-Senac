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
- **Tamanho:** Aproximadamente X MB / Y linhas *(atualizar)*  

🔗 Dataset:  
https://www.kaggle.com/datasets/zkskhurram/global-petrol-prices-impact-of-2026-us-iran-war

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
- **Dashboard:** Power BI / Tableau / Dash *(definir)*  
- **Versionamento:** Git e GitHub  

---

---

**📁 Estrutura do Repositório**

/Data ------------ # Base de dados bruta e tratada

/notebooks -------- # Jupyter notebooks com análises exploratórias e scripts ETL

/dashboard -------- # Arquivos e códigos relacionados ao dashboard

/docs ------------- # Documentações e relatórios adicionais

README.md --------- # Documentação principal do projeto

---

🗓️ **Planejamento do Projeto**

| Semana   | Atividade                                                |
| -------- | -------------------------------------------------------- |
| Semana 1 | Criação do repositório e documentação inicial            |
| Semana 2 | Seleção da base de dados e definição do escopo           |
| Semana 3 | Limpeza, tratamento e organização dos dados              |
| Semana 4 | Desenvolvimento de análises e hipóteses                  |
| Semana 5 | Construção do dashboard e visualizações                  |
| Semana 6 | Interpretação dos resultados e elaboração das conclusões |
| Semana 7 | Documentação final e entrega do projeto                  |

---

| Tarefa                         | Responsável    |
| ------------------------------ | -------------- |
| Estruturação do README         | César Silveira |
| Seleção e análise inicial      | Allan          |
| Limpeza e tratamento dos dados | Marcos         |
| Desenvolvimento das análises   | Paulo Mesquita |
| Construção do dashboard        | Ricardo Leão   |
| Interpretação e conclusões     | César Silveira |
| Documentação final             | Allan          |
| Revisão e envio final          | Marcos         |

---

Processo ETL Planejado

1. Extração: Importação dos dados brutos do arquivo CSV disponível no Kaggle.

2. Transformação: Tratamento de dados faltantes, remoção de duplicatas, padronização dos tipos e seleção das colunas relevantes para a análise.

3. Carga: Salvamento dos dados limpos em um formato adequado para a análise e visualização (CSV, Parquet etc.).

---

| Etapa                       | Descrição                                                           | Status         |
| --------------------------- | ------------------------------------------------------------------- | -------------- |
| 1. Repositório GitHub       | Estrutura inicial do projeto e documentação                         | ✅ Concluído    |
| 2. Seleção da base de dados | Escolha da base "Global Petrol Prices — Impact of 2026 US-Iran War" | ✅ Concluído    |
| 3. Limpeza dos dados        | Tratamento de valores nulos, duplicatas e padronização              | ⏳ Em andamento |
| 4. Análises                 | Desenvolvimento de análises exploratórias e testes de hipóteses     | ⏳ Pendente     |
| 5. Visualização             | Criação de dashboard e gráficos                                     | ⏳ Pendente     |
| 6. Resultados               | Interpretação dos resultados e conclusões                           | ⏳ Pendente     |
| 7. Documentação final       | Finalização do README e documentação complementar                   | ⏳ Pendente     |

---

| Etapa         | Descrição                                                                                                   | Status         |
| ------------- | ----------------------------------------------------------------------------------------------------------- | -------------- |
| Extração      | Importação dos dados brutos do CSV do Kaggle                                                                | ✅ Concluído    |
| Transformação | Tratamento de dados faltantes, remoção de duplicatas, padronização de tipos e seleção de colunas relevantes | ⏳ Em andamento |
| Carga         | Salvamento dos dados limpos em CSV ou Parquet para análise e visualização                                   | ⏳ Em andamento |

---
**📌 Transformações de Dados Planejadas (ETL – Transformação)**

Durante a etapa de Transformação, os seguintes processos serão aplicados:

**1. Tratamento de valores faltantes**

   ● Preencher valores nulos com média, mediana ou interpolação, dependendo da coluna.
   ● Remover linhas ou colunas irrelevantes com muitos dados faltantes.

**2. Remoção de duplicatas**

   ● Identificar e remover registros repetidos para evitar distorções.

**3. Padronização de tipos de dados**

   ● Converter colunas de datas para tipo datetime.
   ● Garantir que preços e indicadores numéricos estejam em formato numérico (float).

**4. Normalização e padronização de unidades**

   ● Preços convertidos para USD por litro para comparação global.
   ● Padronização de nomes de países e regiões (ex.: “USA” → “United States”).

**5. Criação de novas colunas**

   ● Diferença percentual dos preços mês a mês.
   ● Classificação por continente ou região geopolítica.
   ● Indicadores de impacto do conflito (ex.: aumento médio de preço após eventos específicos).

**6. Filtragem e seleção de colunas relevantes**

   ● Manter apenas as colunas necessárias para análises de preços, países, datas e indicadores geopolíticos.

---

**📌 Visualizações e Métricas do Dashboard**

O dashboard será desenvolvido para facilitar a interpretação dos impactos geopolíticos nos preços globais da gasolina, incluindo:

**Visualizações**

● Gráfico de linha temporal: Preço médio da gasolina ao longo do tempo por país ou região.
● Mapa mundial interativo (choropleth): Preços da gasolina por país, destacando variações regionais.
● Gráfico de barras comparativo: Comparação de preços antes e depois do conflito entre EUA e Irã.
● Boxplot ou violino: Distribuição de preços entre países ou regiões.
● Gráfico de dispersão: Relação entre preço da gasolina e indicadores econômicos ou geopolíticos.

**Métricas**

● Preço médio global e por região.
● Variação percentual de preços mês a mês.
● Países com maior aumento ou queda de preços.
● Média de impacto do conflito nos preços globais.
● Ranking de países com preços mais altos ou mais baixos.

---
Integrantes:

| Nome           | GitHub                                                   | Email                           |
| -------------- | -------------------------------------------------------- | ------------------------------- |
| César Silveira | [@CesarSilveira-96](https://github.com/CesarSilveira-96) | cesarsilveira35@gmail.com       |
| Allan          | [@slimaallan-ops](https://github.com/slimaallan-ops)     | slima.allan@gmail.com           |
| Marcos         | [@usuario](https://github.com/usuario)                   |    marcosbahia2605@gmail.com    |
| Paulo Mesquita | [@usuario](https://github.com/usuario)                   | paulo_henrique.dm@hotmail.com   |
| Ricardo Leão   | [@RicardoLeaoDEV](https://github.com/RicardoLeaoDEV)     | ricardoleao_1997@live.com       |

 ---

