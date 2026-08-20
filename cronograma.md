# 📅 Cronograma Detalhado de 30 Dias
## Análise de Dados & Business Intelligence

> Este documento contém o roteiro diário de estudos, dividido em **4 semanas**, com objetivos teóricos, tarefas práticas e entregáveis para cada dia.

---

## 📋 Sumário
1. [Semana 1 — 📗 Excel: Fundamentos, Organização e Análise](#semana-1--excel-fundamentos-organização-e-análise)
2. [Semana 2 — 🗄️ SQL: Consultas e Perguntas de Negócio](#semana-2--sql-consultas-e-perguntas-de-negócio)
3. [Semana 3 — 📊 Power BI & Power Query: Modelagem e DAX](#semana-3--power-bi--power-query-modelagem-e-dax)
4. [Semana 4 — 🐍 Python e Projeto Integrado de Portfólio](#semana-4--python-e-projeto-integrado-de-portfólio)

---

## Semana 1 — 📗 Excel: Fundamentos, Organização e Análise

**Objetivo da semana:** Dominar a estruturação, validação, limpeza e análise de dados em planilhas, criando uma primeira versão de relatório analítico.

### 🗓️ Dia 01: Introdução, Tipos de Dados e Atalhos Essenciais
- **Teoria (20 min):** O papel das planilhas em BI; tipos primitivos de dados (texto, número, data, booleano); referências relativas (`A1`) vs absolutas (`$A$1`).
- **Prática (30 min):** Criar uma planilha com a base bruta `vendas.csv`, ajustar larguras, formatar moedas/datas e treinar atalhos de navegação (`Ctrl + Setas`, `Ctrl + Shift + L`, `Ctrl + Espaço`).
- **Registro (10 min):** Preencher o Diário do Dia 01 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### 🗓️ Dia 02: Limpeza, Validação e Formatação Condicional
- **Teoria (20 min):** Técnicas de sanitização de dados; identificação de duplicatas; espaços excedentes; regras de validação de dados.
- **Prática (30 min):** Aplicar `Remover Duplicadas`, funções `ARRUMAR()` / `TRIM()`, `MAIÚSCULA()` / `MINÚSCULA()`, criar validação em lista suspensa para status do pedido e destacar valores anômalos com Formatação Condicional.
- **Registro (10 min):** Preencher o Diário do Dia 02 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### 🗓️ Dia 03: Fórmulas Lógicas e de Manipulação de Texto
- **Teoria (20 min):** Lógica booleana em planilhas: `SE()`, `SES()`, `E()`, `OU()`, `SEERRO()`; manipulação com `CONCATENAR()` / `TEXTO()` / `ESQUERDA()` / `DIREITA()`.
- **Prática (30 min):** Criar colunas calculadas na base de vendas: Classificação do cliente (ex.: se Faturamento > 1000 = "Premium"), extração do código do produto e tratamento de erros.
- **Registro (10 min):** Preencher o Diário do Dia 03 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### 🗓️ Dia 04: Funções de Busca e Referência (`PROCX`, `PROCV`, `ÍNDICE/CORRESP`)
- **Teoria (20 min):** Como cruzar tabelas no Excel; limitações do `PROCV()`; evolução e sintaxe do `PROCX()`; flexibilidade do par `ÍNDICE()` + `CORRESP()`.
- **Prática (30 min):** Cruzar a tabela de vendas com a tabela de cadastro de produtos/clientes para trazer categoria, custo unitário e cidade do comprador.
- **Registro (10 min):** Preencher o Diário do Dia 04 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### 🗓️ Dia 05: Funções Estatísticas e Agregações Condicionais
- **Teoria (20 min):** Agregações condicionais para relatórios resumidos: `SOMASE()`, `SOMASES()`, `CONT.SE()`, `CONT.SES()`, `MÉDIASE()`.
- **Prática (30 min):** Criar uma aba de resumo com indicadores-chave: Faturamento por Região, Quantidade de Pedidos por Vendedor e Ticket Médio por Categoria.
- **Registro (10 min):** Preencher o Diário do Dia 05 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### 🗓️ Dia 06: Tabelas Dinâmicas (Pivot Tables) e Segmentação
- **Teoria (20 min):** Arquitetura de Tabelas Dinâmicas: Linhas, Colunas, Valores e Filtros; Campos Calculados; Linha do Tempo e Segmentação de Dados (*Slicers*).
- **Prática (30 min):** Gerar matrizes dinâmicas de vendas por mês x categoria; criar campo calculado de Lucro Líquido (`Faturamento - Custo`); inserir segmentadores visuais interativos.
- **Registro (10 min):** Preencher o Diário do Dia 06 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### 🗓️ Dia 07: Gráficos Dinâmicos, Layout de Relatório e Fechamento da Semana
- **Teoria (20 min):** Princípios de design de relatórios em Excel: hierarquia visual, alinhamento, redução de ruído visual.
- **Prática (30 min):** Montar um painel de uma página com 3 KPIs em cartões, 2 gráficos dinâmicos (barras e linha temporal) e salvar como `excel/analise-vendas.xlsx`.
- **Registro (10 min):** Consolidar a revisão da Semana 1 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

---

## Semana 2 — 🗄️ SQL: Consultas e Perguntas de Negócio

**Objetivo da semana:** Aprender a consultar bancos de dados relacionais, filtrar, ordenar, agregar dados e unir tabelas para responder perguntas estratégicas.

### 🗓️ Dia 08: Introdução a Bancos de Dados e Consultas Básicas
- **Teoria (20 min):** Conceitos de SGBDs relacionais (PostgreSQL / SQLite / MySQL); sintaxe fundamental: `SELECT`, `FROM`, `WHERE`; operadores de comparação e lógicos (`=`, `<>`, `>`, `<`, `AND`, `OR`, `NOT`).
- **Prática (30 min):** Configurar ambiente (ex.: SQLite no DBeaver ou DuckDB / PostgreSQL local); criar a tabela de vendas e realizar as primeiras consultas com filtros específicos.
- **Registro (10 min):** Preencher o Diário do Dia 08 em `anotacoes/semana-02.md`.

### 🗓️ Dia 09: Ordenação, Limitação e Tratamento de Nulos
- **Teoria (20 min):** `ORDER BY` (ASC/DESC), `LIMIT` / `TOP`, `DISTINCT`, valores especiais `IS NULL` / `IS NOT NULL`, operadores `IN`, `BETWEEN` e `LIKE` (busca textual).
- **Prática (30 min):** Escrever consultas para encontrar o top 10 maiores pedidos, clientes únicos por estado e produtos que contenham termos específicos no nome.
- **Registro (10 min):** Preencher o Diário do Dia 09 em `anotacoes/semana-02.md`.

### 🗓️ Dia 10: Funções de Agregação e Agrupamento (`GROUP BY`)
- **Teoria (20 min):** Agregações: `COUNT()`, `SUM()`, `AVG()`, `MIN()`, `MAX()`; a mecânica do agrupamento com `GROUP BY`.
- **Prática (30 min):** Calcular faturamento total por categoria, ticket médio por método de pagamento e contagem de pedidos por mês.
- **Registro (10 min):** Preencher o Diário do Dia 10 em `anotacoes/semana-02.md`.

### 🗓️ Dia 11: Filtros de Agrupamento (`HAVING`) e Funções de Data/Texto
- **Teoria (20 min):** Diferença essencial entre `WHERE` (filtra linhas antes da agregação) e `HAVING` (filtra grupos após agregação); funções de data (`EXTRACT`, `DATEPART` ou `strftime`).
- **Prática (30 min):** Filtrar apenas vendedores com faturamento total superior a R$ 50.000; extrair ano e mês das datas de compra para calcular sazonalidade.
- **Registro (10 min):** Preencher o Diário do Dia 11 em `anotacoes/semana-02.md`.

### 🗓️ Dia 12: Modelagem Relacional e Junções Parte 1 (`INNER JOIN`)
- **Teoria (20 min):** Conceitos de Chave Primária (*PK*) e Chave Estrangeira (*FK*); integridade referencial; sintaxe do `INNER JOIN`.
- **Prática (30 min):** Conectar as tabelas de `vendas`, `clientes` e `produtos` para gerar uma visão unificada trazendo nome do cliente, nome do produto e preço unitário.
- **Registro (10 min):** Preencher o Diário do Dia 12 em `anotacoes/semana-02.md`.

### 🗓️ Dia 13: Junções Parte 2 (`LEFT JOIN`) e Subconsultas / CTEs
- **Teoria (20 min):** Diferenças entre `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`; introdução a *Common Table Expressions* (`WITH ... AS`) para consultas legíveis.
- **Prática (30 min):** Identificar produtos que nunca foram vendidos via `LEFT JOIN` com filtro `WHERE id_venda IS NULL`; escrever uma CTE para calcular o ranking de clientes.
- **Registro (10 min):** Preencher o Diário do Dia 13 em `anotacoes/semana-02.md`.

### 🗓️ Dia 14: Resolução de Perguntas de Negócio e Script Final
- **Teoria (20 min):** Boas práticas de formatação SQL, comentários de código e estruturação de scripts para portfólio.
- **Prática (30 min):** Resolver 5 perguntas clássicas de negócio e salvar o arquivo final documentado em `sql/consultas.sql`.
- **Registro (10 min):** Consolidar a revisão da Semana 2 em `anotacoes/semana-02.md`.

---

## Semana 3 — 📊 Power BI & Power Query: Modelagem e DAX

**Objetivo da semana:** Construir um modelo de dados profissional (Star Schema), criar medidas de inteligência de negócios com DAX e desenvolver um dashboard interativo.

### 🗓️ Dia 15: Conexão de Dados e ETL no Power Query
- **Teoria (20 min):** Interface do Power BI Desktop; conceito de ETL (*Extract, Transform, Load*); boas práticas no Power Query.
- **Prática (30 min):** Importar a base de vendas; renomear colunas, alterar tipos de dados, remover colunas desnecessárias e tratar valores nulos.
- **Registro (10 min):** Preencher o Diário do Dia 15 em `anotacoes/semana-03.md`.

### 🗓️ Dia 16: Transformações Avançadas no Power Query
- **Teoria (20 min):** Mesclar consultas (*Merge*) vs Acrescentar consultas (*Append*); Colunas Condicionais; Dinamização e Desdinamização (*Unpivot*).
- **Prática (30 min):** Normalizar tabelas de apoio; aplicar *Unpivot* se necessário; criar colunas condicionais para faixas de valores e carregar para o modelo de dados.
- **Registro (10 min):** Preencher o Diário do Dia 16 em `anotacoes/semana-03.md`.

### 🗓️ Dia 17: Modelagem Dimensional (*Star Schema*) e Tabela Calendário
- **Teoria (20 min):** O que é Esquema Estrela; Tabelas Fato (`fVendas`) vs Tabelas Dimensão (`dClientes`, `dProdutos`); cardinalidade (1:N); direção do filtro cruzado.
- **Prática (30 min):** Criar a tabela `dCalendario` em DAX (`CALENDARAUTO()` ou `CALENDAR()`); estabelecer relacionamentos entre a Fato e as Dimensões no Diagrama de Modelagem.
- **Registro (10 min):** Preencher o Diário do Dia 17 em `anotacoes/semana-03.md`.

### 🗓️ Dia 18: Fundamentos de DAX — Colunas Calculadas vs Medidas
- **Teoria (20 min):** Contexto de Linha vs Contexto de Filtro; por que priorizar Medidas Explícitas; funções base: `SUM()`, `COUNTROWS()`, `DISTINCTCOUNT()`, `DIVIDE()`.
- **Prática (30 min):** Criar tabela exclusiva de medidas (`_Medidas`); calcular: `Faturamento Total`, `Custo Total`, `Lucro Total`, `Margem de Lucro %`, `Total de Pedidos` e `Ticket Médio`.
- **Registro (10 min):** Preencher o Diário do Dia 18 em `anotacoes/semana-03.md`.

### 🗓️ Dia 19: DAX Intermediário — `CALCULATE` e Modificadores de Contexto
- **Teoria (20 min):** A função mais importante do Power BI: `CALCULATE()`; funções de alteração de filtro: `FILTER()`, `ALL()`, `VALUES()`, `ALLEXCEPT()`.
- **Prática (30 min):** Criar métricas: `Faturamento Região Sul`, `% de Participação no Total` (usando `ALL`), e `Vendas Acima da Média`.
- **Registro (10 min):** Preencher o Diário do Dia 19 em `anotacoes/semana-03.md`.

### 🗓️ Dia 20: Inteligência Temporal (*Time Intelligence*) em DAX
- **Teoria (20 min):** Requisitos para inteligência de tempo; funções: `SAMEPERIODLASTYEAR()`, `DATEADD()`, `TOTALYTD()`, `DATESYTD()`.
- **Prática (30 min):** Criar métricas de faturamento acumulado no ano (*YTD*), faturamento do mesmo período no ano anterior (*LY*) e crescimento percentual Ano contra Ano (*YoY %*).
- **Registro (10 min):** Preencher o Diário do Dia 20 em `anotacoes/semana-03.md`.

### 🗓️ Dia 21: Design de Dashboard, Storytelling e Interatividade
- **Teoria (20 min):** UX/UI para BI: alinhamento em grid, paleta de cores consistente (máx. 3 tons), contraste e navegação por abas/botões.
- **Prática (30 min):** Construir o relatório no Power BI Desktop com cartões de KPIs principais, gráfico de tendência temporal, gráfico de barras por categoria e filtros dinâmicos; salvar como `power-bi/dashboard.pbix`.
- **Registro (10 min):** Consolidar a revisão da Semana 3 em `anotacoes/semana-03.md`.

---

## Semana 4 — 🐍 Python e Projeto Integrado de Portfólio

**Objetivo da semana:** Utilizar Python e Pandas para análise estatística e visualização, consolidar todos os entregáveis e publicar o projeto no GitHub.

### 🗓️ Dia 22: Ambiente Python e Estruturas Fundamentais
- **Teoria (20 min):** Ambiente de desenvolvimento (Jupyter Notebook / Google Colab / VS Code); tipos de dados em Python; listas, dicionários e operadores.
- **Prática (30 min):** Criar notebook `analise_exploratoria.ipynb`; praticar iterações simples, manipulação de dicionários e importação de módulos (`import pandas as pd`).
- **Registro (10 min):** Preencher o Diário do Dia 22 em `anotacoes/semana-04.md`.

### 🗓️ Dia 23: Introdução à Biblioteca Pandas (Series e DataFrames)
- **Teoria (20 min):** Estrutura de dados do Pandas; carregamento com `pd.read_csv()`; métodos de inspeção inicial: `.head()`, `.tail()`, `.info()`, `.describe()`, `.shape`.
- **Prática (30 min):** Carregar a base `vendas.csv`, inspecionar tipos de colunas, verificar uso de memória e estatísticas descritivas básicas.
- **Registro (10 min):** Preencher o Diário do Dia 23 em `anotacoes/semana-04.md`.

### 🗓️ Dia 24: Limpeza e Manipulação com Pandas
- **Teoria (20 min):** Tratamento de valores ausentes (`.isna()`, `.fillna()`, `.dropna()`); conversão de tipos (`pd.to_datetime()`, `.astype()`); filtros booleanos.
- **Prática (30 min):** Converter datas, tratar registros com valores nulos, criar coluna de faturamento (`Quantidade * Preco_Unitario`) e aplicar filtros combinados.
- **Registro (10 min):** Preencher o Diário do Dia 24 em `anotacoes/semana-04.md`.

### 🗓️ Dia 25: Agrupamentos e Análise Agregada (`groupby` e `pivot_table`)
- **Teoria (20 min):** O padrão *Split-Apply-Combine*; método `.groupby()`; agregações múltiplas com `.agg()`; criação de tabelas dinâmicas com `.pivot_table()`.
- **Prática (30 min):** Calcular faturamento médio, mediana e soma por categoria; identificar os top 5 produtos mais vendidos e clientes com maior ticket.
- **Registro (10 min):** Preencher o Diário do Dia 25 em `anotacoes/semana-04.md`.

### 🗓️ Dia 26: Visualização de Dados com Matplotlib e Seaborn
- **Teoria (20 min):** Gráficos para análise exploratória: histogramas (distribuição), gráficos de linha (série temporal), barras (comparações) e dispersão/boxplot (outliers).
- **Prática (30 min):** Plotar a curva de vendas mensal, o histograma de preços de produtos e o boxplot de faturamento por categoria para detectar discrepâncias.
- **Registro (10 min):** Preencher o Diário do Dia 26 em `anotacoes/semana-04.md`.

### 🗓️ Dia 27: Análise Exploratória de Dados (EDA) Completa
- **Teoria (20 min):** Metodologia de EDA: levantamento de hipóteses de negócio, validação estatística e redação de conclusões preliminares.
- **Prática (30 min):** Finalizar o Jupyter Notebook com comentários explicativos (em Markdown), destacando pelo menos 3 insights acionáveis descobertos nos dados.
- **Registro (10 min):** Preencher o Diário do Dia 27 em `anotacoes/semana-04.md`.

### 🗓️ Dia 28: Integração dos Entregáveis do Projeto
- **Teoria (20 min):** Coerência analítica: verificar se os números apurados no Excel, SQL, Power BI e Python são consistentes entre si.
- **Prática (30 min):** Auditar os totais de faturamento e volume em todas as 4 ferramentas; organizar a estrutura de pastas do projeto final.
- **Registro (10 min):** Preencher o Diário do Dia 28 em `anotacoes/semana-04.md`.

### 🗓️ Dia 29: Estruturação do Repositório e Storytelling no GitHub
- **Teoria (20 min):** Como criar um README de portfólio atraente: descrição do problema de negócio, esteira de dados, imagens do dashboard, insights e conclusões.
- **Prática (30 min):** Tirar prints do Dashboard Power BI; redigir o `README.md` principal do repositório de portfólio; subir para o GitHub via Git.
- **Registro (10 min):** Preencher o Diário do Dia 29 em `anotacoes/semana-04.md`.

### 🗓️ Dia 30: Revisão Final, Autoavaliação e Próximos Passos
- **Teoria (20 min):** Reflexão sobre a curva de aprendizado; identificação de pontos fortes e áreas para aprofundamento futuro.
- **Prática (30 min):** Completar o checklist final de competências em [`README.md`](./README.md); publicar post de apresentação do projeto no LinkedIn.
- **Registro (10 min):** Escrever a conclusão final em `anotacoes/semana-04.md`.
