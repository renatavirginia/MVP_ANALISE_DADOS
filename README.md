# MVP - Impacto dos Jogos na Saude Mental

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/renatavirginia/MVP_ANALISE_DADOS/blob/main/MVP_Impacto_Jogos_Saude_Mental.ipynb)

## Sobre o Projeto

Este projeto investiga a relacao entre habitos de jogos eletronicos e indicadores de saude mental por meio de uma Analise Exploratoria de Dados (EDA). Utilizando um dataset sintetico com 100.000 registros e 39 variaveis, o trabalho explora se fatores como horas diarias de jogo, exposicao a jogos violentos e sessoes noturnas possuem correlacao com niveis de ansiedade, depressao, estresse e vicio.

## Hipoteses Investigadas

1. Jogadores com mais horas diarias de jogo apresentam niveis mais altos de ansiedade e depressao?
2. A exposicao a jogos violentos tem correlacao com maiores escores de agressividade?
3. Jogadores com melhores habitos de sono e exercicio apresentam menores indices de estresse?
4. Existe relacao entre o nivel de vicio em jogos e a produtividade academica/profissional?

## Dataset

| Informacao | Detalhe |
|---|---|
| **Fonte** | [Gaming and Mental Health - Kaggle](https://www.kaggle.com/datasets/sharmajicoder/gaming-and-mental-health) |
| **Registros** | 100.000 (amostra representativa) |
| **Atributos** | 39 variaveis |
| **Tipo** | Dados sinteticos |

As variaveis cobrem: dados demograficos, comportamento de jogo, indicadores de saude mental, estilo de vida, interacao social, desempenho academico/profissional e saude fisica.

## Estrutura da Analise

1. **Definicao do Problema** - Descricao, hipoteses e selecao dos dados
2. **Analise Exploratoria (EDA)** - Estatisticas descritivas, histogramas, boxplots, scatter plots e matriz de correlacao
3. **Pre-Processamento** - Traducao de colunas, one-hot encoding, padronizacao (StandardScaler), normalizacao (MinMaxScaler), K-Means e PCA
4. **Checklist de Qualidade** - Respostas as perguntas de validacao do dataset
5. **Conclusao** - Respostas as hipoteses, limitacoes e sugestoes futuras

## Principais Resultados

- As correlacoes entre horas de jogo e indicadores de saude mental foram **fracas**, limitacao inerente ao dataset sintetico
- A distribuicao de genero e equilibrada, permitindo comparacoes justas entre grupos
- O agrupamento **K-Means (K=3)** identificou perfis distintos de jogadores (casuais, moderados e hardcore)
- A visualizacao **PCA** demonstrou consistencia entre treino e teste, validando a generalizacao


## Tecnologias

| Categoria | Ferramentas |
|---|---|
| Manipulacao de Dados | Python, Pandas, NumPy |
| Visualizacao | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn (K-Means, PCA, StandardScaler, MinMaxScaler) |

