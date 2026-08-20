# 📊 Plano de Estudos de 30 Dias
## Análise de Dados & Business Intelligence

![Status](https://img.shields.io/badge/status-em%20andamento-blue)
![Duração](https://img.shields.io/badge/duração-30%20dias-informational)
![Carga Horária](https://img.shields.io/badge/carga%20horária-1h%2Fdia-success)
![Nível](https://img.shields.io/badge/nível-iniciante-brightgreen)

> Um plano prático de 30 dias para desenvolver fundamentos em **Análise de Dados e Business Intelligence**, integrando Excel, SQL, Power BI e Python em um único projeto de portfólio.

---

## 🎯 Objetivo

Desenvolver uma base prática para começar a atuar em **Análise de Dados / Business Intelligence**, aprendendo a:

- Coletar e importar dados;
- Organizar e estruturar informações;
- Consultar e filtrar bases relacionais com SQL;
- Limpar e transformar dados via ETL;
- Construir indicadores-chave de desempenho (KPIs);
- Analisar resultados e identificar padrões;
- Criar dashboards dinâmicos e intuitivos;
- Comunicar insights orientados a decisões de negócio.

Ao final dos 30 dias, o objetivo é construir um projeto de portfólio completo seguindo uma esteira analítica profissional:

```text
Dados Brutos
    ↓
Tratamento & Limpeza
    ↓
Exploração & Análise
    ↓
Construção de Indicadores
    ↓
Dashboard Interativo
    ↓
Conclusões & Storytelling
```

---

## 🧭 Trilha de Aprendizagem

A ordem de estudo foi estruturada para que cada ferramenta complemente a anterior de maneira lógica e progressiva.

| Etapa | Tecnologia | Objetivo |
| :---: | :--- | :--- |
| **01** | 📗 **Excel** | Explorar, organizar, tabular e validar dados |
| **02** | 🗄️ **SQL** | Consultar, filtrar, agregar e manipular dados relacionais |
| **03** | 📊 **Power BI & Power Query** | Modelar relacionamentos, criar métricas DAX e dashboards |
| **04** | 🐍 **Python & Pandas** | Automatizar, analisar estatísticas e visualizar dados |

### Fluxo de Aplicação

```text
Excel (Visão inicial da base)
  ↓
SQL (Consultas, filtros e agregações)
  ↓
Power Query (Tratamento ETL automatizado)
  ↓
Power BI + DAX (Modelagem dimensional e Métricas)
  ↓
Python (Análise Exploratória e Automação)
```

> [!IMPORTANT]
> A proposta não é estudar ferramentas de forma isolada, mas compreender como elas operam integradas em um fluxo real de trabalho corporativo.

---

## 📅 Estrutura dos 30 Dias

| Semana | Tema Principal | Foco Prático |
| :---: | :--- | :--- |
| [**Semana 1**](./cronograma.md#semana-1--excel-fundamentos-organização-e-análise) | 📗 Excel | Estruturação, fórmulas lógicas/busca, tabelas dinâmicas |
| [**Semana 2**](./cronograma.md#semana-2--sql-consultas-e-perguntas-de-negócio) | 🗄️ SQL | Consultas relacionais, agregações, filtros e JOINs |
| [**Semana 3**](./cronograma.md#semana-3--power-bi--power-query-modelagem-e-dax) | 📊 Power BI | ETL no Power Query, esquema estrela, DAX e dashboards |
| [**Semana 4**](./cronograma.md#semana-4--python-e-projeto-integrado-de-portfólio) | 🐍 Python | Pandas, visualização gráfica, EDA e portfólio no GitHub |

📌 Para acessar o roteiro detalhado de cada dia, consulte o [`cronograma.md`](./cronograma.md).

---

## ⏱️ Rotina Diária

**Carga horária sugerida:** 1 hora por dia

| Tempo | Atividade |
| :---: | :--- |
| **20 min** | 📚 Teoria, documentação oficial ou videoaula conceitual |
| **30 min** | 💻 Prática direta, escrita de código, fórmulas e testes |
| **10 min** | 📝 Registro no diário de bordo semanal |

### Diário de Bordo

Ao final de cada sessão, documente:
* Conteúdo estudado;
* Exercícios e experimentos práticos executados;
* Dificuldades, erros e soluções encontradas;
* Principais sacadas (*insights*);
* Planejamento para o dia seguinte.

Os registros são salvos na pasta [`anotacoes/`](./anotacoes/).

---

## 🚀 Projeto Final Integrado

Durante os 30 dias, recomenda-se a utilização de uma **mesma base de dados de negócio** (ex.: base transacional de vendas/e-commerce), acompanhando o dado por todas as ferramentas:

### 1. 📗 Excel
* Exploração inicial do arquivo bruto;
* Formatação, tratamento de tipos e remoção de duplicadas;
* Fórmulas (`PROCX`, `SOMASES`, `SE`);
* Tabelas e Gráficos Dinâmicos com segmentação de dados.

### 2. 🗄️ SQL
* Criação de tabelas e importação da base;
* Consultas para responder perguntas estratégicas de negócio;
* Cálculos de faturamento, ticket médio e volume por região;
* Uso de `GROUP BY`, `HAVING`, `JOIN` e CTEs.

### 3. 🔄 Power Query & 📊 Power BI
* Conexão e transformação automatizada dos dados;
* Construção do modelo dimensional (Fato Vendas + Dimensões Cliente, Produto, Calendário);
* Métricas em DAX (`CALCULATE`, `SAMEPERIODLASTYEAR`, margens percentuais);
* Dashboard interativo com visual limpo e storytelling.

### 4. 🐍 Python (Pandas & Matplotlib/Seaborn)
* Leitura da base e inspeção de dados ausentes;
* Análise estatística descritiva (médias, medianas, desvio padrão, quartis);
* Visualização de distribuições e correlações;
* Geração de conclusões finais estruturadas em Jupyter Notebook.

---

## 🗂️ Estrutura Recomendada do Repositório

```text
analise-vendas/
│
├── dados/
│   └── vendas.csv
│
├── excel/
│   └── analise-vendas.xlsx
│
├── sql/
│   └── consultas.sql
│
├── power-bi/
│   └── dashboard.pbix
│
├── python/
│   └── analise_exploratoria.ipynb
│
├── anotacoes/
│   ├── semana-01.md
│   ├── semana-02.md
│   ├── semana-03.md
│   └── semana-04.md
│
├── cronograma.md
├── recursos.md
│
└── README.md
```

---

## ✅ Competências Esperadas

- [ ] Entender e interpretar a modelagem de uma base transacional.
- [ ] Diagnosticar problemas de qualidade e consistência de dados.
- [ ] Aplicar fórmulas analíticas e tabelas dinâmicas no Excel.
- [ ] Escrever consultas SQL eficientes com agregações e junções.
- [ ] Executar pipelines de ETL com Power Query.
- [ ] Modelar esquemas dimensionais (Star Schema) no Power BI.
- [ ] Escrever medidas de inteligência de negócios com DAX.
- [ ] Desenvolver dashboards com navegação intuitiva e foco em KPIs.
- [ ] Manipular e agrupar DataFrames utilizando Python/Pandas.
- [ ] Criar gráficos para análise exploratória de dados (EDA).
- [ ] Sintetizar descobertas em recomendações práticas de negócios.
- [ ] Publicar e documentar o projeto de forma profissional no GitHub.

---

## 📁 Arquivos do Plano

| Arquivo | Descrição |
| :--- | :--- |
| [`README.md`](./README.md) | Visão geral do plano, metodologia e projeto integrado |
| [`cronograma.md`](./cronograma.md) | Roteiro detalhado dos 30 dias (teoria + prática) |
| [`recursos.md`](./recursos.md) | Links, documentações, cursos gratuitos e bases de dados |
| [`anotacoes/`](./anotacoes/) | Diários de bordo e anotações diárias organizadas por semana |

---

## 🛠️ Tecnologias Utilizadas

<p>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
</p>

---

## 📈 Painel de Progresso

```text
Semana 1 | Excel                     [ ░░░░░░░░░░ ]  0%
Semana 2 | SQL                       [ ░░░░░░░░░░ ]  0%
Semana 3 | Power BI + Power Query    [ ░░░░░░░░░░ ]  0%
Semana 4 | Python + Projeto Final    [ ░░░░░░░░░░ ]  0%
```

---

## 💡 Filosofia de Execução

> **Aprender → Praticar → Documentar → Construir → Publicar**

O objetivo principal não é apenas absorver conteúdo passivamente, mas construir evidências palpáveis de competência prática ao longo de cada um dos 30 dias.
