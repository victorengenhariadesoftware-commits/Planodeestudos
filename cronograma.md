\# Cronograma de 30 Dias | Análise de Dados e BI

\#\# Semana 1 | Excel para Análise de Dados

\*\*Meta:\*\* sair do uso convencional do Excel e começar a utilizá-lo como ferramenta analítica.

| Dia | Conteúdo | Prática |  
|---|---|---|  
| 1 | Estrutura de dados, linhas, colunas e tabelas | Transformar uma base em Tabela |  
| 2 | SOMA, MÉDIA, MÁXIMO, MÍNIMO e CONT.SE | Criar indicadores |  
| 3 | SOMASES e CONT.SES | Analisar vendas e categorias |  
| 4 | SE, E, OU e SEERRO | Criar classificações |  
| 5 | PROCV e PROCX | Relacionar duas bases |  
| 6 | Tabelas Dinâmicas | Criar análise gerencial |  
| 7 | Gráficos \+ revisão | Criar mini-dashboard |

\*\*Projeto da semana:\*\* criar uma planilha de vendas contendo faturamento, quantidade vendida, produto mais vendido, desempenho mensal e gráfico por categoria.

\#\# Semana 2 | SQL

\*\*Meta:\*\* aprender a fazer perguntas para um banco de dados.

| Dia | Conteúdo | Prática |  
|---|---|---|  
| 8 | Banco de dados, tabelas, linhas e colunas | Explorar uma base |  
| 9 | SELECT e FROM | Consultas simples |  
| 10 | WHERE, AND, OR e IN | Filtrar informações |  
| 11 | ORDER BY, LIMIT e DISTINCT | Organizar resultados |  
| 12 | COUNT, SUM, AVG, MIN e MAX | Criar métricas |  
| 13 | GROUP BY e HAVING | Análises agrupadas |  
| 14 | JOIN | Relacionar duas tabelas |

\*\*Projeto da semana:\*\* responder com SQL perguntas como:

\- Qual produto vende mais?  
\- Qual cliente compra mais?  
\- Qual mês teve maior faturamento?  
\- Qual categoria apresenta maior ticket médio?  
\- Quais produtos possuem poucas vendas?

Exemplo:

\`\`\`sql  
SELECT  
    categoria,  
    SUM(valor) AS faturamento  
FROM vendas  
GROUP BY categoria  
ORDER BY faturamento DESC;  
\`\`\`

\#\# Semana 3 | Power BI \+ Power Query \+ DAX

\*\*Meta:\*\* transformar dados brutos em um dashboard de BI.

| Dia | Conteúdo | Prática |  
|---|---|---|  
| 15 | Interface do Power BI | Importar uma base |  
| 16 | Power Query | Limpar dados |  
| 17 | Tipos de dados e tratamento | Corrigir erros e duplicatas |  
| 18 | Modelagem | Criar relacionamentos |  
| 19 | DAX básico | Criar medidas |  
| 20 | KPIs e visualizações | Construir gráficos |  
| 21 | Dashboard | Montar projeto completo |

\#\#\# Power Query: prioridades

\- Remover colunas  
\- Alterar tipos de dados  
\- Remover duplicatas  
\- Substituir valores  
\- Tratar valores nulos  
\- Dividir e mesclar colunas  
\- Combinar arquivos

\#\#\# DAX: medidas iniciais

\`\`\`text  
Faturamento \= SUM(Vendas\[Valor\])  
\`\`\`

\`\`\`text  
Quantidade Vendas \= COUNTROWS(Vendas)  
\`\`\`

\`\`\`text  
Ticket Médio \=  
DIVIDE(  
    \[Faturamento\],  
    \[Quantidade Vendas\]  
)  
\`\`\`

Depois avance para \`CALCULATE\`, \`DISTINCTCOUNT\`, \`FILTER\`, \`IF\` e inteligência de tempo.

\*\*Projeto da semana:\*\* Dashboard Comercial com Faturamento, Ticket Médio, Quantidade de Vendas, Evolução Mensal, Vendas por Categoria e Top Produtos.

\#\# Semana 4 | Python para Análise de Dados \+ Projeto Integrado

\*\*Meta:\*\* usar Python como ferramenta analítica para manipular e explorar dados.

| Dia | Conteúdo | Prática |  
|---|---|---|  
| 22 | Python básico | Variáveis, listas e funções |  
| 23 | Jupyter Notebook | Criar notebook |  
| 24 | Pandas | Ler CSV e Excel |  
| 25 | DataFrames | Selecionar e filtrar dados |  
| 26 | Limpeza | Nulos e duplicados |  
| 27 | GroupBy | Criar análises |  
| 28 | Matplotlib | Visualizações |  
| 29 | Projeto integrado | Analisar uma base |  
| 30 | Portfólio | Documentar resultados |

Bibliotecas prioritárias:

\`\`\`python  
import pandas as pd  
import matplotlib.pyplot as plt  
\`\`\`

Exemplo:

\`\`\`python  
import pandas as pd

df \= pd.read\_csv("vendas.csv")

df.groupby("categoria")\["valor"\].sum()  
\`\`\`

\#\# Rotina diária

Para 1 hora de estudo:

\- \*\*20 min:\*\* teoria/aula  
\- \*\*30 min:\*\* exercícios na ferramenta  
\- \*\*10 min:\*\* registro do aprendizado

Use o modelo em \`anotacoes/semana-01.md\` para acompanhar sua evolução.

\#\# Fechamento do dia 30

O projeto final deve reunir Excel, SQL, Power Query, Power BI/DAX e Python em torno de uma mesma base, preferencialmente uma base de vendas. O objetivo é terminar o mês com algo concreto para apresentar em portfólio, e não apenas com cursos concluídos.  
