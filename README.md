# Data Science — Estudos e Exercícios

Coleção de exercícios pontuais de análise de dados e ciência de dados, cada um em
sua própria subpasta. São exercícios de estudo (não projetos de produção) —
reunidos aqui para não ficarem espalhados em dezenas de repositórios minúsculos.
Para projetos completos de portfólio, ver os repositórios "flagship" separados
(engenharia de dados, streaming, Data Vault).

## Exercícios

| Pasta | Sobre |
|---|---|
| `pandas-tratamento-dados/` | Tratamento e análise de dados com pandas |
| `avaliacao-filmes/` | Análise exploratória do dataset MovieLens (avaliações de filmes) |
| `predicao-credito/` | Modelo de predição de aprovação de crédito (dataset UCI Credit Approval) |
| `aviacao-federal-faa/` | Análise de acidentes aéreos (dataset da Federal Aviation Authority) |
| `bombeiros-nyc/` | Análise de dados do corpo de bombeiros de Nova York |
| `custo-publicidade-midia/` | Relação entre custo de publicidade por canal de mídia e vendas |
| `causas-mortalidade-ohio/` | Principais causas de mortalidade em Ohio (2012) |
| `analise-empresas-receita-federal/` | Tratamento de dados de empresas da Receita Federal |
| `datasets-ml-diversos/` | Datasets soltos usados em exercícios de Machine Learning |
| `eleicoes-2018/` | Análise da votação por seção eleitoral — Eleições 2018 (MG) |
| `marketing-campaign/` | Análise de uma campanha de marketing |
| `estatistica-com-python/` | Exercícios de estatística descritiva com Python |

## Sobre os dados grandes

Duas pastas usam datasets públicos grandes demais para versionar no Git — o
código está aqui, os dados baixam à parte:

- **`avaliacao-filmes/`**: inclui a amostra pequena oficial do
  [MovieLens (GroupLens)](https://grouplens.org/datasets/movielens/)
  (`ml-latest-small`). Para o dataset completo (`ml-latest`, ~1GB) ou o TMDB 5000
  (usado no notebook original), baixe direto do GroupLens/Kaggle.
- **`eleicoes-2018/`**: o notebook espera o CSV de votação por seção (MG, 2018),
  disponível nos [Dados Abertos do TSE](https://dadosabertos.tse.jus.br/).
