# ðŸ“… Cronograma Detalhado de 30 Dias
## AnÃ¡lise de Dados & Business Intelligence

> Este documento contÃ©m o roteiro diÃ¡rio de estudos, dividido em **4 semanas**, com objetivos teÃ³ricos, tarefas prÃ¡ticas e entregÃ¡veis para cada dia.

---

## ðŸ“‹ SumÃ¡rio
1. [Semana 1 â€” ðŸ“— Excel: Fundamentos, OrganizaÃ§Ã£o e AnÃ¡lise](#semana-1--excel-fundamentos-organizaÃ§Ã£o-e-anÃ¡lise)
2. [Semana 2 â€” ðŸ—„ï¸ SQL: Consultas e Perguntas de NegÃ³cio](#semana-2--sql-consultas-e-perguntas-de-negÃ³cio)
3. [Semana 3 â€” ðŸ“Š Power BI & Power Query: Modelagem e DAX](#semana-3--power-bi--power-query-modelagem-e-dax)
4. [Semana 4 â€” ðŸ Python e Projeto Integrado de PortfÃ³lio](#semana-4--python-e-projeto-integrado-de-portfÃ³lio)

---

## Semana 1 â€” ðŸ“— Excel: Fundamentos, OrganizaÃ§Ã£o e AnÃ¡lise

**Objetivo da semana:** Dominar a estruturaÃ§Ã£o, validaÃ§Ã£o, limpeza e anÃ¡lise de dados em planilhas, criando uma primeira versÃ£o de relatÃ³rio analÃ­tico.

### ðŸ—“ï¸ Dia 01: IntroduÃ§Ã£o, Tipos de Dados e Atalhos Essenciais
- **Teoria (20 min):** O papel das planilhas em BI; tipos primitivos de dados (texto, nÃºmero, data, booleano); referÃªncias relativas (`A1`) vs absolutas (`$A$1`).
- **PrÃ¡tica (30 min):** Criar uma planilha com a base bruta `vendas.csv`, ajustar larguras, formatar moedas/datas e treinar atalhos de navegaÃ§Ã£o (`Ctrl + Setas`, `Ctrl + Shift + L`, `Ctrl + EspaÃ§o`).
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 01 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### ðŸ—“ï¸ Dia 02: Limpeza, ValidaÃ§Ã£o e FormataÃ§Ã£o Condicional
- **Teoria (20 min):** TÃ©cnicas de sanitizaÃ§Ã£o de dados; identificaÃ§Ã£o de duplicatas; espaÃ§os excedentes; regras de validaÃ§Ã£o de dados.
- **PrÃ¡tica (30 min):** Aplicar `Remover Duplicadas`, funÃ§Ãµes `ARRUMAR()` / `TRIM()`, `MAIÃšSCULA()` / `MINÃšSCULA()`, criar validaÃ§Ã£o em lista suspensa para status do pedido e destacar valores anÃ´malos com FormataÃ§Ã£o Condicional.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 02 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### ðŸ—“ï¸ Dia 03: FÃ³rmulas LÃ³gicas e de ManipulaÃ§Ã£o de Texto
- **Teoria (20 min):** LÃ³gica booleana em planilhas: `SE()`, `SES()`, `E()`, `OU()`, `SEERRO()`; manipulaÃ§Ã£o com `CONCATENAR()` / `TEXTO()` / `ESQUERDA()` / `DIREITA()`.
- **PrÃ¡tica (30 min):** Criar colunas calculadas na base de vendas: ClassificaÃ§Ã£o do cliente (ex.: se Faturamento > 1000 = "Premium"), extraÃ§Ã£o do cÃ³digo do produto e tratamento de erros.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 03 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### ðŸ—“ï¸ Dia 04: FunÃ§Ãµes de Busca e ReferÃªncia (`PROCX`, `PROCV`, `ÃNDICE/CORRESP`)
- **Teoria (20 min):** Como cruzar tabelas no Excel; limitaÃ§Ãµes do `PROCV()`; evoluÃ§Ã£o e sintaxe do `PROCX()`; flexibilidade do par `ÃNDICE()` + `CORRESP()`.
- **PrÃ¡tica (30 min):** Cruzar a tabela de vendas com a tabela de cadastro de produtos/clientes para trazer categoria, custo unitÃ¡rio e cidade do comprador.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 04 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### ðŸ—“ï¸ Dia 05: FunÃ§Ãµes EstatÃ­sticas e AgregaÃ§Ãµes Condicionais
- **Teoria (20 min):** AgregaÃ§Ãµes condicionais para relatÃ³rios resumidos: `SOMASE()`, `SOMASES()`, `CONT.SE()`, `CONT.SES()`, `MÃ‰DIASE()`.
- **PrÃ¡tica (30 min):** Criar uma aba de resumo com indicadores-chave: Faturamento por RegiÃ£o, Quantidade de Pedidos por Vendedor e Ticket MÃ©dio por Categoria.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 05 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### ðŸ—“ï¸ Dia 06: Tabelas DinÃ¢micas (Pivot Tables) e SegmentaÃ§Ã£o
- **Teoria (20 min):** Arquitetura de Tabelas DinÃ¢micas: Linhas, Colunas, Valores e Filtros; Campos Calculados; Linha do Tempo e SegmentaÃ§Ã£o de Dados (*Slicers*).
- **PrÃ¡tica (30 min):** Gerar matrizes dinÃ¢micas de vendas por mÃªs x categoria; criar campo calculado de Lucro LÃ­quido (`Faturamento - Custo`); inserir segmentadores visuais interativos.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 06 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

### ðŸ—“ï¸ Dia 07: GrÃ¡ficos DinÃ¢micos, Layout de RelatÃ³rio e Fechamento da Semana
- **Teoria (20 min):** PrincÃ­pios de design de relatÃ³rios em Excel: hierarquia visual, alinhamento, reduÃ§Ã£o de ruÃ­do visual.
- **PrÃ¡tica (30 min):** Montar um painel de uma pÃ¡gina com 3 KPIs em cartÃµes, 2 grÃ¡ficos dinÃ¢micos (barras e linha temporal) e salvar como `excel/analise-vendas.xlsx`.
- **Registro (10 min):** Consolidar a revisÃ£o da Semana 1 em [`anotacoes/semana-01.md`](./anotacoes/semana-01.md).

---

## Semana 2 â€” ðŸ—„ï¸ SQL: Consultas e Perguntas de NegÃ³cio

**Objetivo da semana:** Aprender a consultar bancos de dados relacionais, filtrar, ordenar, agregar dados e unir tabelas para responder perguntas estratÃ©gicas.

### ðŸ—“ï¸ Dia 08: IntroduÃ§Ã£o a Bancos de Dados e Consultas BÃ¡sicas
- **Teoria (20 min):** Conceitos de SGBDs relacionais (PostgreSQL / SQLite / MySQL); sintaxe fundamental: `SELECT`, `FROM`, `WHERE`; operadores de comparaÃ§Ã£o e lÃ³gicos (`=`, `<>`, `>`, `<`, `AND`, `OR`, `NOT`).
- **PrÃ¡tica (30 min):** Configurar ambiente (ex.: SQLite no DBeaver ou DuckDB / PostgreSQL local); criar a tabela de vendas e realizar as primeiras consultas com filtros especÃ­ficos.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 08 em `anotacoes/semana-02.md`.

### ðŸ—“ï¸ Dia 09: OrdenaÃ§Ã£o, LimitaÃ§Ã£o e Tratamento de Nulos
- **Teoria (20 min):** `ORDER BY` (ASC/DESC), `LIMIT` / `TOP`, `DISTINCT`, valores especiais `IS NULL` / `IS NOT NULL`, operadores `IN`, `BETWEEN` e `LIKE` (busca textual).
- **PrÃ¡tica (30 min):** Escrever consultas para encontrar o top 10 maiores pedidos, clientes Ãºnicos por estado e produtos que contenham termos especÃ­ficos no nome.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 09 em `anotacoes/semana-02.md`.

### ðŸ—“ï¸ Dia 10: FunÃ§Ãµes de AgregaÃ§Ã£o e Agrupamento (`GROUP BY`)
- **Teoria (20 min):** AgregaÃ§Ãµes: `COUNT()`, `SUM()`, `AVG()`, `MIN()`, `MAX()`; a mecÃ¢nica do agrupamento com `GROUP BY`.
- **PrÃ¡tica (30 min):** Calcular faturamento total por categoria, ticket mÃ©dio por mÃ©todo de pagamento e contagem de pedidos por mÃªs.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 10 em `anotacoes/semana-02.md`.

### ðŸ—“ï¸ Dia 11: Filtros de Agrupamento (`HAVING`) e FunÃ§Ãµes de Data/Texto
- **Teoria (20 min):** DiferenÃ§a essencial entre `WHERE` (filtra linhas antes da agregaÃ§Ã£o) e `HAVING` (filtra grupos apÃ³s agregaÃ§Ã£o); funÃ§Ãµes de data (`EXTRACT`, `DATEPART` ou `strftime`).
- **PrÃ¡tica (30 min):** Filtrar apenas vendedores com faturamento total superior a R$ 50.000; extrair ano e mÃªs das datas de compra para calcular sazonalidade.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 11 em `anotacoes/semana-02.md`.

### ðŸ—“ï¸ Dia 12: Modelagem Relacional e JunÃ§Ãµes Parte 1 (`INNER JOIN`)
- **Teoria (20 min):** Conceitos de Chave PrimÃ¡ria (*PK*) e Chave Estrangeira (*FK*); integridade referencial; sintaxe do `INNER JOIN`.
- **PrÃ¡tica (30 min):** Conectar as tabelas de `vendas`, `clientes` e `produtos` para gerar uma visÃ£o unificada trazendo nome do cliente, nome do produto e preÃ§o unitÃ¡rio.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 12 em `anotacoes/semana-02.md`.

### ðŸ—“ï¸ Dia 13: JunÃ§Ãµes Parte 2 (`LEFT JOIN`) e Subconsultas / CTEs
- **Teoria (20 min):** DiferenÃ§as entre `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`; introduÃ§Ã£o a *Common Table Expressions* (`WITH ... AS`) para consultas legÃ­veis.
- **PrÃ¡tica (30 min):** Identificar produtos que nunca foram vendidos via `LEFT JOIN` com filtro `WHERE id_venda IS NULL`; escrever uma CTE para calcular o ranking de clientes.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 13 em `anotacoes/semana-02.md`.

### ðŸ—“ï¸ Dia 14: ResoluÃ§Ã£o de Perguntas de NegÃ³cio e Script Final
- **Teoria (20 min):** Boas prÃ¡ticas de formataÃ§Ã£o SQL, comentÃ¡rios de cÃ³digo e estruturaÃ§Ã£o de scripts para portfÃ³lio.
- **PrÃ¡tica (30 min):** Resolver 5 perguntas clÃ¡ssicas de negÃ³cio e salvar o arquivo final documentado em `sql/consultas.sql`.
- **Registro (10 min):** Consolidar a revisÃ£o da Semana 2 em `anotacoes/semana-02.md`.

---

## Semana 3 â€” ðŸ“Š Power BI & Power Query: Modelagem e DAX

**Objetivo da semana:** Construir um modelo de dados profissional (Star Schema), criar medidas de inteligÃªncia de negÃ³cios com DAX e desenvolver um dashboard interativo.

### ðŸ—“ï¸ Dia 15: ConexÃ£o de Dados e ETL no Power Query
- **Teoria (20 min):** Interface do Power BI Desktop; conceito de ETL (*Extract, Transform, Load*); boas prÃ¡ticas no Power Query.
- **PrÃ¡tica (30 min):** Importar a base de vendas; renomear colunas, alterar tipos de dados, remover colunas desnecessÃ¡rias e tratar valores nulos.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 15 em `anotacoes/semana-03.md`.

### ðŸ—“ï¸ Dia 16: TransformaÃ§Ãµes AvanÃ§adas no Power Query
- **Teoria (20 min):** Mesclar consultas (*Merge*) vs Acrescentar consultas (*Append*); Colunas Condicionais; DinamizaÃ§Ã£o e DesdinamizaÃ§Ã£o (*Unpivot*).
- **PrÃ¡tica (30 min):** Normalizar tabelas de apoio; aplicar *Unpivot* se necessÃ¡rio; criar colunas condicionais para faixas de valores e carregar para o modelo de dados.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 16 em `anotacoes/semana-03.md`.

### ðŸ—“ï¸ Dia 17: Modelagem Dimensional (*Star Schema*) e Tabela CalendÃ¡rio
- **Teoria (20 min):** O que Ã© Esquema Estrela; Tabelas Fato (`fVendas`) vs Tabelas DimensÃ£o (`dClientes`, `dProdutos`); cardinalidade (1:N); direÃ§Ã£o do filtro cruzado.
- **PrÃ¡tica (30 min):** Criar a tabela `dCalendario` em DAX (`CALENDARAUTO()` ou `CALENDAR()`); estabelecer relacionamentos entre a Fato e as DimensÃµes no Diagrama de Modelagem.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 17 em `anotacoes/semana-03.md`.

### ðŸ—“ï¸ Dia 18: Fundamentos de DAX â€” Colunas Calculadas vs Medidas
- **Teoria (20 min):** Contexto de Linha vs Contexto de Filtro; por que priorizar Medidas ExplÃ­citas; funÃ§Ãµes base: `SUM()`, `COUNTROWS()`, `DISTINCTCOUNT()`, `DIVIDE()`.
- **PrÃ¡tica (30 min):** Criar tabela exclusiva de medidas (`_Medidas`); calcular: `Faturamento Total`, `Custo Total`, `Lucro Total`, `Margem de Lucro %`, `Total de Pedidos` e `Ticket MÃ©dio`.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 18 em `anotacoes/semana-03.md`.

### ðŸ—“ï¸ Dia 19: DAX IntermediÃ¡rio â€” `CALCULATE` e Modificadores de Contexto
- **Teoria (20 min):** A funÃ§Ã£o mais importante do Power BI: `CALCULATE()`; funÃ§Ãµes de alteraÃ§Ã£o de filtro: `FILTER()`, `ALL()`, `VALUES()`, `ALLEXCEPT()`.
- **PrÃ¡tica (30 min):** Criar mÃ©tricas: `Faturamento RegiÃ£o Sul`, `% de ParticipaÃ§Ã£o no Total` (usando `ALL`), e `Vendas Acima da MÃ©dia`.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 19 em `anotacoes/semana-03.md`.

### ðŸ—“ï¸ Dia 20: InteligÃªncia Temporal (*Time Intelligence*) em DAX
- **Teoria (20 min):** Requisitos para inteligÃªncia de tempo; funÃ§Ãµes: `SAMEPERIODLASTYEAR()`, `DATEADD()`, `TOTALYTD()`, `DATESYTD()`.
- **PrÃ¡tica (30 min):** Criar mÃ©tricas de faturamento acumulado no ano (*YTD*), faturamento do mesmo perÃ­odo no ano anterior (*LY*) e crescimento percentual Ano contra Ano (*YoY %*).
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 20 em `anotacoes/semana-03.md`.

### ðŸ—“ï¸ Dia 21: Design de Dashboard, Storytelling e Interatividade
- **Teoria (20 min):** UX/UI para BI: alinhamento em grid, paleta de cores consistente (mÃ¡x. 3 tons), contraste e navegaÃ§Ã£o por abas/botÃµes.
- **PrÃ¡tica (30 min):** Construir o relatÃ³rio no Power BI Desktop com cartÃµes de KPIs principais, grÃ¡fico de tendÃªncia temporal, grÃ¡fico de barras por categoria e filtros dinÃ¢micos; salvar como `power-bi/dashboard.pbix`.
- **Registro (10 min):** Consolidar a revisÃ£o da Semana 3 em `anotacoes/semana-03.md`.

---

## Semana 4 â€” ðŸ Python e Projeto Integrado de PortfÃ³lio

**Objetivo da semana:** Utilizar Python e Pandas para anÃ¡lise estatÃ­stica e visualizaÃ§Ã£o, consolidar todos os entregÃ¡veis e publicar o projeto no GitHub.

### ðŸ—“ï¸ Dia 22: Ambiente Python e Estruturas Fundamentais
- **Teoria (20 min):** Ambiente de desenvolvimento (Jupyter Notebook / Google Colab / VS Code); tipos de dados em Python; listas, dicionÃ¡rios e operadores.
- **PrÃ¡tica (30 min):** Criar notebook `analise_exploratoria.ipynb`; praticar iteraÃ§Ãµes simples, manipulaÃ§Ã£o de dicionÃ¡rios e importaÃ§Ã£o de mÃ³dulos (`import pandas as pd`).
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 22 em `anotacoes/semana-04.md`.

### ðŸ—“ï¸ Dia 23: IntroduÃ§Ã£o Ã  Biblioteca Pandas (Series e DataFrames)
- **Teoria (20 min):** Estrutura de dados do Pandas; carregamento com `pd.read_csv()`; mÃ©todos de inspeÃ§Ã£o inicial: `.head()`, `.tail()`, `.info()`, `.describe()`, `.shape`.
- **PrÃ¡tica (30 min):** Carregar a base `vendas.csv`, inspecionar tipos de colunas, verificar uso de memÃ³ria e estatÃ­sticas descritivas bÃ¡sicas.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 23 em `anotacoes/semana-04.md`.

### ðŸ—“ï¸ Dia 24: Limpeza e ManipulaÃ§Ã£o com Pandas
- **Teoria (20 min):** Tratamento de valores ausentes (`.isna()`, `.fillna()`, `.dropna()`); conversÃ£o de tipos (`pd.to_datetime()`, `.astype()`); filtros booleanos.
- **PrÃ¡tica (30 min):** Converter datas, tratar registros com valores nulos, criar coluna de faturamento (`Quantidade * Preco_Unitario`) e aplicar filtros combinados.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 24 em `anotacoes/semana-04.md`.

### ðŸ—“ï¸ Dia 25: Agrupamentos e AnÃ¡lise Agregada (`groupby` e `pivot_table`)
- **Teoria (20 min):** O padrÃ£o *Split-Apply-Combine*; mÃ©todo `.groupby()`; agregaÃ§Ãµes mÃºltiplas com `.agg()`; criaÃ§Ã£o de tabelas dinÃ¢micas com `.pivot_table()`.
- **PrÃ¡tica (30 min):** Calcular faturamento mÃ©dio, mediana e soma por categoria; identificar os top 5 produtos mais vendidos e clientes com maior ticket.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 25 em `anotacoes/semana-04.md`.

### ðŸ—“ï¸ Dia 26: VisualizaÃ§Ã£o de Dados com Matplotlib e Seaborn
- **Teoria (20 min):** GrÃ¡ficos para anÃ¡lise exploratÃ³ria: histogramas (distribuiÃ§Ã£o), grÃ¡ficos de linha (sÃ©rie temporal), barras (comparaÃ§Ãµes) e dispersÃ£o/boxplot (outliers).
- **PrÃ¡tica (30 min):** Plotar a curva de vendas mensal, o histograma de preÃ§os de produtos e o boxplot de faturamento por categoria para detectar discrepÃ¢ncias.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 26 em `anotacoes/semana-04.md`.

### ðŸ—“ï¸ Dia 27: AnÃ¡lise ExploratÃ³ria de Dados (EDA) Completa
- **Teoria (20 min):** Metodologia de EDA: levantamento de hipÃ³teses de negÃ³cio, validaÃ§Ã£o estatÃ­stica e redaÃ§Ã£o de conclusÃµes preliminares.
- **PrÃ¡tica (30 min):** Finalizar o Jupyter Notebook com comentÃ¡rios explicativos (em Markdown), destacando pelo menos 3 insights acionÃ¡veis descobertos nos dados.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 27 em `anotacoes/semana-04.md`.

### ðŸ—“ï¸ Dia 28: IntegraÃ§Ã£o dos EntregÃ¡veis do Projeto
- **Teoria (20 min):** CoerÃªncia analÃ­tica: verificar se os nÃºmeros apurados no Excel, SQL, Power BI e Python sÃ£o consistentes entre si.
- **PrÃ¡tica (30 min):** Auditar os totais de faturamento e volume em todas as 4 ferramentas; organizar a estrutura de pastas do projeto final.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 28 em `anotacoes/semana-04.md`.

### ðŸ—“ï¸ Dia 29: EstruturaÃ§Ã£o do RepositÃ³rio e Storytelling no GitHub
- **Teoria (20 min):** Como criar um README de portfÃ³lio atraente: descriÃ§Ã£o do problema de negÃ³cio, esteira de dados, imagens do dashboard, insights e conclusÃµes.
- **PrÃ¡tica (30 min):** Tirar prints do Dashboard Power BI; redigir o `README.md` principal do repositÃ³rio de portfÃ³lio; subir para o GitHub via Git.
- **Registro (10 min):** Preencher o DiÃ¡rio do Dia 29 em `anotacoes/semana-04.md`.

### ðŸ—“ï¸ Dia 30: RevisÃ£o Final, AutoavaliaÃ§Ã£o e PrÃ³ximos Passos
- **Teoria (20 min):** ReflexÃ£o sobre a curva de aprendizado; identificaÃ§Ã£o de pontos fortes e Ã¡reas para aprofundamento futuro.
- **PrÃ¡tica (30 min):** Completar o checklist final de competÃªncias em [`README.md`](./README.md); publicar post de apresentaÃ§Ã£o do projeto no LinkedIn.
- **Registro (10 min):** Escrever a conclusÃ£o final em `anotacoes/semana-04.md`.