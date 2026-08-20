# 📚 Recursos por Semana

## Plano de Estudos de Análise de Dados & Business Intelligence

![Plano](https://img.shields.io/badge/plano-30%20dias-blue)
![Foco](https://img.shields.io/badge/foco-Dados%20%26%20BI-blueviolet)
![Materiais](https://img.shields.io/badge/materiais-Gmail%20%2B%20Drive-success)
![Método](https://img.shields.io/badge/método-teoria%20%2B%20prática-orange)

> Este arquivo organiza os principais **materiais de apoio** para cada etapa do plano de estudos, priorizando conteúdos já disponíveis no Gmail e no Google Drive.

---

# 🧭 Como Utilizar Este Arquivo

Os materiais abaixo devem funcionar como **apoio ao cronograma**, e não como uma lista de cursos que precisam ser concluídos integralmente.

A lógica do estudo será:

```text
Cronograma do dia
      ↓
Selecionar o conteúdo necessário
      ↓
Estudar o conceito
      ↓
Praticar na ferramenta
      ↓
Aplicar na base de vendas
      ↓
Registrar o aprendizado
```

> [!IMPORTANT]
> A prioridade é desenvolver competência prática. Concluir um curso inteiro é menos importante do que conseguir aplicar corretamente aquilo que foi estudado.

---

# 📗 Semana 1 | Excel para Análise de Dados

## 🎯 Objetivo da Semana

Aprender a utilizar o Excel não apenas como planilha, mas como uma ferramenta para **organizar, explorar, analisar e comunicar dados**.

---

## 📂 Materiais do Seu Contexto

### Santander / DIO | Excel com IA

Conteúdo localizado no Gmail relacionado ao uso de:

* Excel;
* produtividade;
* análise de dados;
* Inteligência Artificial aplicada ao trabalho.

### Brochura Analista de Dados

Arquivo:

```text
Brochura Analista de Dados.pdf
```

Disponível no Google Drive.

Utilize esse material principalmente para entender quais competências são normalmente associadas à formação de um **Analista de Dados**.

---

## 🔎 O Que Buscar nos Materiais

Priorize conteúdos relacionados a:

* [ ] Estruturação de bases
* [ ] Organização de linhas e colunas
* [ ] Tabelas do Excel
* [ ] Fórmulas condicionais
* [ ] Funções de busca
* [ ] Tabelas Dinâmicas
* [ ] Gráficos
* [ ] Indicadores
* [ ] Dashboards simples
* [ ] Uso de IA como apoio à produtividade

---

## 🧮 Funções Prioritárias

```text
SOMA
MÉDIA
MÁXIMO
MÍNIMO
CONT.SE
SOMASES
CONT.SES
SE
E
OU
SEERRO
PROCV
PROCX
```

> [!TIP]
> Não tente decorar todas as funções. Aprenda primeiro **qual problema cada função resolve**.

---

## 🧩 Aplicação no Projeto

Utilize a base de vendas para criar:

```text
Faturamento Total
Quantidade Vendida
Produto Mais Vendido
Venda por Categoria
Desempenho Mensal
Ticket Médio
Gráficos
Mini-dashboard
```

---

## 📦 Resultado Esperado

Ao final da semana:

```text
excel/
└── analise-vendas.xlsx
```

---

# 🗄️ Semana 2 | SQL

## 🎯 Objetivo da Semana

Aprender a transformar perguntas de negócio em **consultas estruturadas a um banco de dados**.

---

## 📂 Materiais do Seu Contexto

### Brochura Analista de Dados

A brochura apresenta **SQL** entre as competências fundamentais da trilha de análise de dados.

Utilize-a principalmente como referência para entender onde SQL se encaixa dentro da formação profissional.

### Materiais do Google Drive

Também existem roteiros e materiais que relacionam:

```text
Excel
SQL
Python
Power BI
```

como competências centrais para atuação em Dados e BI.

---

## 🔎 O Que Priorizar

### Fundamentos

* [ ] Estrutura de bancos de dados
* [ ] Tabelas
* [ ] Linhas e colunas
* [ ] Chaves
* [ ] Relacionamentos básicos

### Consultas

```sql
SELECT
FROM
WHERE
ORDER BY
DISTINCT
GROUP BY
HAVING
JOIN
```

### Funções de Agregação

```sql
COUNT()
SUM()
AVG()
MIN()
MAX()
```

---

## 🧠 Perguntas de Negócio

Utilize SQL para responder perguntas como:

```text
Qual produto vende mais?

Qual cliente compra mais?

Qual categoria gera maior faturamento?

Qual mês apresentou melhor desempenho?

Qual é o ticket médio?

Quais produtos apresentam poucas vendas?
```

---

## 💻 Exemplo

```sql
SELECT
    categoria,
    SUM(valor) AS faturamento
FROM vendas
GROUP BY categoria
ORDER BY faturamento DESC;
```

Esse tipo de consulta transforma uma pergunta de negócio em uma resposta baseada em dados:

```text
Pergunta
   ↓
Consulta SQL
   ↓
Resultado
   ↓
Interpretação
   ↓
Insight
```

---

## 📦 Resultado Esperado

```text
sql/
└── consultas.sql
```

---

# 📊 Semana 3 | Power BI + Power Query + DAX

## 🎯 Objetivo da Semana

Aprender a transformar dados brutos em um **modelo analítico capaz de gerar indicadores e dashboards**.

---

## 📂 Materiais do Seu Contexto

### Brochura Analista de Dados

A brochura inclui **Power BI** dentro das competências relacionadas à formação em análise de dados.

### Materiais do Google Drive

Outros conteúdos disponíveis conectam Power BI com:

```text
Excel
SQL
Python
```

dentro da mesma trilha profissional.

Isso ajuda a entender o Power BI não como ferramenta isolada, mas como uma etapa dentro de um processo maior de análise.

---

# 🔄 Power Query

## O Que Priorizar

* [ ] Importar dados
* [ ] Remover colunas
* [ ] Remover duplicatas
* [ ] Alterar tipos de dados
* [ ] Tratar valores nulos
* [ ] Corrigir erros
* [ ] Substituir valores
* [ ] Dividir colunas
* [ ] Mesclar colunas
* [ ] Filtrar registros
* [ ] Combinar arquivos
* [ ] Mesclar consultas

---

## 🧠 Papel do Power Query

Pense no Power Query como a etapa responsável por:

```text
Dados Brutos
     ↓
Limpeza
     ↓
Padronização
     ↓
Transformação
     ↓
Dados Prontos para Análise
```

---

# 📊 Power BI

## O Que Priorizar

* [ ] Importação de dados
* [ ] Modelagem
* [ ] Relacionamentos
* [ ] Medidas
* [ ] KPIs
* [ ] Gráficos
* [ ] Segmentadores
* [ ] Filtros
* [ ] Layout
* [ ] Construção de dashboards

---

## 📈 Indicadores Sugeridos

```text
Faturamento Total
Ticket Médio
Quantidade de Vendas
Quantidade de Clientes
Vendas por Categoria
Vendas por Região
Top Produtos
Evolução Mensal
```

---

# 🧮 DAX

## Funções Prioritárias

Comece por:

```text
SUM
COUNTROWS
DIVIDE
```

Depois avance para:

```text
CALCULATE
DISTINCTCOUNT
FILTER
IF
```

E somente depois aprofunde-se em:

```text
Inteligência de Tempo
```

---

## 💻 Exemplos

### Faturamento

```DAX
Faturamento =
SUM(Vendas[Valor])
```

### Quantidade de Vendas

```DAX
Quantidade Vendas =
COUNTROWS(Vendas)
```

### Ticket Médio

```DAX
Ticket Médio =
DIVIDE(
    [Faturamento],
    [Quantidade Vendas]
)
```

---

## 📦 Resultado Esperado

```text
power-bi/
└── dashboard.pbix
```

---

# 🐍 Semana 4 | Python para Análise de Dados

## 🎯 Objetivo da Semana

Aprender o Python necessário para começar a **manipular, explorar, analisar e visualizar dados**.

> [!NOTE]
> Nesta etapa, você não precisa aprender Python inteiro. O foco está apenas nos recursos que ajudam diretamente no trabalho com dados.

---

## 📂 Materiais do Seu Contexto

### Santander / DIO | Dados com Python e IA

Conteúdo localizado no Gmail relacionado a:

* Python;
* análise de dados;
* Inteligência Artificial;
* produtividade.

### Brochura Analista de Dados

O documento também contém referências a ferramentas como:

```text
Python
SQL
Jupyter Notebook
Matplotlib
```

---

## 🔎 O Que Priorizar

### Python Básico

* [ ] Variáveis
* [ ] Strings
* [ ] Números
* [ ] Listas
* [ ] Dicionários
* [ ] Condicionais
* [ ] Laços
* [ ] Funções

> Estude apenas o suficiente para conseguir avançar para análise de dados.

---

### Jupyter Notebook

Aprenda a:

* [ ] Criar notebooks
* [ ] Executar células
* [ ] Misturar código e documentação
* [ ] Organizar uma análise
* [ ] Registrar conclusões

---

### Pandas

Priorize:

* [ ] `read_csv()`
* [ ] `read_excel()`
* [ ] DataFrames
* [ ] Seleção de colunas
* [ ] Filtros
* [ ] Ordenação
* [ ] Valores nulos
* [ ] Duplicatas
* [ ] `groupby()`
* [ ] Funções de agregação

---

### Matplotlib

Comece utilizando gráficos simples:

```text
Barras
Linhas
Histogramas
Dispersão
```

---

## 🧰 Bibliotecas Prioritárias

```python
import pandas as pd
import matplotlib.pyplot as plt
```

---

## 💻 Exemplo

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

---

## 📦 Resultado Esperado

```text
python/
└── analise.ipynb
```

---

# 🧠 Estratégia de Uso dos Materiais

Não tente concluir todos os cursos, PDFs, vídeos ou materiais durante os 30 dias.

Utilize cada recurso para responder a uma necessidade específica do [`cronograma.md`](./cronograma.md).

A regra principal será:

```text
Aprender
   ↓
Praticar
   ↓
Aplicar
   ↓
Documentar
```

Ou, de forma mais completa:

```text
Aprender um conceito
        ↓
Praticar na ferramenta
        ↓
Aplicar no projeto de vendas
        ↓
Interpretar o resultado
        ↓
Registrar nas anotações
```

---

# 🚫 O Que Evitar

Durante os 30 dias, evite:

* assistir aulas durante horas sem praticar;
* tentar concluir vários cursos simultaneamente;
* estudar ferramentas sem produzir arquivos;
* copiar códigos sem entender o objetivo;
* trocar constantemente de base de dados;
* acumular materiais sem utilizá-los;
* gastar tempo excessivo procurando o curso "perfeito".

> [!WARNING]
> O excesso de materiais pode virar uma armadilha. O objetivo deste plano é aprender fazendo, não montar uma coleção infinita de cursos.

---

# 🔗 Projeto Integrado

Sempre que possível, utilize **a mesma base de vendas durante as quatro semanas**.

Isso permitirá observar como diferentes ferramentas resolvem partes distintas do mesmo problema.

| Ferramenta         | Papel no Projeto                  |
| ------------------ | --------------------------------- |
| 📗 **Excel**       | Exploração e indicadores iniciais |
| 🗄️ **SQL**        | Consultas e perguntas de negócio  |
| 🔄 **Power Query** | Limpeza e preparação              |
| 📊 **Power BI**    | Visualização e dashboard          |
| 🧮 **DAX**         | Métricas e indicadores            |
| 🐍 **Python**      | Análise complementar              |

---

## 🔁 Fluxo Completo

```text
📂 vendas.csv
      ↓
📗 Excel
Exploração inicial
      ↓
🗄️ SQL
Consultas
      ↓
🔄 Power Query
Tratamento
      ↓
📊 Power BI + DAX
Dashboard e KPIs
      ↓
🐍 Python
Análise complementar
      ↓
💡 Insights
      ↓
📝 Portfólio
```

---

# 📝 Avaliação dos Recursos

Ao concluir cada semana, registre quais materiais realmente contribuíram para seu aprendizado.

Utilize perguntas como:

```markdown
## Avaliação dos Recursos

### Materiais utilizados

- 

### O que mais ajudou

- 

### Conteúdos que foram difíceis

- 

### O que preciso revisar

- 

### Materiais que pretendo consultar novamente

- 
```

---

# ⭐ Sistema de Avaliação Opcional

Você também pode classificar cada recurso:

|  Nota | Avaliação                     |
| :---: | ----------------------------- |
|   ⭐   | Pouco útil                    |
|   ⭐⭐  | Útil em alguns pontos         |
|  ⭐⭐⭐  | Bom                           |
|  ⭐⭐⭐⭐ | Muito bom                     |
| ⭐⭐⭐⭐⭐ | Excelente para revisão futura |

Isso ajuda a transformar sua pasta de estudos em uma **biblioteca pessoal de recursos realmente úteis**, em vez de apenas um depósito de links.

---

# 📁 Organização Recomendada

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
├── README.md
├── cronograma.md
└── recursos.md
```

---

# 🎯 Princípio do Plano

> **Os recursos são ferramentas de apoio. O projeto é o centro do aprendizado.**

Durante os 30 dias, mantenha o foco no ciclo:

```text
Estudar
  ↓
Praticar
  ↓
Construir
  ↓
Errar
  ↓
Corrigir
  ↓
Documentar
  ↓
Evoluir
```

Ao final, o mais importante não será quantos cursos foram concluídos, mas quantas competências você consegue **demonstrar através do projeto construído**.

---

## 🔗 Navegação

[🏠 Voltar para o README](./README.md) | [📅 Ver cronograma completo](./cronograma.md) | [📝 Abrir anotações](./anotacoes/)
