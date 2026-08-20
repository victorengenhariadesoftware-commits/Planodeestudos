# 📅 Cronograma de 30 Dias

## Análise de Dados & Business Intelligence

![Duração](https://img.shields.io/badge/duração-30%20dias-informational)
![Carga Horária](https://img.shields.io/badge/carga%20horária-1h%2Fdia-success)
![Foco](https://img.shields.io/badge/foco-prático-blueviolet)
![Projeto](https://img.shields.io/badge/projeto-portfólio-orange)

> Cronograma prático de 30 dias para desenvolver fundamentos em **Análise de Dados e Business Intelligence**, avançando de Excel e SQL até Power BI, DAX e Python.

---

# 🗺️ Visão Geral

O cronograma está dividido em quatro etapas progressivas:

| Semana | Tecnologia  | Objetivo                                           |
| :----: | ----------- | -------------------------------------------------- |
| **01** | 📗 Excel    | Explorar, organizar e analisar dados               |
| **02** | 🗄️ SQL     | Consultar dados e responder perguntas de negócio   |
| **03** | 📊 Power BI | Transformar dados em indicadores e dashboards      |
| **04** | 🐍 Python   | Explorar dados e consolidar o projeto de portfólio |

```text
Excel
  ↓
SQL
  ↓
Power Query
  ↓
Power BI + DAX
  ↓
Python
  ↓
Projeto de Portfólio
```

> [!IMPORTANT]
> O objetivo não é apenas concluir aulas. Cada semana deve gerar uma entrega prática que será incorporada ao projeto final.

---

# 📗 Semana 1 | Excel para Análise de Dados

## 🎯 Meta

Sair do uso convencional do Excel e começar a utilizá-lo como uma **ferramenta de análise de dados**.

Ao final da semana, você deverá conseguir estruturar uma base, calcular indicadores, relacionar informações e apresentar resultados visualmente.

---

## 📆 Cronograma

|   Dia  | Conteúdo                                        | Prática                                           |
| :----: | ----------------------------------------------- | ------------------------------------------------- |
| **01** | Estrutura de dados, linhas, colunas e tabelas   | Transformar uma base comum em **Tabela do Excel** |
| **02** | `SOMA`, `MÉDIA`, `MÁXIMO`, `MÍNIMO` e `CONT.SE` | Criar indicadores básicos                         |
| **03** | `SOMASES` e `CONT.SES`                          | Analisar vendas por categoria, produto ou período |
| **04** | `SE`, `E`, `OU` e `SEERRO`                      | Criar classificações e regras de negócio          |
| **05** | `PROCV` e `PROCX`                               | Relacionar informações entre duas bases           |
| **06** | Tabelas Dinâmicas                               | Criar uma análise gerencial                       |
| **07** | Gráficos + revisão                              | Construir um mini-dashboard                       |

---

## 🧩 Projeto da Semana

Criar uma **planilha de análise de vendas** contendo:

* [ ] Faturamento total
* [ ] Quantidade vendida
* [ ] Produto mais vendido
* [ ] Desempenho mensal
* [ ] Faturamento por categoria
* [ ] Tabela dinâmica
* [ ] Gráficos
* [ ] Mini-dashboard

### 📦 Entrega sugerida

```text
excel/
└── analise-vendas.xlsx
```

---

# 🗄️ Semana 2 | SQL

## 🎯 Meta

Aprender a transformar perguntas de negócio em **consultas SQL**.

A ideia é começar a raciocinar sobre dados armazenados em tabelas e aprender a extrair apenas as informações necessárias.

---

## 📆 Cronograma

|   Dia  | Conteúdo                                  | Prática                          |
| :----: | ----------------------------------------- | -------------------------------- |
| **08** | Banco de dados, tabelas, linhas e colunas | Explorar a estrutura de uma base |
| **09** | `SELECT` e `FROM`                         | Criar consultas simples          |
| **10** | `WHERE`, `AND`, `OR` e `IN`               | Filtrar informações              |
| **11** | `ORDER BY`, `LIMIT` e `DISTINCT`          | Organizar e limitar resultados   |
| **12** | `COUNT`, `SUM`, `AVG`, `MIN` e `MAX`      | Criar métricas                   |
| **13** | `GROUP BY` e `HAVING`                     | Construir análises agrupadas     |
| **14** | `JOIN`                                    | Relacionar duas tabelas          |

---

## ❓ Perguntas de Negócio

Durante a semana, utilize SQL para responder perguntas como:

* Qual produto vende mais?
* Qual cliente possui maior volume de compras?
* Qual mês apresentou maior faturamento?
* Qual categoria possui maior ticket médio?
* Quais produtos apresentam poucas vendas?
* Qual região gera maior receita?
* Quais clientes compram com maior frequência?

---

## 💻 Exemplo de Consulta

```sql
SELECT
    categoria,
    SUM(valor) AS faturamento
FROM vendas
GROUP BY categoria
ORDER BY faturamento DESC;
```

### O que essa consulta faz?

```text
SELECT      → escolhe as informações
SUM         → soma os valores
FROM        → define a tabela
GROUP BY    → agrupa por categoria
ORDER BY    → organiza o resultado
```

---

## 🧩 Projeto da Semana

Criar um arquivo contendo consultas que respondam a diferentes perguntas de negócio.

### 📦 Entrega sugerida

```text
sql/
└── consultas.sql
```

> [!TIP]
> Adicione comentários no arquivo `.sql` explicando qual pergunta cada consulta pretende responder.

Exemplo:

```sql
-- Qual categoria possui maior faturamento?

SELECT
    categoria,
    SUM(valor) AS faturamento
FROM vendas
GROUP BY categoria
ORDER BY faturamento DESC;
```

---

# 📊 Semana 3 | Power BI + Power Query + DAX

## 🎯 Meta

Transformar dados brutos em um **dashboard de Business Intelligence**.

Nesta semana, o foco passa a ser o fluxo completo:

```text
Importação
    ↓
Limpeza
    ↓
Transformação
    ↓
Modelagem
    ↓
Métricas
    ↓
Visualizações
    ↓
Dashboard
```

---

## 📆 Cronograma

|   Dia  | Conteúdo                    | Prática                            |
| :----: | --------------------------- | ---------------------------------- |
| **15** | Interface do Power BI       | Importar uma base                  |
| **16** | Power Query                 | Limpar e transformar dados         |
| **17** | Tipos de dados e tratamento | Corrigir erros, nulos e duplicatas |
| **18** | Modelagem de dados          | Criar relacionamentos              |
| **19** | DAX básico                  | Criar medidas                      |
| **20** | KPIs e visualizações        | Construir gráficos e indicadores   |
| **21** | Dashboard                   | Montar o projeto completo          |

---

# 🔄 Power Query | Prioridades

Durante os primeiros contatos com Power Query, concentre-se nas operações mais utilizadas no trabalho cotidiano.

* [ ] Remover colunas
* [ ] Renomear colunas
* [ ] Alterar tipos de dados
* [ ] Remover duplicatas
* [ ] Substituir valores
* [ ] Tratar valores nulos
* [ ] Dividir colunas
* [ ] Mesclar colunas
* [ ] Filtrar registros
* [ ] Combinar arquivos
* [ ] Mesclar consultas

> [!NOTE]
> Pense no Power Query como a etapa responsável por transformar uma base bagunçada em uma base confiável para análise.

---

# 🧮 DAX | Medidas Iniciais

## Faturamento

```DAX
Faturamento =
SUM(Vendas[Valor])
```

## Quantidade de Vendas

```DAX
Quantidade Vendas =
COUNTROWS(Vendas)
```

## Ticket Médio

```DAX
Ticket Médio =
DIVIDE(
    [Faturamento],
    [Quantidade Vendas]
)
```

---

## 📚 Próximas Funções DAX

Depois de dominar medidas simples, avance gradualmente para:

```text
CALCULATE
DISTINCTCOUNT
FILTER
IF
DIVIDE
SUMX
RELATED
```

Depois, comece a estudar **inteligência de tempo**, com funções voltadas para comparação entre períodos.

Exemplos:

```text
Faturamento do mês
Faturamento do mês anterior
Crescimento %
Faturamento acumulado
Comparação ano contra ano
```

---

## 🧩 Projeto da Semana

Criar um **Dashboard Comercial** contendo:

* [ ] Faturamento total
* [ ] Ticket médio
* [ ] Quantidade de vendas
* [ ] Evolução mensal
* [ ] Vendas por categoria
* [ ] Vendas por região
* [ ] Top produtos
* [ ] Segmentadores de dados
* [ ] KPIs

### 📦 Entrega sugerida

```text
power-bi/
└── dashboard.pbix
```

---

# 🐍 Semana 4 | Python + Projeto Integrado

## 🎯 Meta

Utilizar Python como ferramenta analítica para **manipular, explorar e visualizar dados**.

Nesta etapa, o objetivo não é aprender toda a linguagem Python, mas desenvolver o suficiente para começar a trabalhar com dados.

---

## 📆 Cronograma

|   Dia  | Conteúdo          | Prática                             |
| :----: | ----------------- | ----------------------------------- |
| **22** | Python básico     | Variáveis, listas e funções         |
| **23** | Jupyter Notebook  | Criar e organizar um notebook       |
| **24** | Pandas            | Ler arquivos CSV e Excel            |
| **25** | DataFrames        | Selecionar, ordenar e filtrar dados |
| **26** | Limpeza           | Tratar nulos e duplicados           |
| **27** | `groupby()`       | Criar análises agrupadas            |
| **28** | Matplotlib        | Criar visualizações                 |
| **29** | Projeto integrado | Analisar a base completa            |
| **30** | Portfólio         | Documentar resultados e conclusões  |

---

# 📚 Bibliotecas Prioritárias

Comece apenas com duas bibliotecas principais:

```python
import pandas as pd
import matplotlib.pyplot as plt
```

### Pandas

Responsável principalmente por:

```text
Importar dados
Limpar dados
Filtrar registros
Agrupar informações
Criar métricas
Explorar bases
```

### Matplotlib

Responsável principalmente por:

```text
Gráficos de barras
Gráficos de linhas
Histogramas
Visualizações exploratórias
```

---

# 💻 Exemplo com Pandas

```python
import pandas as pd

df = pd.read_csv("vendas.csv")

faturamento_por_categoria = (
    df.groupby("categoria")["valor"]
      .sum()
      .sort_values(ascending=False)
)

print(faturamento_por_categoria)
```

### Fluxo da análise

```text
vendas.csv
    ↓
pd.read_csv()
    ↓
DataFrame
    ↓
groupby()
    ↓
sum()
    ↓
Análise por categoria
```

---

# 🚀 Dias 29 e 30 | Projeto Integrado

Nos dois últimos dias, todas as etapas estudadas durante o mês devem se conectar.

## Fluxo do Projeto

```text
📂 vendas.csv
      ↓
📗 Excel
Exploração inicial
      ↓
🗄️ SQL
Consultas de negócio
      ↓
🔄 Power Query
Tratamento dos dados
      ↓
📊 Power BI + DAX
Indicadores e dashboard
      ↓
🐍 Python
Análise complementar
      ↓
📝 README
Insights e conclusões
```

---

## 📌 Dia 29 | Análise

Analise a base utilizando as ferramentas estudadas.

Tente responder perguntas como:

* Qual período apresentou maior faturamento?
* Quais são os produtos mais vendidos?
* Quais categorias geram mais receita?
* Existe alguma tendência ao longo dos meses?
* Quais produtos possuem baixo desempenho?
* Qual é o ticket médio?
* Existem valores fora do padrão?

---

## 📌 Dia 30 | Portfólio

Organize e documente todo o projeto.

### Checklist

* [ ] Organizar os arquivos do projeto
* [ ] Revisar as consultas SQL
* [ ] Revisar o dashboard
* [ ] Revisar o notebook Python
* [ ] Selecionar os principais gráficos
* [ ] Registrar os principais insights
* [ ] Explicar as decisões tomadas
* [ ] Atualizar o `README.md`
* [ ] Publicar o projeto no GitHub

---

# ⏱️ Rotina Diária

Para uma rotina de **1 hora por dia**:

|      Tempo | Atividade                       |
| ---------: | ------------------------------- |
| **20 min** | 📚 Teoria, documentação ou aula |
| **30 min** | 💻 Exercícios práticos          |
| **10 min** | 📝 Registro do aprendizado      |

> [!TIP]
> Sempre que possível, passe mais tempo praticando do que assistindo aulas. Em dados, conhecimento começa a ganhar forma quando você coloca a mão na base.

---

# 📝 Registro de Aprendizado

Após cada dia de estudo, registre:

```markdown
## Dia XX

### O que estudei

### O que pratiquei

### O que aprendi

### Dificuldades

### Próximo passo
```

Utilize os arquivos da pasta:

```text
anotacoes/
```

Exemplo:

```text
anotacoes/
├── semana-01.md
├── semana-02.md
├── semana-03.md
└── semana-04.md
```

---

# 📈 Acompanhamento do Progresso

## Semana 1

* [ ] Dia 01
* [ ] Dia 02
* [ ] Dia 03
* [ ] Dia 04
* [ ] Dia 05
* [ ] Dia 06
* [ ] Dia 07

## Semana 2

* [ ] Dia 08
* [ ] Dia 09
* [ ] Dia 10
* [ ] Dia 11
* [ ] Dia 12
* [ ] Dia 13
* [ ] Dia 14

## Semana 3

* [ ] Dia 15
* [ ] Dia 16
* [ ] Dia 17
* [ ] Dia 18
* [ ] Dia 19
* [ ] Dia 20
* [ ] Dia 21

## Semana 4

* [ ] Dia 22
* [ ] Dia 23
* [ ] Dia 24
* [ ] Dia 25
* [ ] Dia 26
* [ ] Dia 27
* [ ] Dia 28
* [ ] Dia 29
* [ ] Dia 30

---

# 🏁 Resultado Esperado

Ao concluir o cronograma, você deverá possuir um pequeno projeto estruturado desta forma:

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
│   └── analise.ipynb
│
├── anotacoes/
│   ├── semana-01.md
│   ├── semana-02.md
│   ├── semana-03.md
│   └── semana-04.md
│
├── cronograma.md
├── recursos.md
└── README.md
```

---

# 🎯 Fechamento do Dia 30

O projeto final deve reunir:

**Excel + SQL + Power Query + Power BI + DAX + Python**

em torno de uma mesma base de dados.

O objetivo não é terminar o mês apenas com uma lista de cursos concluídos.

O objetivo é conseguir mostrar:

```text
O problema
    ↓
Os dados
    ↓
O tratamento
    ↓
A análise
    ↓
Os indicadores
    ↓
A visualização
    ↓
Os insights
    ↓
A conclusão
```

> [!IMPORTANT]
> Ao final dos 30 dias, seu GitHub deve começar a funcionar como uma **evidência prática daquilo que você sabe fazer**, e não apenas como um local para armazenar arquivos.

---

## 🔗 Navegação

[⬅️ Voltar para o README](./README.md) | [📚 Ver recursos de estudo](./recursos.md)
